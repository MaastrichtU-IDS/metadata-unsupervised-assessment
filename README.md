# Metadata Unsupervised Assessment
In this project we carry out a quality assessment of Gene Expression Omnibus [GEO](https://www.ncbi.nlm.nih.gov/geo/) dataset. We first create features of the dataset using topic modeling, then we create the feature matrix, by matching the terms present in the dataset.

## Getting Started

Following tools should be installed in your computer: 
- Jupyter Notebook
- Python 2.7 and newer versions

### Prerequisites

- For Windows: Install [Docker](https://www.docker.com/)
- For LINUX and macOS: Install [turicreate](https://github.com/apple/turicreate/blob/master/README.md)

### Accessing with Docker

1. Clone this repository
```shell
git clone https://github.com/MaastrichtU-IDS/metadata-unsupervised-assessment.git
cd metadata-unsupervised-assessment

```
2. Build a Docker image and run
```shell
docker build -t turi_mua .
docker run -it -p 8888:8888 -v "$PWD":/home/jovyan --name=meta_turi turi_mua

```
3. Access the service (token prompts in the terminal)

    http://0.0.0.0:8888/?token=<SOME-RANDOM-TOKEN-SHOWED-IN-CONSOLE>

