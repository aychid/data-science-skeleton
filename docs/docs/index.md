# Data Science Skeleton documentation!

## Description

Hello World!

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `az storage blob upload-batch -d` to recursively sync files in `data/` up to `azure-container-test/data/`.
* `make sync_data_down` will use `az storage blob upload-batch -d` to recursively sync files from `azure-container-test/data/` to `data/`.


