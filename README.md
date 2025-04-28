Client Application is an application to test PersonalInformationRestAPI.
This application contains get.html page to retrive information based on PersonId and create.html to create a new person record. 
get HTML page is using jquery for get method, check the URL in ajax call. Make sure it matches your PersonalInformationRestAPI deployed application URL
create HTML page is using jquery for post method, check the URL in ajax call. Make sure it matches your PersonalInformationRestAPI deployed application URL
run the maven command "mvn clean install" to generate the war.
Deploy and test.

Note: Both the PersonalInformationRestAPI & ClientApplication should be deployed in same Tomcat.
