# CentOS7.4_1708_kubernetes_1.9.3
CentOS7.4_1708_kubernetes_1.9.3

[https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-init/](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-init/)



## pull镜像打tag

kube-scheduler-amd64:v1.9.3
kube-proxy-amd64:v1.9.3
kube-controller-manager-amd64:v1.9.3
kube-apiserver-amd64:v1.9.3
etcd-amd64:3.1.10
pause-amd64:3.0 




####  kube-scheduler-amd64:v1.9.3
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-scheduler-amd64_1.9.3

docker tag ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-scheduler-amd64_1.9.3 gcr.io/google_containers/kube-scheduler-amd64:v1.9.3


#### kube-proxy-amd64:v1.9.3
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-proxy-amd64_1.9.3

docker tag ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-proxy-amd64_1.9.3  gcr.io/google_containers/kube-proxy-amd64:v1.9.3




####  kube-controller-manager-amd64:v1.9.3
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-controller-manager-amd64_1.9.3  

 docker tag ibackchina2018/centos7.4_1708_kubernetes_1.9.3:kube-controller-manager-amd64_1.9.3  gcr.io/google_containers/kube-controller-manager-amd64:v1.9.3



####  apiserver-amd64_1.9.3
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:apiserver-amd64_1.9.3


 docker tag ibackchina2018/centos7.4_1708_kubernetes_1.9.3:apiserver-amd64_1.9.3  gcr.io/google_containers/kube-apiserver-amd64:v1.9.3





####  etcd-amd64:3.1.10
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:etcd-amd64_3.1.10

docker tag  ibackchina2018/centos7.4_1708_kubernetes_1.9.3:etcd-amd64_3.1.10   gcr.io/google_containers/etcd-amd64:3.1.10





####  pause-amd64:3.0 
docker pull ibackchina2018/centos7.4_1708_kubernetes_1.9.3:pause-amd64_3.0 


docker tag ibackchina2018/centos7.4_1708_kubernetes_1.9.3:pause-amd64_3.0    gcr.io/google_containers/pause-amd64:3.0 



