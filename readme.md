After installing minikube and kubectl

run the following commands in order

1. kubectl apply -f mongo-sercret.yaml
2. kubectl apply -f mongo-configmap.yaml
3. kubectl apply -f mongodb.yaml
4. kubectl apply -f mongo-express.yaml

Now check if deployments are up and running with
1. kubectl get all

After all deployments are successfully up run
1. minikube service mongo-express-service

Your browser should open and you will see a UI for basic CRUD operations in mongodb