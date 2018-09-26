## Dashboard Views for APIs

Other available views for your API include:

- **Settings**: lists the settings for your API, some of which are editable. In this section, you can change the token expiration time and enable offline access (so that Auth0 will allow applications to ask for Refresh Tokens for this API). For details, see [API Settings](/api-auth/references/dashboard/api-settings).

- **Scopes**: allows you to define the scopes for your API by setting scope names and a descriptions.

- **Machine to Machine Applications**: lists all applications for which the **Client Credentials** grant is **enabled**. (By default, this grant is **enabled* for [Regular Web Applications](/applications/webapps) and [Machine to Machine Applications](/applications/machine-to-machine)). You can authorize any listed application to request Access Tokens for your API. Optionally, you can select a subset of the defined scopes to limit an authorized application's access to your API. 

- **Test**: allows you to execute a sample Client Credentials flow with any of the authorized applications so you can check that everything is working as expected.
