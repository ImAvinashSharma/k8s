# k8s
kubectl create namespace ingress-nginx
kubectl config set-context --current --namespace=ingress-nginx
helm repo add ingress-nginx <https://kubernetes.github.io/ingress-nginx>
helm repo update
helm install ingress-nginx ingress-nginx/ingress-nginx
