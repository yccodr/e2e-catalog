# nftopology-operator

## Description
sample description

## Usage

### Prerequisites

- Apply Package Variant CRD

```
kubectl apply -f https://github.com/nephio-project/porch/raw/main/controllers/config/crd/bases/config.porch.kpt.dev_packagevariants.yaml
```


### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nftopology-operator`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nftopology-operator`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nftopology-operator
kpt live apply nftopology-operator --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
