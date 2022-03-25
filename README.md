# Tomcat 10 Sample Application

Tomcat 10.0.x is the first Tomcat release to make the jump from Java EE to Jakarta EE. This means that applications running on previous versions of Tomcat will almost certainly require changes to run on Tomcat 10.0.x. This sample application directly targets Jakarta EE 9: the [pom file](pom.xml) has been updated to use `jakarta.jakartaee-web-api`, whereas an older version of this application would have used `javax.servlet-api`. If you browse the source code, you can see that import statements that would have used `javax` in the past are now using `jakarta`.

If you have an existing Tomcat 9 application, you can use the [Tomcat Jakarta EE Migration Tool](https://github.com/apache/tomcat-jakartaee-migration) (under development) to migrate your source code or archive files from Java EE APIs to Jakarta EE APIs for Tomcat 10. For more information, please see the official [Tomcat 10 migration guide](https://tomcat.apache.org/migration-10.html) from the Apache Foundation.

## Deploy to App Service

ToDo
