<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2si0mi50j0iNEOYz2DVOwoR4Gmd",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2si0mi50j0iNEOYz2DVOwoR4Gmd"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.4czzfzpgsl8ywxdq7.local-ngrok-cname.com",
			"created_at": "2025-02-07T10:14:08Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2si0mu5rWTrIyP61PI34Q76zmhx",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2si0mu5rWTrIyP61PI34Q76zmhx"
		},
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
					"started_at": "2025-02-07T10:14:09Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.4czzfzpgsl8ywxdq7.local-ngrok-cname.com",
			"created_at": "2025-02-07T10:14:09Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2si0mtns6Dv1dINldWHPLQmc7xX",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2si0mtns6Dv1dINldWHPLQmc7xX"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
