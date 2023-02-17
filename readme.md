# How to access a Springboot application via LDAP security?

In resources is a file test-server.ldif. Together with application property:

spring.ldap.embedded.ldif=classpath:test-server.ldif

you will have a (test) LDAP server. In there is a user which you can use to access 

user : ben  
password : benspassword

or

user : bob  
password : bobspassword


http://localhost:8080

