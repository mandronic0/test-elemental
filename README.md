```
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: test
  namespace: fleet-local
spec:
  repo: https://github.com/mandronic0/test-elemental/
  paths:
  - Elemental/CRDs
  - Elemental/Operator
```
