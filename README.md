# NSX-T K8s Integration demo repository

## basic-demo-scenario

This includes basic demo to show off benefit of NSX-T
Please look at README.md under the folder.

## samples of k8s-yaml

There are some yaml samples which are not guaranteed to work. 

## test-scripts

It is useful when you create multiple tenants at the same time.
If you want ingress in a new tenant, you can do like `./create-ingress.sh new-tenant`
If you want service type lb in a new tenant, you can do like `./create-lbservice.sh new-tenant`

## yaml-examples-for-installation

This is an example when you deploy ncp/nsx-node-agent on native kubernetes

## yaml example for ncp feature

The folder name is like `<supported version>-<feature name>`

