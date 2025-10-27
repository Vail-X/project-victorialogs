helm repo add vm https://victoriametrics.github.io/helm-charts/
helm repo update
Pull and unpack
helm pull vm/victoria-logs-cluster --version <version_number> --untar