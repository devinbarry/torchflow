# How to login and push

## Tag image

`docker tag 0af3a97c918f softwrdev/torchflow:latest-py37`

## Login to Docker hub

After this you will be prompted for a password:

`docker login --username=softwrdev`

## Push image

`docker push softwrdev/torchflow:latest-py37`
