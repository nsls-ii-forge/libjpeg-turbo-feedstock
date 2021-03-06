About libjpeg-turbo
===================

Home: https://libjpeg-turbo.org

Package license: IJG, modified 3-clause BSD and zlib

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/libjpeg-turbo-feedstock/blob/master/LICENSE.txt)

Summary: IJG JPEG compliant runtime library with SIMD and other optimizations

Development: https://github.com/libjpeg-turbo/libjpeg-turbo

Documentation: https://libjpeg-turbo.org

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=202&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/libjpeg-turbo-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=202&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/libjpeg-turbo-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=202&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/libjpeg-turbo-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=202&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/libjpeg-turbo-feedstock?branchName=master&jobName=win&configuration=win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-libjpeg--turbo-green.svg)](https://anaconda.org/nsls2forge/libjpeg-turbo) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/libjpeg-turbo.svg)](https://anaconda.org/nsls2forge/libjpeg-turbo) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/libjpeg-turbo.svg)](https://anaconda.org/nsls2forge/libjpeg-turbo) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/libjpeg-turbo.svg)](https://anaconda.org/nsls2forge/libjpeg-turbo) |

Installing libjpeg-turbo
========================

Installing `libjpeg-turbo` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
conda config --set channel_priority strict
```

Once the `nsls2forge` channel has been enabled, `libjpeg-turbo` can be installed with:

```
conda install libjpeg-turbo
```

It is possible to list all of the versions of `libjpeg-turbo` available on your platform with:

```
conda search libjpeg-turbo --channel nsls2forge
```




Updating libjpeg-turbo-feedstock
================================

If you would like to improve the libjpeg-turbo recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/libjpeg-turbo-feedstock are
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


