<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme weighted","metadata":"{\"environment\": \"staging\"}","backends":{"bkdhr_2b6Jjxhs9QIYwJzyfI9TZIqMtCD":0,"bkdhr_2b6JjytAKQEbCiusjRTmNoHrwlM":1}}' \
https://api.ngrok.com/backends/weighted
```
