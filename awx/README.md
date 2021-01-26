# Ansible AWX/Tower
Postman collection to interact with the Ansible AWX (open source) or
RedHat Tower (commercial product) job management system.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

To use the specific samples requests in this collection, be sure to perform
the following modifications to the standard installation process:

1. Uncomment the `project_data_dir=/var/lib/awx/projects` line from
   the `awx/installer/inventory` file before installing. This will enable
   the use of the `manual` SCM type if remote repositories are not available.

2. After installation, create a simple test playbook `pb.yml` which logs into
   the Cisco DevNet always-on CSR1000v to collect the version information.

```
$ mkdir -p /var/lib/awx/projects/devnet_code
$ cat > /var/lib/awx/projects/devnet_code/pb.yml
---
- name: "Get version from DevNet sandbox CSR1000v"
  hosts: "all"
  gather_facts: false
  tasks:
    - name: "Collect IOS-XE version"
      ios_command:
        commands: "show version | include Software"
      register: "result"

    - name: "Print IOS-XE version"
      debug:
        var: "result.stdout[0]"
...
(Control+D)
```

## Environments
There is one environment included with the collection:
  * `awx`: This environment assumes you've built a private AWX instance
    using a supported installation method, such as docker, kubernetes,
    or openshift. The API supports HTTP basic auth or token-based auth.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2021 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
