<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-17T10:09:05Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tAFPDqPA4JyQ4ETBsFEAWPYw2o",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tAFPDqPA4JyQ4ETBsFEAWPYw2o"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tAFNwDcImJEDnFBouVlQzyBJwZ",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tAFNwDcImJEDnFBouVlQzyBJwZ"
				},
				"enabled": true
			},
			"created_at": "2025-02-17T10:08:55Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tAFNvymXGMgLZtONE2Peosu3Qs",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tAFNvymXGMgLZtONE2Peosu3Qs"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
