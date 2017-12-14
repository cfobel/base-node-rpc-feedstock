About base-node-rpc
===================

Home: https://github.com/sci-bots/base-node-rpc

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: 



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/base-node-rpc-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/base-node-rpc-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/base-node-rpc-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/base-node-rpc-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/base-node-rpc-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/base-node-rpc-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/cfobel/base-node-rpc/badges/version.svg)](https://anaconda.org/cfobel/base-node-rpc)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/cfobel/base-node-rpc/badges/downloads.svg)](https://anaconda.org/cfobel/base-node-rpc)

Installing base-node-rpc
========================

Installing `base-node-rpc` from the `cfobel` channel can be achieved by adding `cfobel` to your channels with:

```
conda config --add channels cfobel
```

Once the `cfobel` channel has been enabled, `base-node-rpc` can be installed with:

```
conda install base-node-rpc
```

It is possible to list all of the versions of `base-node-rpc` available on your platform with:

```
conda search base-node-rpc --channel cfobel
```




Updating base-node-rpc-feedstock
================================

If you would like to improve the base-node-rpc recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cfobel` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cfobel` channel.
Note that all branches in the conda-forge/base-node-rpc-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.