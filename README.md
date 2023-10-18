# nmra-speedtest
Networkables Monitoring remote agent for speed testing

Example Run:
```
docker run \
  -d --rm \
  --name nmra-speedtest \
  -e PG_ORG_NAME="YOUR_CUSTOMER_ID" \
  -e PG_ORG_TOKEN="YOUR_SECRET_TOKEN" \
  -e PG_SITE_NAME="YOUR_SITE_NAME" \
  ghcr.io/networkables/nmra-speedtest:1.2.0
```
