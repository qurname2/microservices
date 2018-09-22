#microservices

Raising the instance in gce after receiving the credentials.json
```
docker-machine create --driver google --google-project id-your-project --google-zone europe-west1-b --google-machine-type f1-micro --google-machine-image $(gcloud compute images list --filter ubuntu-1604-lts --uri|grep v20180911) docker-host 
```
