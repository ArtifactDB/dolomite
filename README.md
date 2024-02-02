<!-- These are examples of badges you might want to add to your README:
     please update the URLs accordingly

[![Built Status](https://api.cirrus-ci.com/github/<USER>/dolomite.svg?branch=main)](https://cirrus-ci.com/github/<USER>/dolomite)
[![ReadTheDocs](https://readthedocs.org/projects/dolomite/badge/?version=latest)](https://dolomite.readthedocs.io/en/stable/)
[![Coveralls](https://img.shields.io/coveralls/github/<USER>/dolomite/main.svg)](https://coveralls.io/r/<USER>/dolomite)
[![Conda-Forge](https://img.shields.io/conda/vn/conda-forge/dolomite.svg)](https://anaconda.org/conda-forge/dolomite)
[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter)](https://twitter.com/dolomite)
-->

[![Project generated with PyScaffold](https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold)](https://pyscaffold.org/)
[![PyPI-Server](https://img.shields.io/pypi/v/dolomite.svg)](https://pypi.org/project/dolomite/)
[![Monthly Downloads](https://pepy.tech/badge/dolomite/month)](https://pepy.tech/project/dolomite)
![Unit tests](https://github.com/ArtifactDB/dolomite/actions/workflows/pypi-test.yml/badge.svg)

# Umbrella for easy installation

This is an umbrella package that enables easy installation of all packages in the [**dolomite**](https://github.com/ArtifactDB/dolomite.base) framework.
It allows users to pull down all relevant packages with a single `pip` call, allowing them to (un)serialize every known resource.
Of course, the flipside is that the Python installation may now contain a lot of transitive dependencies that are not really necessary.
Advanced users or developers may prefer to install individual _dolomite_ packages based on their use cases.
