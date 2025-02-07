# nssf-document

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nssf-document`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nssf-document`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nssf-document
kpt live apply nssf-document --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/


### CR Example
```yaml
apiVersion: req.winlab.nycu/v1alpha1
kind: NSSFDocument
metadata:
  name: document
  namespace: free5gc-cp
spec:
  snssaiList:
    - sst: 1
      sd: "010203"
  tai:
    plmnId:
      mcc: "208"
      mnc: "93"
    tac: "1"
```