```
apiVersion: entando.org/v1
kind: EntandoDeBundle
metadata:
  name: ss005
  namespace: qe-one
  labels:
    contentType: 'true'
    contentTemplate: 'true'
spec:
  details:
    name: ss005
    description: >-
      A bundle to use for testing.
    dist-tags:
      latest: v0.0.1
    versions:
      - v0.0.1
  tags:
    - version: v0.0.1
      shasum: 1639fd2f6d93d0dafe8594c632542e579c42d059
      integrity: 1639fd2f6d93d0dafe8594c632542e579c42d059
      tarball: 'https://github.com/excess17/ss005.git'
```
