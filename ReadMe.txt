Camel Router Spring Project
===========================

To build this project use

    mvn install

To run this project with Maven use

    mvn camel:run

For more help see the Apache Camel documentation

    http://camel.apache.org/


Example calling in POSTMAN:

POST URL:
http://localhost:9090/service/processOrders

Headers:
Content-Type application/json


Body:
{
    "uniqueOrderId": "12221",
    "orderQuantity": "222",
    "accountId": "3",
    "ean13": "44"
}