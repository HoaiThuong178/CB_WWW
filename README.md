# CB_WWW

## persistence
```xml
<persistence-unit name="default">
  <properties>
    	<property name="jakarta.persistence.jdbc.driver" 			value="org.mariadb.jdbc.Driver"/>
    	<property name="jakarta.persistence.jdbc.url"		
    value="jdbc:mariadb://localhost:3306/GK?createDatabaseIfNotExist=true"/>
    	<property name="jakarta.persistence.jdbc.user" value="root"/>
    	<property name="jakarta.persistence.jdbc.password" value="sapassword"/>
    	<property name="hibernate.show_sql" value="true"/>
    	<property name="hibernate.hbm2ddl.auto" value="update"/>
  </properties>
</persistence-unit>

## build.gradle
implementation 'org.mariadb.jdbc:mariadb-java-client:3.2.0'
compileOnly('jakarta.servlet:jakarta.servlet-api:6.0.0')





