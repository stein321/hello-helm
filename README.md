# hello-helm
Sample app deployed with helm.  Built to demonstrate [k8s-toolchain](https://github.com/cplee/k8s-toolchain)

# Pipeline
<img src="pipeline.png?raw=true">

* Build docker image 
* Vulnerability static analysis of image with [Clair](https://github.com/coreos/clair)
* Deploy image with [Helm](https://github.com/kubernetes/helm)
* Test with [Goss](https://github.com/aelsabbahy/goss)
