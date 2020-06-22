# Cisco Umbrella for SAUTO
Postman collection to programmatically interact with Cisco Umbrella.
Includes Reporting, Enforcement, and Investigate APIs.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There is one environment included with the collection:
  * `reservable`: Contains a placeholder for the all of the variables
    needed to interact with all three Umbrella APIs. The reservable
    instance is available within dCloud, not DevNet, and only supports
    the Reporting and Enforcement APIs. There is no publicly-accessible
    way to access the Investigate API at the time of this writing.
    The variables in this environment are as follows:
    * `org_id`: The organization ID, mostly for the Reporting API
    * `report_api_key`: Reporting API key (basic auth username)
    * `report_api_secret`: Reporting API secret (basic auth password)
    * `enforce_cust_key`: Enforcement API key (query param)
    * `investigate_api_key`: Investigate API key (authz token)

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2020 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
