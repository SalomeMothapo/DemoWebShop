This project uses masterthought maven plugin for cucumber reporting,please refer to the attached
inoder to run this project you will have to use either mvn clean verify for a new target folder to be created with report,or you can simply use the testRunner class to execute it
its a cucumber BDD model that consist of pages for as POM however pagefactory was not added to lack of capacity on my side
we have hooks class that will automatically open your browser and page  everytime you run the script by using the @Before anotion ,we also have the @Fter method that will enable the browser to automatically close and quit the browser that are ruuning
and then we have a feature file for Registration,i could not do the Login part because it has some bugs,after registering a user I was expecting to login using the registered user which did'nt happen and this was a challenge for me cause everytime I test my scrip I had to register new user
report can be found under this directory target/cucumber-html-reports/overview-features.html
