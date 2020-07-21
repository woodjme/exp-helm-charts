# Exp-Helm-Charts

This repo makes use of GitHub pages to host charts. See `./docs` folder.

## Package Charts

Example:

```sh
helm package ./charts/aws-ecr-credential/ -d ./docs/
helm repo index ./docs/
```
