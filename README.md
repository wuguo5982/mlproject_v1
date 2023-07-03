### End to End Machine Learning Project (for practice purpose only)
## Azure deployment 
1. Container registry.
2. Docker set up in local and push to container registry.
3. Azure Web app with container.
4. Configure the github deployment center. 


## Run from terminal:

docker build -t testdockeraz.azurecr.io/mltest:latest .
docker login testdockeraz.azurecr.io
docker push testdockeraz.azurecr.io/mltest:latest

Please refer to https://www.youtube.com/watch?v=g687fRBNNGo&list=PLZoTAELRMXVPS-dOaVbAux22vzqdgoGhG&index=14&t=560s
