# Kubernetes-MongoDb

# Namespace

kubectl apply -f mongodb-namespaces.yaml

kubectl get ns 

# Mongo Db Secret

kubectl apply -f mongodb-secret.yaml

kubectl get secret -n mongo-k8s

# Mongo Db Config Map

kubectl apply -f mongodb-configmap.yaml

kubectl get configmap -n mongo-k8s

# Mongo Db Deployment

kubectl apply -f mongodb.deployment.yaml

kubectl get deployment -n mongo-k8s

# Get Pods, PersistentVolumeClaim, PersistentVolume

kubectl get pods -n mongo-k8s

kubectl get pvc -n mongo-k8s

kubectl get pv -n mongo-k8s

# Mongo Express Deployment

kubectl apply -f mongodb-express-deployment.yaml

# Get Services, Deployments, Pods

kubectl get service -n mongo-k8s

kubectl get deployment -n mongo-k8s

kubectl get pods -n mongo-k8s
