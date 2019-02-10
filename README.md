<<<<<<< HEAD
About cdms2
===========

Home: https://cdms.readthedocs.io/en/latest
=======
About cdtime
============

Home: http://gitub.com/CDAT/cdtime
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7

Package license: 3-Clause BSD

Feedstock license: BSD 3-Clause

<<<<<<< HEAD
Summary: Community Data Management System

The Community Data Management System is an object-oriented
data management system, specialized for organizing
multidimensional, gridded data used in climate
analysis and simulation.
=======
Summary: Climate calendar manipulation tools

The cdtime module contains functions for converting between
these forms, based on the common calendars used in climate
simulation. Basic arithmetic and comparison operators are also available.
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7


Current build status
====================

<<<<<<< HEAD
[![Linux](https://img.shields.io/circleci/project/github/conda-forge/cdms2-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/cdms2-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/cdms2-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/cdms2-feedstock)
=======
[![Linux](https://img.shields.io/circleci/project/github/conda-forge/cdtime-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/cdtime-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/cdtime-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/cdtime-feedstock)
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
<<<<<<< HEAD
| [![Conda Recipe](https://img.shields.io/badge/recipe-cdms2-green.svg)](https://anaconda.org/conda-forge/cdms2) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/cdms2.svg)](https://anaconda.org/conda-forge/cdms2) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/cdms2.svg)](https://anaconda.org/conda-forge/cdms2) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/cdms2.svg)](https://anaconda.org/conda-forge/cdms2) |

Installing cdms2
================

Installing `cdms2` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:
=======
| [![Conda Recipe](https://img.shields.io/badge/recipe-cdtime-green.svg)](https://anaconda.org/conda-forge/cdtime) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/cdtime.svg)](https://anaconda.org/conda-forge/cdtime) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/cdtime.svg)](https://anaconda.org/conda-forge/cdtime) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/cdtime.svg)](https://anaconda.org/conda-forge/cdtime) |

Installing cdtime
=================

Installing `cdtime` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7

```
conda config --add channels conda-forge
```

<<<<<<< HEAD
Once the `conda-forge` channel has been enabled, `cdms2` can be installed with:

```
conda install cdms2
```

It is possible to list all of the versions of `cdms2` available on your platform with:

```
conda search cdms2 --channel conda-forge
=======
Once the `conda-forge` channel has been enabled, `cdtime` can be installed with:

```
conda install cdtime
```

It is possible to list all of the versions of `cdtime` available on your platform with:

```
conda search cdtime --channel conda-forge
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


<<<<<<< HEAD
Updating cdms2-feedstock
========================

If you would like to improve the cdms2 recipe or build a new
=======
Updating cdtime-feedstock
=========================

If you would like to improve the cdtime recipe or build a new
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
<<<<<<< HEAD
Note that all branches in the conda-forge/cdms2-feedstock are
=======
Note that all branches in the conda-forge/cdtime-feedstock are
>>>>>>> 22c983de4c479888ba9ec7ca47c07ae2217b76c7
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
