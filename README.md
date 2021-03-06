# Cicloguia API

## Goal

Apply all my knowledge about python web development and cloud services, to create a fast, reliable, and easy to maintain
REST-API. Which will expose thousands of bicycles products, allowing riders to identify prices fluctuations, stock, and
sales.

## Design patterns

* Service layer
* Repository

## Development technologies

* Python 3.8
* Docker
* Localstack: amazon/dynamodb-local
* DynamoDB local: localstack/localstack

## Python dependencies

* FastAPI
* Pydantic
* Pytest
* Uvicorn
* Boto3

## Development stack

1. Install the python package locally: `cd service && pip install -e cicloguia`
2. Build the stack: `docker-compose build`
3. Launch the stack: `docker-compose up -d`
4. Upload the sample products: `python service/src/entrypoint/uploader.py`