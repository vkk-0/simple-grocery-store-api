🛒 Simple Grocery Store API - Postman Collection
This repository contains a Postman collection for testing the Simple Grocery Store API. It includes structured requests for key functionalities like products, cart, orders, and error validation.


📦 Collection Overview
The collection is organized into the following folders:

Happy path – Valid scenarios covering complete user and order flows.

Missing authentication – Negative tests where auth is missing or invalid.

Invalid inputs – Tests that trigger validation errors.


🌐 Environments
This collection supports two Postman environments:

Production

Testing

These environments define variables such as:

baseURL – Base API URL (e.g., https://api.example.com)

accessToken – Token used for authenticated requests

Dynamic variables such as productId, cartId, and orderId are set during runtime using test scripts.

Using an Environment
Open Postman and go to Environments.

Click Import and upload Production.postman_environment.json or Testing.postman_environment.json.

Select the desired environment from the environment dropdown before running requests.

🛠️ Getting Started
Prerequisites
Postman installed

API base URL and access credentials (if required)

Importing the Collection
Open Postman.

Click Import > Upload Files.

Select Simple Grocery Store API.postman_collection.json.

Click Import.


🔄 Usage Guide
Start with any authentication or registration request if needed.

Use requests under the Happy path folder to simulate valid flows.

Use Missing authentication and Invalid inputs folders to test error handling.

Use the Collection Runner to automate and batch run scenarios.


📁 Files
Simple Grocery Store API.postman_collection.json – Main collection file

Production.postman_environment.json – Environment variables for production

Testing.postman_environment.json – Environment variables for test/development


🧪 Tips
Use console.log() in scripts for debugging responses.

Use pm.environment.set() to store dynamic values between requests.

Enable Postman Console (View > Show Postman Console) to see runtime logs.

