# snakemake-tutorial

## How to install snakemake
### If you have anaconda3 then try one among below:
###### conda install -c conda-forge -c bioconda snakemake
###### brew install snakemake
###### sudo apt install snakemake(Linux)
### See this page: https://snakemake.readthedocs.io/en/stable/getting_started/installation.html

## How to start
###### git clone https://github.com/Woosub-Kim/snakemake-tutorial.git
###### cd snakemake-tutorial
###### conda env create --name snakemake-tutorial --file environment.yaml
###### conda activate snakemake-tutorial

## TroubleShooting
### If you meet package confilcts during installing
###### try other ways to install
###### re-install anaconda3 or try to replace anaconda3 to miniconda3
###### frankly speeking I don't know how to solve it.

## If you see import related errors during excuting snakemake
### It can be smart_open version issue and you can do this!
### conda install smart_open==2.0.0 
### pip install smart_open==2.0.0
