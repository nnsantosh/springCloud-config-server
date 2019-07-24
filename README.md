##Eureka discovery server should be up and running so that this config server registers with the discovery server

##Once the config server Spring Boot is started on port 8888 below is the rest end point to access it:
##Rest end point to access default profile
http://localhost:8888/config-client-app/default
##Rest end point that overrides default
http://localhost:8888/config-client-app/prod
##Rest end point for accessing hte properties file directly
http://localhost:8888/config-client-app.properties