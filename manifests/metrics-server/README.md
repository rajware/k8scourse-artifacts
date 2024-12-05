# metrics-server

The manifests in this directory mirror the manifests from the project https://github.com/kubernetes-sigs/metrics-server. Only selected versions are mirrored.

We add the `--kubelet-insecure-tls` flag to the deployment, to allow the metrics server to work correctly in kubeadm-created clusters. WARNING: This is insecure, and should not be done in production clusters. We do it because we use these manifests only for training.

Some of these manifests are available for download via shortened URLS, as follows:

|Manifest|URL|
|---|---|
|metricsserver-0.6.1.yaml|http://re.rspl.net/k8s-metrics-server|
