# oai-operator

## Description

The oai-operator is a Kubernetes operator that manages the lifecycle of OAI nfdeployment


## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nssf-document-operator`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree oai-operator`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init oai-operator
kpt live apply oai-operator --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
