# Scalable Data Connector API

A production-ready REST API backend built using Python and Flask.

## Features
- RESTful API design
- JSON request validation
- Structured error handling
- Logging implementation
- External API integration
- Health check endpoint

## Tech Stack
- Python
- Flask
- Requests
- Gunicorn

## Endpoints
GET /              -> Health check  
POST /ingest      -> Data ingestion  
GET /fetch?url=   -> Fetch external API data  

## How to Run

pip install -r requirements.txt  
python app.py
