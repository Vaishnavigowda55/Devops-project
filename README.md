# Docker with kubernetes 
#new one

##### connect to server
##### sudo yum update 
##### sudo yum install git 
##### sudo yum install docker 
##### sudo usermod -aG docker $USER 
##### newgrp docker 
##### sudo systemctl start docker 
##### sudo git clone https://github.com/Vaishnavigowda55/Docker-with-kubernetes.git
##### cd Docker-with-kubernetes
##### sudo chmod +x install.sh
##### sudo ./install.sh
##### sudo chmod +x kind-conifg.yml
##### kind create cluster --config kind-conifg.yml --name eks-cluster 
