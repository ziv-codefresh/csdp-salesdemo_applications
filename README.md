# CSDP-SalesDemo_Applications
Git source for ArgoCD application defintions

Adding this  git source:
```bash
cf git-source create csdp-salesdemo-${environment} applications --git-src-repo https://github.com/codefresh-contrib/csdp-salesdemo_applications.git/argocd/${environment} --git-token <token>
```
where 'environment' = 'dev', 'stage', or 'prod-east'