# Fuank-customer-api
This API will upsert Customer data into Salesforce and Cosmos dB

This API is not deployed into cloud, to run the project into local you can simply download the zip folder and run as mulesoft project. No configuration or key is required.
Postman collection is available in src/test/resources folder.
Two end points are there, one is to get the customer details and other is to upsert into Salesforce or Cosmo DB.

Get - http://localhost:8081/api/customerDetails?customerId=c0195781-111f-4d2e-8d68-c3bf9a742d38

Post - http://localhost:8081/api/customerDetails

Client and Secret Id is required in headers. However, In back end no validation will happen, since the project is not deployed in cloud.
