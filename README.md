About qt-wayland
================

Home: http://qt-project.org

Package license: LGPL-3.0-only

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/qt-wayland-feedstock/blob/main/LICENSE.txt)

Summary: QtWayland module

Development: https://github.com/qt/qtwayland/tree/5.15

Documentation: https://wiki.qt.io/QtWayland

The QtWayland module consists of two parts.

Wayland platform plugin --
    Enables Qt applications to be run as Wayland clients.

QtWaylandCompositor API --
    Enables the creation of Wayland compositors using Qt and QtQuick.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-wayland-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-wayland-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-qt--wayland-green.svg)](https://anaconda.org/qtforge/qt-wayland) | [![Conda Downloads](https://img.shields.io/conda/dn/qtforge/qt-wayland.svg)](https://anaconda.org/qtforge/qt-wayland) | [![Conda Version](https://img.shields.io/conda/vn/qtforge/qt-wayland.svg)](https://anaconda.org/qtforge/qt-wayland) | [![Conda Platforms](https://img.shields.io/conda/pn/qtforge/qt-wayland.svg)](https://anaconda.org/qtforge/qt-wayland) |

Installing qt-wayland
=====================

Installing `qt-wayland` from the `qtforge` channel can be achieved by adding `qtforge` to your channels with:

```
conda config --add channels qtforge
conda config --set channel_priority strict
```

Once the `qtforge` channel has been enabled, `qt-wayland` can be installed with `conda`:

```
conda install qt-wayland
```

or with `mamba`:

```
mamba install qt-wayland
```

It is possible to list all of the versions of `qt-wayland` available on your platform with `conda`:

```
conda search qt-wayland --channel qtforge
```

or with `mamba`:

```
mamba search qt-wayland --channel qtforge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search qt-wayland --channel qtforge

# List packages depending on `qt-wayland`:
mamba repoquery whoneeds qt-wayland --channel qtforge

# List dependencies of `qt-wayland`:
mamba repoquery depends qt-wayland --channel qtforge
```




Updating qt-wayland-feedstock
=============================

If you would like to improve the qt-wayland recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`qtforge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `qtforge` channel.
Note that all branches in the conda-forge/qt-wayland-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@hmaarrfk](https://github.com/hmaarrfk/)

