Git source for applications

`cf git-source create csdp-salesdemo-${environment} applications --git-src-repo https://github.com/codefresh-contrib/csdp-salesdemo_applications.git/argocd/${environment} --git-token <token>`
where 'environment' = 'dev', 'stage', or 'prod-east'