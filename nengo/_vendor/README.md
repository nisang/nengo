Vendorized dependencies
=======================

This directory contains Nengo dependencies that have been vendorized, i.e. are
shipped with Nengo to allow for easy offline install with a single file.

To add a new vendorized dependency add it to `requirements-vendorized.txt` and
run

```bash
pip install --target nengo/_vendor -r nengo/_vendor/requirements-vendorized.txt
```

from the Nengo root directory.
To update all vendorized Nengo dependencies to the latest version run

```bash
pip install --upgrade --target nengo/_vendor -r nengo/_vendor/requirements-vendorized.txt
```

from the Nengo root directory.
