This repository contains details how to use a defined dashboard to test new or existing databases engine.
As Support or CSM there will be a need to test customer issues and this could be in different Database engine with this process, you warranty that test something that works in others DBs in newer version of Preset or new Database Version. 

- A jupyter notebook, to test the database connection URI ( same as preset), will create and load data in the datbase. It also has reference/images how the dashboard should look. 

- A JSON file is an exported dashboard that has several charts and it is the expected results. 

- Source data from COVID19 Data that is already transformed based based on [this blog](https://preset.io/blog/2020-03-12-corona-virus/)


## Install if you want to use Virtual Env 
```bash
# setup a virtual env
virtualenv env -p /usr/bin/python3
source env/bin/activate

# install required deps
pip install -r requirements.txt

# start notebook server
jupyter notebook
```

## If you don't want to use virtual envirment just open the Notebook 
```
# start notebook server
jupyter notebook
```
