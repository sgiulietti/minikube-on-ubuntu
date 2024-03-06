## Install and configure Minikube on Ubuntu OS

Step 1: Install minikube on Ubuntu.
Execute on terminal the following commands:

    curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
    sudo install minikube-linux-amd64 /usr/local/bin/minikube

Step 2: Create a minikube cluster
Execute on terminal the following commands:

    minikube start

Step 3: Install Docker for Ubuntu
Visit the official website of Docker:

    https://docs.docker.com/desktop/install/ubuntu/

Step 4: Start a minikube cluster
Execute on terminal the following commands:

    minikube start –driver docker

Step 5: Get available kubectl for Ubuntu
Execute on terminal the following commands:

    minikube kubectl – get pods -A
  
