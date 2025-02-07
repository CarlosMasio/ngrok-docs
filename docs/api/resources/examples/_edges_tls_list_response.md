<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-07T10:14:36Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2si0qJimrGFTFHqwtfHTh3KIHPK",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2si0qJimrGFTFHqwtfHTh3KIHPK"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2si0onK5kGVdrXGOdfVKmBktz0g",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2si0onK5kGVdrXGOdfVKmBktz0g"
				},
				"enabled": true
			},
			"created_at": "2025-02-07T10:14:24Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2si0olCwg5ziCbzEeRGn2d5lllT",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2si0olCwg5ziCbzEeRGn2d5lllT"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
