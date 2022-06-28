# demo-postman-2022

## Run newman with reporters
```
$npm i -g newman
$npm i -g newman-reporter-html
$newman run -d users.csv -n 5 -r cli,junit,html demo.postman_collection.json
```

## Run stubby
```
$npm i -g stubby
$stubby -d api.yml
```
