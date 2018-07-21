
![構成図](https://qiita-image-store.s3.amazonaws.com/0/235100/f72eb4b2-d0ad-5515-2c0b-ab9aa7a00b73.png "構成図")

https://neko-gae-multi-service.appspot.com/
https://neko-gae-multi-service.appspot.com/php

## work
docker run --rm -v `pwd`:/code -it google/cloud-sdk:latest bash

## default service deploy
gcloud app deploy --project neko-gae-multi-service --version 1 app.yaml dispatch.yaml

## php service deploy
gcloud app deploy --project neko-gae-multi-service --version 1 app.yaml
