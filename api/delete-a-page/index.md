# Title: Delete a page
<!-- Position: 6 -->
---
Bludit API provides the features to edit a page.

All request to the API need the `API Token`, you can find the token in the settings of the plugin.

All request to the API to write content is necessary to provide an `Authorization Token`.
This token is only available on users with the role **ADMINISTRATOR**. You can get the `Authorization Token` on **Admin panel > Manage > Users > {Username} > Edit User > Authentication Token > Token**.

<h2 id="request">Request</h2>

- Endpoint: `/api/pages/<key>`
- Method: `DELETE`
- Content-Type: `application/json`
- Content

```
{
	"token": "24a8857ed78a8c89a91c99afd503afa7",
	"authentication": "193569a9d341624e967486efb3d36d75"
}
```

<h2 id="response">Response</h2>

- HTTP Code: `200`
- Content-Type: `application/json`
- Content

```
{
	"status": "0",
	"message": "Page deleted."
}
```
