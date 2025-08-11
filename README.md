# Chamelab Template Generator

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/a7med7x7/chamelab-cli)](https://github.com/a7med7x7/chamelab-cli/releases)


> Scaffold GPU-ready ML projects for [Chameleon Cloud](https://www.chameleoncloud.org) with MLflow tracking, containerized environments, and reproducible workflows.

--- 

##  Overview

This template helps you **bootstrap** a complete machine learning environment on Chameleon Cloud.  
It is designed for **researchers, ML engineers, and students** working on ML research who want to:
- Quickly set up Chameleon Cloud GPU instances
- Configure a containerized ML environment (Docker + Compose)
- Enable MLflow tracking 
- Include example notebooks for popular ML frameworks

---

##  Requirements

- **Python** ≥ 3.8
- **Copier** ≥ 9.0
- [Chameleon Cloud account](https://www.chameleoncloud.org)

---

##  Installation

Install Copier if you don’t have it yet:

```sh
pip install copier
```

or 
```sh
pipx install copier 
```

---

## QUick Start 

Create a New Project with 
```sh
copier copy --vcs-ref main https://github.com/A7med7x7/chamelab-cli.git projectx
```
You’ll be prompted for:

- Project name

- Author name

- Workflow type

- GPU type

- ML framework

- Optional integrations

This will generate your ML project in my-ml-project/ 