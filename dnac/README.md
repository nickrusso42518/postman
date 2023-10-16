# Cisco DNA Center for ENAUTO
Postman collection to interact with the Cisco DNA Center REST API.
Now includes Software Defined Access (SDA) workflow calls.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There are three environments included with the collection:
  * `always_on`: Contains host/credential information for the Cisco DevNet
    "Always On" DNA Center instance, which is publicly available to all.
  * `reservable`: Contains host/credential information for the Cisco DevNet
    reservable DNA Center instance, which require a DevNet account and
    valid reservation to utilize.
  * `dcloud_ent_hw`: Contains host/credential information for the Cisco dCloud
    enterprise hardware (v4) lab. Note that this DNAC instance has almost no
    configuration pre-staged on it.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2023 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
