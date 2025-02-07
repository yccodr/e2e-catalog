# tn-agent

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] tn-agent`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree tn-agent`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init tn-agent
kpt live apply tn-agent --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
