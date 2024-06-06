# Notebooks for Kubeflow / OpenShift

This repo is intended to help those who are trying to make Jupyter notebook containers compatible with OpenShift and make improvements that can be contributed to upstream Kubeflow [here](https://github.com/kubeflow/kubeflow/tree/master/components/example-notebook-servers).

How is this repo different from other repos? The work here is intended to provide a base with simple best practices that will be universally usable. It is also intended to appropriately leverage existing work.

In short, this work is intended to:

- Focus on [notebooks only](https://github.com/kubeflow/kubeflow/tree/master/components/example-notebook-servers)
- Help contribute upstream - not [this](https://github.com/red-hat-data-services/notebooks
) and [this](https://github.com/opendatahub-io/notebooks)
- Avoid fragile design / duplicated work - [yes](https://github.com/redhat-na-ssa/demo-ocp-gpu/tree/main/containers/udi-cuda/ubi8) / [nope](https://github.com/opendatahub-io/notebooks/tree/main/cuda/c9s-python-3.9), [not this](https://github.com/opendatahub-io-contrib/workbench-images)
