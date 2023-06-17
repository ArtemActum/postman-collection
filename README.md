# Postman-collection
### Table of Contents
- #### Introduction
- #### Installation

### Introduction
Example of basic API tests in Postman based on [documentation](https://restful-booker.herokuapp.com/apidoc/index.html) 
- I have prepared tests with positive and negative tests, variables as a URL, tests that automatically check status code and schema validation
![image](https://github.com/ArtemActum/postman-collection/assets/102807433/51f2643e-51dd-4738-82be-4f81e7599ebc)
- Schema is a specification for validation the structure of JSON data, which checks type of object and name of fields and other.
- Schema is generated [here](https://www.jsonschema.net/) based on response, a big benefit of using schemas is that it shows the path of the error. 
![error](https://github.com/ArtemActum/postman-collection/assets/102807433/9dd74173-0447-4abc-b291-e0e6c4d6c3f1)
#### Negative tests:
![image](https://github.com/ArtemActum/postman-collection/assets/102807433/d5a75b4d-8f00-4868-8a77-6fd29405a82e)
- I added basic negative tests with negative number in string type, 
- Here is possible to add more negative cases with different combinations of type of objects such as string, integer, boolean or float. 
- Different integers or strings such as chinese letters, special signs, negative numbers, date format.
- Send empty Body to the same request.

#### Requests:
- Auth - CreateToken
- Booking:
- GetBookingIds
- GetBooking
- CreateBooking
- UpdateBooking
- PartialUpdateBooking
- DeleteBooking
- Ping - HealthCheck

![Postman](https://github.com/ArtemActum/postman-collection/assets/102807433/0e0c590c-1b7e-4942-a6b6-fe54e2e1109f)

### Installation
To use this Postman collection, you need to have Postman installed on your local machine. You can download and install Postman from the official website: https://www.postman.com/downloads/. 

Once you have installed Postman, you can import the collection into your workspace by following these steps:

1. Clone this repository to your local machine or download it as a ZIP file.
2. Open Postman and click on the "Import" button in the top left corner.
3. Select the "Import From File" option and choose the downloaded collection file (**`postman-collection.json`**).
4. The collection will be imported into your Postman workspace, and you can start exploring and executing the requests.
