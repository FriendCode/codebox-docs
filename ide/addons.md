---
layout: default
title: Addons
section: ide/addons
---

# Managing addons

### Define addons directories:

Codebox need two directories for managing addons:

* A directory for storing defaults addons: `WORKSPACE_ADDONS_DEFAULTS_DIR` (don't change if you don't know what you're doing)
* A directory for storing all the installed addons: `WORKSPACE_ADDONS_DIR`
* A directory for storing temporary data: `WORKSPACE_ADDONS_TEMP_DIR`

`WORKSPACE_ADDONS_DEFAULTS_DIR` will be access in read-only mode but `WORKSPACE_ADDONS_DIR` need write permissions.

By default, Codebox will store the new addons into `.addons`.
Caution: If the directory doesn't exists, Codebox will recursively create it.
