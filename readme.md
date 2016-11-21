# start

```sh
docker-compose build
docker-compose up
echo "deploy.test.testservice:1|c" | nc -w 1 -u localhost 8125
echo "deploy.test.other-service:1|c" | nc -w 1 -u localhost 8125
```

grafana:
user: admin
pass: secret
```http://localhost:3000/```
