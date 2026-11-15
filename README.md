# ff-api-endpoints

1. http://78.154.103.35:14430/ - FF Guest Level filter
2. http://78.154.103.37:14674/ - FF Profile and Outfit Generator
```
GET /api?uid=387531739 (Banner without Info)
GET /banner?uid=387531739 (Banner with Info)
GET /outfit?uid=387531739
GET /status
```
3. http://78.154.103.39:11168/ - FF Info
```
GET /info?uid=387531739
```
4. http://78.154.103.23:12698/ - FF JWT
```
GET /token?uid=123456789&password=ABCD
```
