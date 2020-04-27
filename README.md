This repository contains details how to use a defined dashboard to test new or existing databases engine.
As Support or CSM there will be a need to test customer issues and this could be in different Database engine with this process, you warranty that test something that works in others DBs in newwer version of Preset or new Database Version. 

- A jupyter notebook, to test the database connection URI ( same as preset), will create and load data in the datbase. It also has reference/images how the dashboard should look. 

- A JSON file is an exported dashboard that has several charts and it is the expected results. 


## Install
```bash
# setup a virtual env
virtualenv env -p -python3
source env/bin/activate

# install required deps
pip install -r requirements.txt

# start notebook server
jupyter notebook
```
