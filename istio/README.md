# Profile dump
```sh
  $ istioctl profile dump demo > istio-operator.yaml
```
# Generate manifest
```sh
  $ istioctl manifest generate > generated-manifest.yaml
```

# Operator manifest
```sh
  $ istioctl manifest generate -f istio-operator.yaml > manifest-operator-generate.yaml
```
# Diff Old New manifest
```sh
  $ istioctl manifest diff generated-manifest.yaml manifest-operator-generate.yaml
```