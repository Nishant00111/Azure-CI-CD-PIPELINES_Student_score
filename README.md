## End to End MAchine Learning Project

### HERE , use the container registry in Azure to store the Docker Image 
### Credentials of Container Registry --
#### Username: testdockernishu.azurecr.io
#### Password: NLmwim3d/isWMA9KCyWGCr6rEjyZsEuYQOiRm8l5wk+ACRABOoZp

## Run from terminal:

docker build -t testdockernishu.azurecr.io/mltest:latest .

docker login testdockernishu.azurecr.io

docker push testdockernishu.azurecr.io/mltest:latest
