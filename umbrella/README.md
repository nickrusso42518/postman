# Cisco Umbrella for SAUTO
Postman collection to programmatically interact with Cisco Umbrella.
Includes Reporting, Enforcement, Investigate, and Management APIs. These
APIs have been identified as "legacy", so the collection also includes
new "unified" v2 API example requests and responses.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There is one environment included with the collection:
  * `reservable`: Contains a placeholder for the all of the variables
    needed to interact with all Umbrella APIs. The reservable
    instance is available within both dCloud and DevNet, and only supports
    the Reporting, Enforcement, and Management APIs. There is no public
    way to access the Investigate API at the time of this writing.
    The variables in this environment are as follows:
    * `org_id`: The organization ID, mostly for the Reporting API
    * `report_api_key`: Reporting API key (basic auth username)
    * `report_api_secret`: Reporting API secret (basic auth password)
    * `enforce_cust_key`: Enforcement API key (query param)
    * `investigate_api_key`: Investigate API key (authz token)
    * `mgmt_key`: Management API key (basic auth username)
    * `mgmt_secret`: Management API secret (basic auth password)
    * `v2_username`: Unified v2 API keyID (basic auth username)
    * `v2_password`: Unified v2 API secret (basic auth password)
    * `v2_token`: Unified v2 API token (authz bearer)

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2023 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
