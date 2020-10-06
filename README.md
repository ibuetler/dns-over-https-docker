# dns-over-https
* updated repo with docker-compose.yml and build.sh 

## Build Docker Image
```
bash build.sh
```

## Start Docker
```
docker-compose up -d
```

## Use DNS over HTTPS
```
dig -p 5380 @localhost www.ost.ch
```

## DoH Config
* doh-client.conf

