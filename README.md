# Helm Chart Repository

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/shubhamtatvamasi)](https://artifacthub.io/packages/search?repo=shubhamtatvamasi)
[![Release Charts](https://github.com/ShubhamTatvamasi/helm/workflows/Release%20Charts/badge.svg)](https://github.com/ShubhamTatvamasi/helm/actions)

### Helm 4

Download helm:
```bash
wget https://get.helm.sh/helm-v4.1.4-linux-amd64.tar.gz
```

```bash
tar -C /tmp/helm -xzf helm-v4.1.4-linux-amd64.tar.gz
```

```bash
sudo mv /tmp/helm/linux-amd64/helm  /usr/local/bin
```

---

Download helm:
```bash
curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
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

Create new helm chart:
```bash
helm create my-chart
```
