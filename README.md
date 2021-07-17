# Helm Chart Repository

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/shubhamtatvamasi)](https://artifacthub.io/packages/search?repo=shubhamtatvamasi)
[![Release Charts](https://github.com/ShubhamTatvamasi/helm/workflows/Release%20Charts/badge.svg)](https://github.com/ShubhamTatvamasi/helm/actions)

Download helm:
```bash
HELM_VERSION=3.6.3
HELM_LINUX=helm-v${HELM_VERSION}-linux-amd64.tar.gz
wget https://get.helm.sh/$HELM_LINUX
tar -zxvf $HELM_LINUX
sudo mv linux-amd64/helm /usr/local/bin/helm
rm -r $HELM_LINUX linux-amd64
```

Add helm repo on your list:
```bash
helm repo add shubhamtatvamasi https://shubhamtatvamasi.github.io/helm
helm repo update
```

Search all repos:
```bash
helm search repo shubhamtatvamasi
```
