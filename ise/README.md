# Cisco Identity Services Engine (ISE) and pxGrid for SAUTO
Postman collection to interact with the Cisco ISE APIs:
  * External RESTful Services (ERS)
  * pxGrid Control
  * pxGrid REST/data collection
  * Initial setup for pxGrid websockets/STOMP for streaming telemetry

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There is one environment included with the collection, as the pxGrid sandbox
can be used for both ERS and pxGrid with little effort. ERS must be manually
enabled but all the pxGrid services are enabled from the beginning.
  * `reservable`: Contains host/credential information for the Cisco DevNet
    reservable pxGrid instance, which requires a DevNet account and
    valid reservation to utilize. Password and secret placeholders can be
    updated along the way to simplify API interactions.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2020 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
