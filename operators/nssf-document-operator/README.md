# nssf-document-operator

## Description

The NSSF Document Operator is a Kubernetes operator that manages the lifecycle of NSSF configuration documents.

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nssf-document-operator`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nssf-document-operator`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nssf-document-operator
kpt live apply nssf-document-operator --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
