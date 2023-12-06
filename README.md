⚠️⚠️⚠️ This library is no longer updated. For an updated spec, use the following curl: ⚠️⚠️⚠️

```
curl -X GET \
  'https://api.vimeo.com/?openapi=1' \
  -H 'Accept: application/json;version=3.4' \
  -H 'Authorization: bearer YOUR_BEARER_TOKEN'
```

# Vimeo + OpenAPI

<img src="https://user-images.githubusercontent.com/33762/49821892-8c1dc000-fd49-11e8-93e3-98c7ddd9a654.png" width="400" />

Our OpenAPI specification powers the [Vimeo API Reference](https://developer.vimeo.com/api/reference) pages and API playground.

For an updated spec, make the following request:
```
curl -X GET \
  'https://api.vimeo.com/?openapi=1' \
  -H 'Accept: application/json;version=3.4' \
  -H 'Authorization: bearer YOUR_BEARER_TOKEN'
```

If you also wish to receive a copy of the specification for a different API version (version 3.4 is our latest public default), you can do so by changing your `Accept` header to pull a copy appropriate for that version.

## Support
If you have any questions or problems, [contact us](https://vimeo.com/help/contact).
