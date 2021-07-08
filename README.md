# ![xeus-cling](https://xeus-cling.readthedocs.io/en/latest/_images/xeus-cling.svg)
[![Azure Pipelines](https://dev.azure.com/jupyter-xeus/jupyter-xeus/_apis/build/status/jupyter-xeus.xeus-cling?branchName=master)](https://dev.azure.com/jupyter-xeus/jupyter-xeus/_build/latest?definitionId=4&branchName=master)
[![Appveyor](https://ci.appveyor.com/api/projects/status/qn0wskxlvy52utuv?svg=true)](https://ci.appveyor.com/project/jupyter-xeus/xeus-cling)
[![Documentation Status](http://readthedocs.org/projects/xeus-cling/badge/?version=latest)](https://xeus-cling.readthedocs.io/en/latest/?badge=latest)
[![Binder](https://img.shields.io/badge/launch-binder-579aca.svg?logo=data:image/png;base64,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)](https://mybinder.org/v2/gh/WhiteNoize-SNU/CppJupyter/main)
[![Join the Gitter Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/QuantStack/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

`xeus-cling` is a Jupyter kernel for C++ based on the C++ interpreter [cling](https://github.com/root-project/cling) and
the native implementation of the Jupyter protocol [xeus](https://github.com/jupyter-xeus/xeus).

## Installation

xeus-cling has been packaged for the mamba (or conda) package manager on the **Linux** and **OS X** platforms. At the moment, we are not providing packages for the **Windows** platform.

To ensure that the installation works, it is preferable to install `xeus-cling` in a fresh environment. It is also needed to use a [miniforge](https://github.com/conda-forge/miniforge) or [miniconda](https://conda.io/miniconda.html) installation because with the full [anaconda](https://www.anaconda.com/) you may have a conflict with the `ZeroMQ` library which is already installed in the anaconda distribution.

### Installation with mamba or conda

The safest usage is to create an environment named `cling`:

```
mamba create -n cling
source activate cling
```

Then you can install in this environment `xeus-cling` and its dependencies

```
mamba install xeus-cling -c conda-forge
```

### Installation from source

You will first need to create a new environment and install the dependencies:

```bash
mamba create -n xeus-cling -c conda-forge cmake xeus=1.0.0 cling=0.8 clangdev=5.0 llvmdev=5 nlohmann_json cppzmq xtl pugixml cxxopts
source activate xeus-cling
```

You can then compile the sources:

```bash
cmake -D CMAKE_INSTALL_PREFIX=${CONDA_PREFIX} -D CMAKE_C_COMPILER=$CC -D CMAKE_CXX_COMPILER=$CXX -D CMAKE_INSTALL_LIBDIR=${CONDA_PREFIX}/lib -D DOWNLOAD_GTEST=ON
make && make install
```

If you don't have a frontend already installed (classic Jupyter Notebook or JupyterLab for instance), install one:

```bash
mamba install jupyterlab -c conda-forge
```

## Trying it online

To try out xeus-cling interactively in your web browser, just click on the binder
link:

[![Binder](https://mybinder.org/static/logo.svg?v=fe52c40adc69454ba7536393f76ebd715e5fb75f5feafe16a27c47483eabf3311c14ed9fda905c49915d6dbf369ae68fb855a40dd05489a7b9542a9ee532e92b)](https://mybinder.org/v2/gh/jupyter-xeus/xeus-cling/stable?filepath=notebooks/xcpp.ipynb)

## Documentation

To get started with using `xeus-cling`, check out the full documentation

http://xeus-cling.readthedocs.io/

## Usage

Launch the jupyter notebook with `jupyter notebook` and launch a new C++ notebook by selecting the **C++14** kernel in the *new* dropdown.

### A C++ notebook

You can now make use of the C++ programming language in the Jupyter notebook.

![A C++ notebook](https://raw.githubusercontent.com/jupyter-xeus/xeus-cling/master/notebook.png)

### Inline help and tab-completion

Quick help is shown on the pager with the special `?` magic.

![Help](https://github.com/jupyter-xeus/xeus-cling/blob/master/help.png?raw=true)

Content for the quick help is available for the standard library, and can be made available for third-party packages.

### Rendering of rich outputs

![Rich output](https://github.com/jupyter-xeus/xeus-cling/blob/master/rich-output.png?raw=true)

### Jupyter interactive widgets

A C++ backend for the Jupyter interactive widgets is available in the [`xwidgets`](https://github.com/QuantStack/xwidgets/) package.

![Widgets](https://github.com/jupyter-xeus/xeus-cling/blob/master/widgets.gif?raw=true)

## Dependencies

``xeus-cling`` depends on

 - [xeus](https://github.com/jupyter-xeus/xeus)
 - [xtl](https://github.com/xtensor-stack/xtl)
 - [cling](https://github.com/root-project/cling)
 - [pugixml](https://github.com/zeux/pugixml)
 - [cxxopts](https://github.com/jarro2783/cxxopts)
 - [nlohmann_json](https://github.com/nlohmann/json)


| `xeus-cling` |   `xeus`        |      `xtl`      |     `cling`   |   `pugixml`   | `cppzmq` | `cxxopts`     | `nlohmann_json` | `dirent` (windows only) |
|--------------|-----------------|-----------------|---------------|---------------|----------|---------------|-----------------|-------------------------|
|  master      |  >=1.0.0,<2.0.0 |  >=0.7.0,<0.8.0 | >=0.6,<0.9    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=2.2 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.12.1      |  >=1.0.0,<2.0.0 |  >=0.7.0,<0.8.0 | >=0.6,<0.9    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=2.2 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.12.0      |  >=1.0.0,<2.0.0 |  >=0.7.0,<0.8.0 | >=0.6,<0.9    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=2.2 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.11.0      |  >=0.24.0,<0.26 |  >=0.6.23,<0.7  | >=0.6,<0.9    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=2.2 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.10.1      |  >=0.24.0,<0.26 |  >=0.6.23,<0.7  | >=0.6,<0.8    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=2.2 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.10.0      |  >=0.24.0,<0.25 |  >=0.6.5,<0.7   | >=0.6,<0.8    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.9.0       |  >=0.24.0,<0.25 |  >=0.6.5,<0.7   | >=0.6,<0.7    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.8.1       |  >=0.23.2,<0.24 |  >=0.6.5,<0.7   | >=0.6,<0.7    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.8.0       |  >=0.23.2,<0.24 |  >=0.6.5,<0.7   | >=0.6,<0.7    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.7.1       |  >=0.21.1,<0.22 |  >=0.6.5,<0.7   | >=0.5,<0.6    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.7.0       |  >=0.21.1,<0.22 |  >=0.6.5,<0.7   | >=0.5,<0.6    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.6.1,<4.0    | >=2.3.2,<3              |
|  0.6.0       |  >=0.20.0,<0.21 |  >=0.6.1,<0.7   | >=0.5,<0.6    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.3.0,<4.0    | >=2.3.2,<3              |
|  0.5.1       |  >=0.19.1,<0.20 |  >=0.6.1,<0.7   | >=0.5,<0.6    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.3.0,<4.0    | >=2.3.2,<3              |
|  0.5.0       |  >=0.19.1,<0.20 |  >=0.6.1,<0.7   | >=0.5,<0.6    | ~1.8.1        | ~4.3.0   | >=2.1.1,<=3.0 | >=3.3.0,<4.0    | >=2.3.2,<3              |

`xeus-cling` requires its dependencies to be built with the same compiler and same C runtime as the one used to build `cling`.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) to know how to contribute and set up a development environment.

## License

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

This software is licensed under the BSD-3-Clause license. See the [LICENSE](LICENSE) file for details.
