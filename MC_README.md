# McNairy README

## TODO
- create kind k8s clsuter: backstage-demo
    FYI: Kind prepends `kind-` to the cluster name so the context will show up as `kind-backstage-demo`.
- create variables
- run install_script.sh while in the kind-backstage-demo context

## Undo

- Delete all resources created with Backstage
- Delete IAM user: vcluster-demo in AWS
- Delete vclusters-demo cluster (this will delete all k8s resources associated with the vcluster)

## Questions
