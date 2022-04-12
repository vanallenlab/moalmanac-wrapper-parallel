# Molecular Oncology Almanac wrapper for parallel processing
Given large dataframes for each data type, submit a job to each cpu to process one patient with the [Molecular Oncology Almanac](https://github.com/vanallenlab/moalmanac).

## Installation
Please follow all installation instructions for the [Molecular Oncology Almanac](https://github.com/vanallenlab/moalmanac) in addition to completing the instructions below.

### Download this software from Github
This package can be downloaded through Github on the website or by using terminal. To download on the website, navigate to the top of this page, click the green `Clone or download` button, and select `Download ZIP`. This will download this repository in a compressed format. To install using Github on terminal, type 

```bash
git clone https://github.com/vanallenlab/moalmanac-wrapper-parallel.git
cd moalmanac-wrapper-parallel
```

### Install Python dependencies
This repository uses Python 3.8. We recommend using a [virtual environment](https://docs.python.org/3/tutorial/venv.html) and running Python with either [Anaconda](https://www.anaconda.com/download/) or  [Miniconda](https://conda.io/miniconda.html). 

To create a virtual environment and install dependencies with Anaconda or Miniconda, run the following from this repository's directory:
```bash
conda create -y -n moalmanac-wrapper-parallel python=3.8
conda activate moalmanac-wrapper-parallel
pip install -r requirements.txt
```

If you are using base Python, you can create a virtual environment and install dependencies by running:
```bash
virtualenv moalmanac-wrapper-parallel
source activate moalmanac-wrapper-parallel/bin/activate
pip install -r requirements.txt
```

## Contributing 
Please [create a new branch](https://docs.github.com/en/github-ae@latest/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches), make changes, and [open a pull request](https://docs.github.com/en/github-ae@latest/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
