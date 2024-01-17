<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"issuer":{"allow_list":[{"value":"https://dev-72114178.okta.com/oauth2/default"}]},"audience":{"allow_list":[{"value":"api://default"}]},"http":{"tokens":[{"type":"at+jwt","method":"header","name":"Authorization","prefix":"Bearer "}]},"jws":{"allowed_algorithms":["RS256","ES256"],"keys":{"sources":{"additional_jkus":["https://dev-72114178.okta.com/oauth2/default/v1/keys"]}}}}' \
https://api.ngrok.com/edges/https/edghts_2b6JkFZHKTqJhaHMHwDau4EABCr/routes/edghtsrt_2b6JkCkQfxS7RAf3rJMbksDgwcg/jwt_validation
```
