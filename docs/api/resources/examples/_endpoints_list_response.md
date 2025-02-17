<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-17T10:09:00Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tAFNvUPMEq0mmzX306fgqX8was",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tAFNvUPMEq0mmzX306fgqX8was"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tAFOdumpIKBZ8GsF2sqz6k6Z7p",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-17T10:09:00Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tAFOdumpIKBZ8GsF2sqz6k6Z7p",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-17T10:08:58Z",
			"hostport": "adbc3ae44c16.ngrok.paid:443",
			"id": "ep_2tAFOHj9DmFDuN6RjOArHp2Djd8",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tAFLr0qVy5FS3kxvzEppppICAm",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://adbc3ae44c16.ngrok.paid",
			"tunnel": {
				"id": "tn_2tAFOHj9DmFDuN6RjOArHp2Djd8",
				"uri": "https://api.ngrok.com/tunnels/tn_2tAFOHj9DmFDuN6RjOArHp2Djd8"
			},
			"tunnel_session": {
				"id": "ts_2tAFONq4p8mPASUG4rX9LxLDQY9",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tAFONq4p8mPASUG4rX9LxLDQY9"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-17T10:08:58Z",
			"upstream_url": "http://localhost:80",
			"url": "https://adbc3ae44c16.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-17T10:08:55Z",
			"domain": {
				"id": "rd_2tAFNvUPMEq0mmzX306fgqX8was",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tAFNvUPMEq0mmzX306fgqX8was"
			},
			"edge": {
				"id": "edgtls_2tAFNvymXGMgLZtONE2Peosu3Qs",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tAFNvymXGMgLZtONE2Peosu3Qs"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tAFNyRY0KvhV09CmKaHWiuyNSI",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-17T10:08:55Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
