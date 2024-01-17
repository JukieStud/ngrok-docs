<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"reserved_domains": [
		{
			"id": "rd_2b6JhEmnEcbeShfRelTtnXqrfGX",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2b6JhEmnEcbeShfRelTtnXqrfGX",
			"created_at": "2024-01-17T22:15:11Z",
			"domain": "myapp.mydomain.com",
			"region": "",
			"cname_target": "2udamkamcl8pjmrff.4laphcsbnwp442rye.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": {
				"id": "cert_2b6JhEmXDrQcPhns6F5MGmKBtGo",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2b6JhEmXDrQcPhns6F5MGmKBtGo"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"acme_challenge_cname_target": null
		},
		{
			"id": "rd_2b6JhBn8z6BdG4hgp3fs7v9WJdv",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2b6JhBn8z6BdG4hgp3fs7v9WJdv",
			"created_at": "2024-01-17T22:15:11Z",
			"description": "Device 0001 Dashboard",
			"metadata": "{\"service\": \"dashboard\"}",
			"domain": "manage-0001.app.example.com",
			"region": "",
			"cname_target": "4mgkuazanf1yq46m3.4laphcsbnwp442rye.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"renews_at": null,
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"started_at": "2024-01-17T22:15:11Z",
					"retries_at": null
				}
			},
			"acme_challenge_cname_target": null
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains",
	"next_page_uri": null
}
```
