# Errors

<aside class="notice">This error section might change.</aside>

The API uses the following error codes for any response that isn't a `200` status code:

Error Code | Meaning
---------- | -------
`400` | Bad Request -- Your request sucks
`401` | Unauthorized -- Your `APIKEY`, `JWT` or 2FA `auth_code` is wrong
`404` | Invalid Request -- The endpoint doesn't exist
`403` | Forbidden -- The endpoint is hidden for some reason
`500` | Internal Server Error -- We had a problem with our server. Try again later.
`503` | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
