# Install minikube and kubernetes
minikube start
minikube dashboard

# Add the ingress facility to minikube
minikube addons enable ingress

# kindly make the changes in "sudo nano /etc/hosts" as 
192.168.49.2    sample-ingress.com

