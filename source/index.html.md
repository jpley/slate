---
title: SIIM.IO API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - json

toc_footers:
  - made with <3 by <a href="https://siim.io" target="_blank">siim.io</a>

includes:
  - estimates
  - data_types
  - enums
  - return_codes
  - status_codes
  - errors

search: true
---

# API Overview

Welcome to the siim.io API! You can use our API to access siim.io API endpoints, which manage shipments and many tools you may need when you want to ship items.

Through the SIIM.IO API your application can retrieve and manage shipments. Our API is organized around REST, and designed to use resource oriented URLs and HTTP response codes to indicate API errors.

## Versioning

Our API is versioned and the version number is increased when there are any breaking changes.
The current version of the API is `v1`, and the value is passed as part of the URL of the request.

## Authentication

> To connect to the API, use this code in the header every request:

> `api-key: YOUR_API_KEY`

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "api-key: meowmeowmeow"
```

SIIM.IO uses API keys to allow access to the API. You can register a new SIIM.IO API key by sending an email to <a href="mailto:iwanttoplay@siim.io">iwanttoplay@siim.io</a>.

SIIM.IO expects for the API key to be included in all API requests to the server in a header that looks like the following:

`api-key: YOUR_API_KEY`

<aside class="notice">
You must replace <code>YOUR_API_KEY</code> with your personal API key.
</aside>
