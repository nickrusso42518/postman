# Cisco Smart Licensing API
Postman collection to manage Cisco smart licenses.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There is one environment included with the collection,
  * `smartlic`: Contains host/credential information which users can
    populate. The `client_id` and `client_secret` are used to obtain
    a token. The `client_token` is used for all subsequent requests.
    The `domain_id` is specified on your smart account which scopes
    your requests. Be sure your Cisco login ID has access to that
    specific domain.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2023 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
