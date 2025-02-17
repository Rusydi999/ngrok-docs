<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-17T10:08:39Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.2jgbmy3epbljgabfn.local-ngrok-cname.com",
			"created_at": "2025-02-17T10:08:39Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tAFLzC6kNnVaHKUyJDnqI21Obo",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tAFLzC6kNnVaHKUyJDnqI21Obo"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tAFLveE0qO4L202wYQ75TwYMSk",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tAFLveE0qO4L202wYQ75TwYMSk"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.2jgbmy3epbljgabfn.local-ngrok-cname.com",
			"created_at": "2025-02-17T10:08:39Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tAFLwMhKsBdAWqy5Yx4BfEdw9P",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tAFLwMhKsBdAWqy5Yx4BfEdw9P"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
