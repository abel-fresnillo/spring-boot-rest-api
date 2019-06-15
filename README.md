# Spring Boot Rest API Application

Very basic Spring Boot Application that exposes a Rest API with CRUD operations for a Customer entity. 

The application uses MongoDB to store the Customer data.  

## Getting Started

### Prerequisites

The application was tested using the following software versions:

```
MongoDB v4.0.2
```

### Running the Application

If you haven't started your MongoDB Deamon, execute the following command to start it:

```
mongod
```

Once you checked out the project run Maven Install:

```
mvn clean install
```

To run the project execute the following command:

```
mvn spring-boot:run
```

The application will start and the API will be available in the URL below, you can use Postman or the Rest API client of your choice:

http://localhost:8080/customers

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* **Abel Fresnillo** - [abel-fresnillo](https://github.com/abel-fresnillo)