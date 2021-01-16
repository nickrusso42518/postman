# Arista EOS
Postman collection to interact with the Arista EOS eAPI
and RESTCONF API. Note that the EOS RESTCONF API is very limited
at the time of this writing.

## Usage
Be sure to check the folder descriptions for a summary of each workflow,
and note that each request has at least one "example" showing the response
format.

## Environments
There is one environment included with the collection:
  * `arista_eos`: Contains a general environment template for a
    privately-built EOS instance (not a public sandbox). The eAPI
    supports HTTP and HTTPS but RESTCONF only supports HTTPS. Both
    APIs use HTTP basic user via `username` and `password` variables.

You can add custom environments for your own networks as you see fit.

## Copyright
Copyright 2021 Nicholas Russo.

Consumers may download and edit any document in this collection for personal
use only. Downloading and editing any document in this collection for
redistribution is prohibited.

All rights reserved.
