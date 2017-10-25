# SAGE2 Enabled Data-science Notebooks

## Prerequisites
* Docker

## Installation
```bash
docker pull andrewtburks/sage2-datascience-notebook
```

## Usage
```bash
docker run -it --rm -p 8888:8888 andrewtburks/sage2-datascience-notebook start.sh jupyter lab
```