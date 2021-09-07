---
permalink: /software/
title: "Software"
---

I develop software as part of my research and as a hobby. I love working on Open Source projects. I believe that science must be available to everyone!

Below you'll find packages/software/scripts that I developed during my Ph.D.

pymfe: Python Meta-Feature Extractor
------------------------------------
The pymfe (**py**thon **m**eta-**f**eature **e**xtractor) provides a
comprehensive set of meta-features implemented in python. The package brings
cutting edge meta-features, following recent literature propose. The pymfe
architecture was thought to systematically make the extraction, which can
produce a robust set of meta-features. Moreover, pymfe follows recent
meta-feature formalization aiming to make MtL reproducible.

[![Build Status](https://travis-ci.org/ealcobaca/pymfe.svg?branch=master)](https://travis-ci.org/ealcobaca/pymfe)
[![codecov](https://codecov.io/gh/ealcobaca/pymfe/branch/master/graph/badge.svg)](https://codecov.io/gh/ealcobaca/pymfe)
[![Documentation Status](https://readthedocs.org/projects/pymfe/badge/?version=latest)](https://pymfe.readthedocs.io/en/latest/?badge=latest)
[![PythonVersion](https://img.shields.io/pypi/pyversions/pymfe.svg)](https://www.python.org/downloads/release/python-370/)
[![Pypi](https://badge.fury.io/py/pymfe.svg)](https://badge.fury.io/py/pymfe)
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

The installation process is similar to other packages available on pip:

```python
pip install -U pymfe
```

We write a great [Documentation](https://pymfe.readthedocs.io/en/latest/?badge=latest)
to guide you on how to use the pymfe library.

System for Recommending Machine Learning Algorithms for Gene Expression Data Analysis Using Meta-learning
---------------------------------------------------------------------------------------------------------

Cancer is one of the main causes of death today. Understanding its internal mechanisms and designing computational models capable of improving its diagnosis will have substantial benefits. New sequencing technologies, based on RNA-Seq, have made available a large amount of data that can be used for cancer diagnosis. As the manual analysis of these data is unfeasible, machine learning algorithms have been used successfully. However, each machine learning algorithm has an inductive bias, making it better suited to a given subset of problems. This project studies the use of strategies that improve the selection of classification algorithms for machine learning in the context of data classification. We investigate the potential of using meta-learning to associate characteristics present in a dataset with the most appropriate classification techniques to deal with them in identifying tumors through gene expression, using RNA-Seq and Microarray technology.

Source: https://github.com/ealcobaca/rec-sys-to-cancer
