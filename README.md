This is the contribution I have done while working on an app in the University of Sheffield. I forked the part I had worked on here. 
![deploy](https://github.com/sheffieldmltracking/btviewer/actions/workflows/deploy.yml/badge.svg)

# Bee tracking viewer

This repository contains the code for a user interface for viewing bee tracking photos and human labelling of these tracking images.

# Installation

Install the package in a [virtual environment](https://docs.python.org/3/tutorial/venv.html) using the [Python package manager](https://pip.pypa.io/en/stable/).

```bash
pip install btviewer
```

# Usage

To run the backend, please run the `btviewer` command in your terminal, specifying the root folder that contains your image capture sessions:

```bash
btviewer ~/my_data/
```

To see the other options, run:

```
btviewer --help
```

# Contributing

Please read the [contribution guide](CONTRIBUTING.md).
