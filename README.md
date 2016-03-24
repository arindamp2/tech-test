# tech-test
Technologies Used : Java, Selenium, Maven; Editor Used : IntelliJ

Instructions:

- Download the zip file(sample-test.zip) and upzip to a specified location in your work station
- Please note that, I have used Firefox version 45.0.1 for testing, I hope it would work with other versions
- Due to some problem with my installed firefox version, firefox profile has been used, which is also present under zipped file
(sample-test\src\test\resources\profile) 
- Please note that, in all the tests, the location of firefox exe and firefox profile are hardcoded, like 
- new FirefoxBinary(new File("C:\\Program Files (x86)\\Mozilla Firefox\\firefox.exe"));
- The location is new FirefoxProfile(new File("C:\\test\\sample-test\\src\\test\\resources\\profile"));
- Please Change them accordingly or just create a folder named 'test' under C driver and unzip the file there.

- After unzipping, please go to the directory and use mvn clean install. If the project is opened in  Intellij, all the dependencies 
can be auto imported or else click the magical maven import buttons in intellij
- I have added in total 6 tests, named : 
 TestAdminLogin
 TestAddEditDeleteBranchFeature
 TestAddEditDeleteStaffFeature
 TestPaginationInTheStaffPage
 TestAccountEdit
 TestRegisterNewAccount

 - TestAccountEdit fails, since account information could not saved after editing
 - TestRegisterNewAccount also fails, since new account registration was not possible
