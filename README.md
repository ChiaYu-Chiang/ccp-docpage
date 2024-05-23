# ccp-docpage

This repository provides a website for users to view ccp documentation

## How to install

1. Clone this repository.
* clone with SSH
```shell
git clone git@github.com:ChiaYu-Chiang/ccp-docpage.git
```
* clone with HTTPS
```shell
git clone https://github.com/ChiaYu-Chiang/ccp-docpage.git
```
2. Enable virtual environment.
```shell
cd ccp-docpage\
```
* windows
```shell
python -m venv .venv
.venv\Scripts\activate
```
* linux
```shell
python -m venv .venv
source .venv/bin/activate
```
3. Install required packages.
```shell
pip install -r requirements.txt
```

## How to use

1. Start up the web server.
```shell
mkdocs serve -a 0.0.0.0:8000
```
2. Visit website.
* <http://127.0.0.1:8000>

