# About-API

API stands for Application Programming Interface. This allow two softeware application to communicate with each other .
--TYPE OF API -
1.Web API - http like api for google map etc.
2.Library API - like for pyhton etc.
3.Local API - like Windows API
4.Operating System API -
5.Database API -like for mysql connector
6.Hardware api - like printer,camera

--Common TYPE OF WEB API 
1.REST API-
Uses HTTP methods like GET, POST, PUT, DELETE.
Data formats: JSON or XML.
Example: GitHub API.
2.SOAP API-
More rigid and secure, suited for enterprise environments.
Example: Payment Gateway APIs.
3.GraphQL API:
A query language for APIs.
Allows clients to request specific data fields.
Example: Facebook GraphQL API.
4.RPC API (Remote Procedure Call):
Executes code on a remote server.
Variants: XML-RPC, JSON-RPC.

--BASIC COMPONENT OF AN API:

with the help of real life example let's understand this :
You are building a front-end application for an e-commerce store, and you need to interact with the server to retrieve product information, add a product to the cart, update its quantity, or remove it from the cart.

ENDPOINT - Specific URL where the API can be accessed 
          example tp access the product sevtion you need the URL accordinglly.
Request - The data or parameter send to the API 
          When you want to search for "laptops", you can send a GET request with a query parameter:
          sql  GET https://api.ecommerce.com/products?search=laptop
Respond - The data the API returns to your request.
           Example:After sending the request above, the server responds with the product details in JSON format:
json
[
  {
    "id": 101,
    "name": "Gami

Authentication
 Ensures secure access to the API.
           Example:To prevent unauthorized access, the server requires an API key or OAuth token.
           You include this in the header of the request:
           plaintext   Authorization: Bearer YOUR_API_KEY
Method-
GET - retrive the producrt details then user request it and you have provide the response to it 
POST - Add new product to the cas=rt - request and ewe need to provide the response.
PUT - Increase the quantity of the product - request and respone accordinglly .
DELETE - remove the product from the cart . request and resopnse 


--HOW API WORKS 
1.REQUEST - the client send the request to the API endpoint 
2.API SERVER - Proces sthe request and Fetch or modifie the requested data .
3.Response- The server sends back the response in a predefined format (e.g., JSON, XML).

Popular API Tools
Postman: For testing and debugging APIs.
Swagger/OpenAPI: For designing and documenting APIs.
Insomnia: Lightweight API testing tool.
cURL: Command-line tool to interact with APIs.

