# Cisco SD-WAN for ENAUTO
Postman collection to interact with the Cisco SD-WAN REST API.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There are three environments included with the collection:
  * `always_on_old`: Contains host/credential information for the Cisco DevNet
    "Always On" SD-WAN instance, which is publicly available to all. This
    is an old version of the sandbox and will likely be decommissioned soon.
  * `always_on_new`: Contains host/credential information for the Cisco DevNet
    "Always On" SD-WAN instance, which is publicly available to all. This
    is a new version of the sandbox and should be used before the old one.
    Version 19.2+ requires the `X-XSRF-TOKEN` header for any non-GET requests.
  * `reservable`: Contains host/credential information for the Cisco DevNet
    reservable SD-WAN instance, which require a DevNet account and
    valid reservation to utilize. This instance is fully configurable.
    Version 19.2+ requires the `X-XSRF-TOKEN` header for any non-GET requests.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2021 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
