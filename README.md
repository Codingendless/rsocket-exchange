# RSocket Sample for RSocketExchange

Start server with profile `server` or with env `RSOCKET_EXCHANGE_PROFILE=server`

Start client with profile `client` or with env `RSOCKET_EXCHANGE_PROFILE=client`

# Test

```http request
GET http://localhost:8081/question?current=1
Content-Type: application/json
```