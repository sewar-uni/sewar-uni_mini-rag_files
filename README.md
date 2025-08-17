# mini-rag
this is minimal implementaion of the RAG model for question answering


## requairments
- python 3.8 or later

### install python using miniconda
1)download and install miniconda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)
2)create a new enviroment using the folowing command:
```bash
$ conda create -n mini-rag python=3.8
```
3)activate the enviroment:
```bash
$ conda activate mini-rag
```
# (optional) setup your command line for better readability 
```bash
 export ps1="\[033[01;32m\]\u@\h:\w\n\[\033[00m\]\$"
 ```
## installation 

### install the required packages
```bash
$ pip install -r requirements.txt
```
### setup the enviroment variables
```bash
$ cp.env.example.env
```
set your enviroment variables in the `.env` file.like `OPENAI-API-KEY` value.




