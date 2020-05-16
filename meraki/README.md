# Cisco Meraki for ENAUTO
Postman collection to interact with the Cisco Meraki REST API.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format. Note that the MV Sense and external captive portal APIs can be used
in some DevNet sandboxes, but seeing their impact is difficult without real
hardware. I've included example responses from DevNet and personal labs.

## Updates
On 15 May 2020, I discovered that Meraki changed their main API host
from `dashboard.meraki.com` to `api.meraki.com`. The contents of the URL
and subsequent REST resources appear to be unchanged. This collection
now includes example redirection responses, along with updated URLs
for all other requests.

## Environments
There are two environments included with the collection:
  * `always_on`: Contains the API key string for the Cisco DevNet
    "Always On" Meraki instance, which is publicly available to all.
  * `reservable`: Contains a sample API key string for the Cisco DevNet
    reservable Meraki instance, which requires a DevNet account and
    valid reservation to utilize. This will change with every reservation,
    so be sure to manually update this value after generating a Meraki
    API key: https://documentation.meraki.com/zGeneral_Administration/Other_Topics/The_Cisco_Meraki_Dashboard_API 

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2020 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
