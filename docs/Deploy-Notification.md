# Deploy notification services and API gateway

## Start the micro services

1.Start the MongoDB
```bash
mongod
```
2.Start the redis
```bash
redis-server
```
3.Run the notification service.
```bash
cd troph-services/notification
go run main.go
```
4.Run api service.
```bash
cd troph-services/api
go run main.go
```
5.Set the api gate way hander as api
```bash
micro api --handler=api
```
More information about the API end point -> [API Documentation](Welcome-API/NotificationPush-API)
