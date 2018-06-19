# vmware-pk-deploy-meta

## Overview
This is a meta repository to assemble all repositories required for a PKS + NSX-T deployment on vSphere.

You likely really want to be looking at the [vmware-pks-deploy](https://github.com/vmware/vmware-pks-deploy) project.

Do not clone this repository. Instead, [install Git Repo](https://source.android.com/source/downloading#installing-repo).

Once you've installed Git Repo, you will use it to download and assemble all the component git repositories.

This processis as follows:
* create and/or change into a directory where you'd like to place all source relevant to this PKS deployment
* then execute the following

`repo init -u git@gitlab.eng.vmware.com:ps-emerging/pks-deploy-meta.git`

...followed by...

`repo sync`

## Contributing

The vmware-pk-deploy-meta project team welcomes contributions from the community. If you wish to contribute code and you have not
signed our contributor license agreement (CLA), our bot will update the issue when you open a Pull Request. For any
questions about the CLA process, please refer to our [FAQ](https://cla.vmware.com/faq). For more detailed information,
refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Copyright © 2018 VMware, Inc. All Rights Reserved.
SPDX-License-Identifier: MIT
