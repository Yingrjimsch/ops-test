# DOK Ops Template Base

  

This repository contains the operations base yaml files. Every deployment type has it's own folder and can be referenced by a component (see How To).

  

## Getting started

  

To make it easy for you to get started with the OPS Base there is a folder `example` with different ready to use examples.

To contribute or change something in the OPS Base please work as following:
1. Create a new branch with feature or fix
2. Develop your feature/bugfix and test it locally with **the right kustomize version** installed on argocd.
3. Merge your changes in the `beta` branch if you are finished with development for public testing.
4. After public testing merge the beta branch in `main` and remove your development branch.

