# LogicalDoc

## setup
```
docker-compose up -d
```

https://docs.logicaldoc.com/resources/wsdoc/rest/8.6/index.html#/

## login

```
curl -X GET "http://localhost:8080/services/rest/auth/login?u=admin&pw=admin" -H  "accept: application/json" -H  "Authorization: Basic YWRtaW46YWRtaW4="
```

## get docs

```
curl -X GET "http://localhost:8080/services/rest/document/list?folderId=100" -H  "accept: application/json" -H  "Authorization: Basic YWRtaW46YWRtaW4="
```

## get folder listChildren

```
curl -X GET "http://localhost:8080/services/rest/folder/listChildren?folderId=4" -H  "accept: application/json" -H  "Authorization: Basic YWRtaW46YWRtaW4="
```
