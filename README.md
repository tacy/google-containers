# kubeadm dependance image
google-containers mirror

# image list
## 1.6.2
* kube-apiserver-amd64:v1.6.2
* kube-controller-manager-amd64:v1.6.2
* kube-scheduler-amd64:v1.6.2
* kube-proxy-amd64:v1.6.2

* pause-amd64:3.0
* etcd-amd64:3.0.17
* k8s-dns-kube-dns-amd64:1.14.1
* k8s-dns-sidecar-amd64:1.14.1
* k8s-dns-dnsmasq-nanny-amd64:1.14.1
* kukbernetes-dashboard-amd64:v1.6.0


## 1.5.7
```
const (
	KubeEtcdImage = "etcd"

	KubeAPIServerImage         = "apiserver"
	KubeControllerManagerImage = "controller-manager"
	KubeSchedulerImage         = "scheduler"
	KubeProxyImage             = "proxy"

	KubeDNSImage         = "kube-dns"
	KubeDNSmasqImage     = "dnsmasq"
	KubeExechealthzImage = "exechealthz"
	Pause                = "pause"

	gcrPrefix   = "gcr.io/google_containers"
	etcdVersion = "2.2.5"

	kubeDNSVersion     = "1.7"
	dnsmasqVersion     = "1.3"
	exechealthzVersion = "1.1"
	pauseVersion       = "3.0"
)

```
