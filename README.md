## Build
```shell
docker build -t zxdanielwang/cicdworkshop . --platform linux/amd64
```

## (Optional) Tag
```shell
docker tag zxdanielwang/cicdworkshop:latest public.ecr.aws/g0i8g9c7/cicdworkshop:latest
```

## (Optional) Push
```shell
docker push public.ecr.aws/g0i8g9c7/cicdworkshop:latest
```

## Run
```shell
docker run -p 8000:8000 zxdanielwang/cicdworkshop
```
