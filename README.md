About motmetrics
================

Home: https://github.com/cheind/py-motmetrics

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Benchmark multiple object trackers (MOT) in Python

The py-motmetrics library provides a Python implementation of metrics for benchmarking multiple object trackers (MOT).


Current build status
====================

All platforms:
[![noarch](https://img.shields.io/circleci/project/github/loopbio/motmetrics-feedstock/master.svg?label=noarch)](https://circleci.com/gh/loopbio/motmetrics-feedstock)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-motmetrics-green.svg)](https://anaconda.org/loopbio/motmetrics) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/motmetrics.svg)](https://anaconda.org/loopbio/motmetrics) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/motmetrics.svg)](https://anaconda.org/loopbio/motmetrics) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/motmetrics.svg)](https://anaconda.org/loopbio/motmetrics) |

Installing motmetrics
=====================

Installing `motmetrics` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `motmetrics` can be installed with:

```
conda install motmetrics
```

It is possible to list all of the versions of `motmetrics` available on your platform with:

```
conda search motmetrics --channel loopbio
```




Updating motmetrics-feedstock
=============================

If you would like to improve the motmetrics recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/motmetrics-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.