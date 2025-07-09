# linuxoid69.github.io

Для добавления нового Helm chart нужно его положить в папку ./charts/ и выполнить команду:

```bash
helm repo index ./helm-charts --merge index.yaml --url https://linuxoid69.github.io/helm-charts/
```
