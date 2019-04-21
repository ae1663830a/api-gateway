# API-GATEWAY

### Get configured routes:

```bash
curl http://192.168.0.20:8080/management/routes | jq
```

* Response example:
```code
{
  "/config/**": "config-server",
  "/api/order/**": "order-service",
  "/eureka-server-1/**": "eureka-server-1"
}
```