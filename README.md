# ADC k8s Deployment Exploration

This repository has been archived.

This repository was created to explore the use of helm for a test deployment to
ADC's kubernetes test cluster.

Refer to the [ogdc-helm](https://github.com/qgreenland-net/ogdc-helm) repository
for the latest developments on helm configurations for the OGDC stack.


## Using helm

Good places to start:

* [Using helm](https://helm.sh/docs/intro/using_helm/): Includes introductory
  information about foundational concepts.
* [Topics](https://helm.sh/docs/topics/): In-depth explanations of various
  concepts in Helm
* [Chart template guide](https://helm.sh/docs/chart_template_guide/):
  information about the Helm templating system. E.g., how to add control flow,
  access vairables, loop over lists/mappings, etc.
  

## Other options to consider

* [kompose](https://kompose.io/user-guide/): takes docker compose configuration
  and converts it into kubernetes yaml, helm, and other options. Why not use this? Helm feels very heavy-weight.
* [skaffold](https://skaffold.dev/): Skaffold handles the workflow for building,
  pushing and deploying your application
