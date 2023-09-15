# Flask Store API

This is a simple Flask API for managing stores and their items. You can use this API to create, retrieve, and manage stores and their associated items.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed.
- Required Python libraries can be installed using `pip`:

  ```bash
  pip install Flask

Postman for testing the API endpoints.

Getting Started:

1.Clone the repository:
- git clone https://github.com/Divyabhardwaj04/flask-store-api.git

2.Navigate to the project directory:
- cd flask-store-api

3.Run the Flask application:
- python app.py

The API will be available at `http://localhost:8000`.

API Endpoints
Get Store by Name
`GET /store/<string:name>`: Retrieve information about a store by its name.
Get Items for a Store
`GET /store/<string:name>/item`: Retrieve items for a specific store by name.
Create a New Store
`POST /store`: Create a new store by providing a JSON payload with the store name.
Create Items for a Store
`POST /store/<string:name>/items`: Create items for a specific store by providing a JSON payload with the item name and price.

## Testing with Postman
Install Postman if you haven't already.

Open Postman and create requests to test the API endpoints listed above.

Use the base URL `http://localhost:8000` for your requests.

Use the HTTP methods (`GET`, `POST`, etc.) and request bodies as mentioned in the API endpoints section.

Send the requests and examine the responses to ensure the API is functioning as expected.
