in order to run this project you will have to use either mvn clean verify for a new target folder to be created with the report, or you can simply use the testRunner class to execute it
this project it is a cucumber BDD model that consists of pages for POM however page factory was not added due to a lack of capacity on my side
we have a hooks class that will automatically open your browser and page  every time you run the script by using the @Before method, we also have the @After method that will enable the browser to close and quit the browsers that are running automatically
and then we have a feature file for Registration, I could not do the Login part because it has some bugs, after registering a user I was expecting to log in using the registered user which didn't happen and this was a challenge for me cause every time I test my scrip I had to register a new user
report can be found under this directory target/cucumber-html-reports/overview-features.html
