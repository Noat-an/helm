# helm

```bash
werf helm secret generate-secret-key > .werf_secret_key

werf helm secret values encrypt template-secrets.yaml -o .helm/secret-values.yaml

werf helm  template app ./practice/ --debug > app.yaml
```