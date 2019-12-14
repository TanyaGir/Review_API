# Review_API
# MySQL
Please make sure a MySQL instance is running and listening to port 3306.
A database named `productreview` is already created.


# MongoDb
Please make sure a MongoDb daemon is running and listening at port 27017 and the MongoDb user has appropriate credentials to create a `productreview` database.

Please change properties in application.properties to match proper credentials for the application to connect to the database servers.

If the application is not able to create connection to the database, then the application throws error shown below.

`org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'flywayInitializer' defined in class path resource [org/springframework/boot/autoconfigure/flyway/FlywayAutoConfiguration$FlywayConfiguration.class]: Invocation of init method failed; nested exception is org.flywaydb.core.internal.exception.FlywaySqlException:`
