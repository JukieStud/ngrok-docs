<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"tls_edges": [
		{
			"id": "edgtls_2b6JkhPRrzPOfhotsy0AyQBcGdi",
			"description": "acme tls edge",
			"metadata": "{\"environment\": \"staging\"}",
			"created_at": "2024-01-17T22:15:39Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2b6JkhPRrzPOfhotsy0AyQBcGdi",
			"hostports": ["example.com:443"],
			"backend": null,
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policies": null
		},
		{
			"id": "edgtls_2b6JjD0C3KxrMVi8qD1oUUVmiVK",
			"description": "acme tls edge",
			"created_at": "2024-01-17T22:15:27Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2b6JjD0C3KxrMVi8qD1oUUVmiVK",
			"hostports": ["endpoint-example.com:443"],
			"backend": {
				"enabled": true,
				"backend": {
					"id": "bkdhr_2b6JjCSOL5ps6i5pcMXrXsw7l2B",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2b6JjCSOL5ps6i5pcMXrXsw7l2B"
				}
			},
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policies": null
		}
	],
	"uri": "https://api.ngrok.com/edges/tls",
	"next_page_uri": null
}
```
