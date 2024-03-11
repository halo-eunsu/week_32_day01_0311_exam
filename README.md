# MySQL 데이터베이스 연결 설정

spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name?useSSL=false&serverTimezone=UTC&allowPublicKeyRetrieval=true

spring.datasource.username=your_database_username

spring.datasource.password=your_database_password

# JPA 설정
spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true

spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5InnoDBDialect
