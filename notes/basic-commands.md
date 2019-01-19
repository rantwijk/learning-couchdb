curl http://127.0.0.1:5984
curl 'http://couchdb:5984/_uuids?count=5'
curl -X PUT 'http:/127.0.0.1:5984/demo/doc' -d '{"motto": "I love gnomes"}'
curl -X PUT http://127.0.0.1:5984/demo
RESPONSE: {"ok":true}

curl -X GET http://127.0.0.1:5984/demo


