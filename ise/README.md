# Cisco Identity Services Engine (ISE) and pxGrid
Postman collection to interact with the Cisco ISE APIs:
  * External RESTful Services (ERS)
  * pxGrid Control
  * pxGrid REST/data collection
  * Initial setup for pxGrid websockets/STOMP for streaming telemetry
  * Monitoring API (mnt)

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There are two environments included with the collection,
  * `devnet`: Contains host/credential information for the Cisco DevNet
    reservable pxGrid instance, which requires a DevNet account and
    valid reservation to utilize. Password and secret placeholders can be
    updated along the way to simplify API interactions. The pxGrid sandbox
    can be used for ERS, pxGrid, and mnt APIs. ERS must be manually
    enabled but all the pxGrid services are enabled from the beginning.
  * `dcloud`: Contains host/credential information for the Cisco dCloud
    ISE demo which comes pre-built with many other security components,
    including a test client (useful for MNT API testing).

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2021 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
