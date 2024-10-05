# Easy-docker-DB-configs

- configs inspired form https://docs.chaicode.com/postgresql-installation/

## MySql Spring boot application.properties

- spring.datasource.url=jdbc:mysql://localhost:3306/chaiDB
- spring.datasource.username=<username>
- spring.datasource.password=<password>
- spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
- spring.jpa.hibernate.ddl-auto=update
- spring.jpa.show-sql=true

## PostgreSql Spring boot application.properties

- spring.datasource.url=jdbc:postgresql://localhost:5432/chaiDB
- spring.datasource.username=<username>
- spring.datasource.password=<password>
- spring.datasource.driver-class-name=org.postgresql.Driver
- spring.jpa.hibernate.ddl-auto=update
- spring.jpa.show-sql=true
