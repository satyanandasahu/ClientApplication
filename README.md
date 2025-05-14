Client Application is an application to test PersonalInformationRestAPI.
This application contains get.html page to retrive information based on PersonId and create.html to create a new person record. 
get HTML page is using jquery for get method, check the URL in ajax call. Make sure it matches your PersonalInformationRestAPI deployed application URL
create HTML page is using jquery for post method, check the URL in ajax call. Make sure it matches your PersonalInformationRestAPI deployed application URL
run the maven command "mvn clean install" to generate the war.
Deploy and test.

Note: 
1.  Both the PersonalInformationRestAPI & ClientApplication should be deployed in same Tomcat.
2.  To better understand this project this video on youtube link: 
    1.	https://youtu.be/o8IIkcmXt6Q  (Docker)
    2.	https://youtu.be/J2GZhlhVKt4 (Creating Client Application (UI) And Deploying )
    3.	https://youtu.be/AL4Z3_FpjMY (Spring Boot Application deployment on embedded tomcat & external tomcat )
    4.	https://youtu.be/7kptCL3oeyw (Rest API Integration with Service Layer & Test using SOAP UI )

