# vmware-pks-deploy-meta

[![Build Status](https://travis-ci.org/vmware/vmware-pks-deploy-meta.svg?branch=master)](https://travis-ci.org/vmware/vmware-pks-deploy-meta)

## Overview
This is a meta repository to assemble all repositories required for a PKS + NSX-T deployment on vSphere.

You likely really want to be looking at the [vmware-pks-deploy](https://github.com/vmware/vmware-pks-deploy) project.

Do not clone this repository. Instead, [install Git Repo](https://source.android.com/source/downloading#installing-repo).

Once you've installed Git Repo, you will use it to download and assemble all the component git repositories.

This processis as follows:
* create and/or change into a directory where you'd like to place all source relevant to this PKS deployment
* then execute the following

`repo init -u git@github.com:vmware/vmware-pks-deploy-meta.git`

...followed by...

`repo sync`

## Contributing

The vmware-pks-deploy-meta project team welcomes contributions from the community. Before you start working with vmware-pks-deploy-meta, please read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Copyright © 2018 VMware, Inc. All Rights Reserved.
SPDX-License-Identifier: MIT
