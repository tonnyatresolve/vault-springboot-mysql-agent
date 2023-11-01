# Demo of Vault Agent Injector to connect to MySQL Database Server

## Environment variables  
```
database_endpoint=mysql.abc.local:3306
database_name=wordpress
username=[database username] #it will be shown on the API response
password=[database password] #it will be shown on the API response
```

## API Endpoint  
[http://[hostname]:8080/api/v1/companies](http://[hostname]:8080/api/v1/companies)


## Insert a DB record to the database to show the result  
```
use wordpress;
INSERT INTO companies (ID, COMPANY_ADDRESS, COMPANY_EMAIL, COMPANY_NAME) VALUES (1, 'Company Address in MySQL', 'Company’ Email in MySQL', 'Company Name in MySQL');
```