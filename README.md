# ArgoCD CLI
Github Action to install ArgoCD CLI

## Usage
To use this action, add the following step to your GitHub Action workflow:

### Select desired version from https://github.com/argoproj/argo-cd/releases

```yaml
- name: Setup ArgoCD CLI 
  uses: MonkeyECX/actions-argocd-cli@v1
  with:
    version: v2.5.7 # optional 
```

## Authors

Forked to [Ajeet Yadav](https://github.com/imAjeetYadav)
