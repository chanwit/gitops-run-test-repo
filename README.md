# gitops-run-test-repo

1. Run `git clone https://github.com/chanwit/gitops-run-test-repo`
2. Run `cd gitops-run-test-repo`
3. Run `gitops beta run ./manifests --port port=8000:80,resource=svc/nginx,namespace=default`

Open an editor, make changes to YAML files and see it's reloading.

Press Ctrl+C to stop GitOps Run.
