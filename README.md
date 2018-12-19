# jenkinsx

Extend jenkinsxio/jenkinsx:latest with additional Jenkins plugins

When deploying/upgrading Jenkins-X, add this override in values.yaml:

```
jenkins:
  Master:
    Image: "avtalsbanken/jenkinsx"
    ImageTag: "latest"
```
