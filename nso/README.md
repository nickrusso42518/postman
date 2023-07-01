# Cisco Network Services Orchestrator (NSO)
Postman collection to interact with the Cisco NSO RESTCONF and JSON RPC APIs.
Includes API calls for several custom NSO service packages.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There are four environments included with the collection:
  * `always_on`: Contains host/credential information for the Cisco DevNet
    "Always On" NSO instance. This does not require a reservation nor a VPN
    connection and is publicly accessible over the Internet.
  * `reservable_dev`: Contains host/credential information for the Cisco DevNet
    reservable NSO instance, which require a DevNet account and
    valid reservation to utilize. This connects to the DevBox and only works
    if you've manually installed NSO following the various Learning Labs.
  * `reservable_prod`: Contains host/credential information for the Cisco DevNet
    reservable NSO instance, which require a DevNet account and
    valid reservation to utilize. This works out of the box and allows you
    to interact with the pre-built NSO instance immediately.
  * `local_install`: Contains host/credential information for an NSO instance
    that you've locally installed. You must change the NSO host address, but
    the other information should be correct by default.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2023 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
