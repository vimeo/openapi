# Vimeo + OpenAPI

This repository contains an [OpenAPI specification](https://www.openapis.org/) for the the latest version of the Vimeo API.

Our OpenAPI specification powers the [Vimeo API Reference](https://developer.vimeo.com/api/reference) pages and API playground.

## Updates
This repository will be updated automatically every Friday (if there are changes), but if you'd like to get the latest changes, you can do so by making a request to the following API endpoint:

```
curl -X GET \
  'https://api.vimeo.com/?openapi=1' \
  -H 'Accept: application/json;version=3.4' \
  -H 'Authorization: bearer YOUR_BEARER_TOKEN'
```

If you also wish to receive a copy of the specification for a different API version (version 3.4 is our latest public default), you can do so by changing your `Accept` header to pull a copy appropriate for that version.

## Tests
Currently we utilize [Speccy](https://github.com/wework/speccy) for running a gamut of validation and standards checks:

```
npm test
```

## Support
If you have any questions or problems, create a [ticket](https://github.com/vimeo/openapi/issues) or [contact us](https://vimeo.com/help/contact).
