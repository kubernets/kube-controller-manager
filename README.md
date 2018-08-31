# kube-controller-manager

github addr [https://github.com/kubernets/kube-controller-manager](https://github.com/kubernets/kube-controller-manager)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/kube-controller-manager/raw/master/get-kube-controller-manager-image.sh

## Arch and Version

- [**amd64** v1.11.2](https://hub.docker.com/r/kubernets/kube-controller-manager-amd64)

    > docker pull kubernets/kube-controller-manager-amd64:v1.11.2

    > docker tag kubernets/kube-controller-manager-amd64:v1.11.2 gcr.io/google-containers/kube-controller-manager-amd64:v1.11.2 

    > docker rmi kubernets/kube-controller-manager-amd64:v1.11.2
