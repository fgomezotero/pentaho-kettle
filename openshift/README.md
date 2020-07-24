# brief introduction

I make available a Webspoon template focused on a development or test environment for the community. We start from an ephemeral configuration that can scale as much as they want since this service is statelessI make available a Webspoon template focused on a development or test environment for the community. We start from an ephemeral configuration that can scale as much as they want since this service is stateless.

## Basic usage

```
$ oc create -f webspoon-template.yaml
```

The previous step loads the template and its artefacts to the current namespace or project. T

```
$ oc process webspoon-template -p NAME=webspoon | oc create -f -
```

Finally we process the template and initialize the parameter, created each of the artifacts.

- - -

> I hope you find it useful.