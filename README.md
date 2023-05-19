# Stock Management System

The Stock Management System is a web-based application developed using Spring Boot. It offers a comprehensive set of RESTful endpoints for efficient stock management, including retrieval, update, insertion, and deletion of stocks based on various criteria.

## Framework and Technologies

The Stock Management System is built using the following technologies and frameworks:

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful API

## Endpoints

The Stock Management System provides the following RESTful endpoints:

- `GET /stock/type/{stockType}` - Retrieves stocks based on the specified stock type.
- `GET /stock/abovePrice/price/{price}/lowerData/date/{date}` - Retrieves stocks with prices above a specified value and lower than a specific date.
- `GET /stock/cap/{capPercentage}` - Retrieves all stocks above a certain market cap percentage.
- `POST /stock/` - Inserts new stocks into the system.
- `PUT /stock/marketCap/{marketCap}/id/{id}` - Updates the market cap of a stock using its ID.
- `PUT /stock/stock/type/id` - Updates the stock type of a stock using its ID.
- `PUT /stock/stock/{id}` - Updates stock information using its ID.
- `DELETE /stock/ownerCount/{count}` - Deletes stocks based on the owner count.

## Getting Started

To use the Stock Management System, follow these steps:

1. Clone the repository or download the project files.
2. Import the project into your preferred Java development environment.
3. Set up the necessary dependencies and configurations, including the database configuration.
4. Build and run the application.
5. Access the endpoints using an HTTP client such as cURL, Postman, or a web browser. Send requests to the appropriate URL and use the specified HTTP methods.
6. Ensure that you provide the required request parameters and payload as documented in the endpoint descriptions.

## Summary

The Stock Management System is a robust Spring Boot application that provides a RESTful API for efficient stock management. It enables users to retrieve stocks based on type, price, and date, update stock information, insert new stocks, and delete stocks based on the owner count. By following the provided endpoint documentation and utilizing the appropriate HTTP methods and request parameters, users can seamlessly perform various stock management operations.


