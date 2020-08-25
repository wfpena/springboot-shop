## Shop Web Api

Basic CRUD Rest API for Customers, Orders and Products entities.

## Entities

### Customer

`

    // Auto Generated by increment
    Long id

    @NotNull
    String name;
    
    @NotNull
    String individualTaxpayerRegistry;

`

### Order

`

    // Auto Generated by increment
    Long id

    String description


`

### Product

`

    // Auto Generated by increment
    Long id

    String name

    String description


`

### Running Locally

1. Install Maven and Java (JDK 11).

2. Download and run H2 Database and set the config in the `application.properties` file.

3. Run `mvn spring-boot:run` in the root of the project.

### Running unit tests

1. Run `mvn test` in the root of the project.