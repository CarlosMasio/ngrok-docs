<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-07T10:14:30Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2si0omJFcdpMJotT35YPzqlBwYF",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2si0omJFcdpMJotT35YPzqlBwYF"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2si0pRmAN3E6m9vYrYFBP9Jvetd",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-07T10:14:30Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2si0pRmAN3E6m9vYrYFBP9Jvetd",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-07T10:14:28Z",
			"hostport": "40bc3050cb46.ngrok.paid:443",
			"id": "ep_2si0pFiPRLJjRQFd3sNg34lhPk8",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2si0mnPsPtyaNf42cSwmnjGcnN2",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://40bc3050cb46.ngrok.paid",
			"tunnel": {
				"id": "tn_2si0pFiPRLJjRQFd3sNg34lhPk8",
				"uri": "https://api.ngrok.com/tunnels/tn_2si0pFiPRLJjRQFd3sNg34lhPk8"
			},
			"tunnel_session": {
				"id": "ts_2si0pIOHAFvFNGpd4mQQHrlVJrL",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2si0pIOHAFvFNGpd4mQQHrlVJrL"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-07T10:14:28Z",
			"upstream_url": "http://localhost:80",
			"url": "https://40bc3050cb46.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-07T10:14:25Z",
			"domain": {
				"id": "rd_2si0omJFcdpMJotT35YPzqlBwYF",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2si0omJFcdpMJotT35YPzqlBwYF"
			},
			"edge": {
				"id": "edgtls_2si0olCwg5ziCbzEeRGn2d5lllT",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2si0olCwg5ziCbzEeRGn2d5lllT"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2si0okunlNkfdkf5raWcKCA5oz4",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-07T10:14:25Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
