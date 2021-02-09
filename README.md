# Welcome to Amazon Gallery App — Full Stack App with Micro Services
## Contents

1. [Backend API](#backend-api)
1. [Amazon Scraper](#amazon-scraper)
1. [Connector Script](#connector-script)
1. [Frontend](#frontend)

## Backend API

### Setup Python Virtual Environment
```buildoutcfg
cd Backend
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```
### Running Server
Make sure to be in `Backend` directory.
```buildoutcfg
./mange.py migrate
./mange.py runserver
```
- Go and check endpoints `http://127.0.0.1:8000/products` etc.

## Amazon Scraper

### Run Amazon Scraper
Make sure to activate venv and be in `Backend` directory.
```buildoutcfg
python AmazonScript/scraper.py
```

## Connector Script

### Run script
Make sure to activate venv and be in `Backend` directory. <br>
Make sure to have .json files in your `AmazonScraper/reports` directory. <br>
Make sure to run your server before running script. <br>
```buildoutcfg
python AmazonScript/api_connector.py
```

## Frontend

### Run Live Server
Download Live Server extension to VS code and run server.

