﻿# Halforbit ApiClient

## Release Notes

### 2020-08-27

#### 1.0.43

- Added a virtual `GetHttpClient` method to `RequestClient`, to allow sub classes to override the provisioning of `HttpClient`.

### 2020-07-07

#### 1.0.38

- Fixed a bug where multiple authorization requests would be dispatched at once when using bearer token authentication in parallel.

- Added `.BearerTokenAuthorizationWithBaseUrl()` `Request` extension method which allows the base URL to be specified from the authorization result.