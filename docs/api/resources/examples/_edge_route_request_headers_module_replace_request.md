<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"x-frontend":"ngrok"},"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2b6JkQ5sJGaZ9XPsipBcNuEwPLV/routes/edghtsrt_2b6JkQCjxnn9zkFqtSH7UfkROwZ/request_headers
```
