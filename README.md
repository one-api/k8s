# control plane
curl -sSL https://raw.githubusercontent.com/one-api/k8s/main/install.sh | sudo sh


# kubectl
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
sudo install kubectl /usr/local/bin/kubectl
