# Hints_2.0_Automation

This framework supports UI automation through Selenium library. Written in Java programming language and supports Extent Reporting. It is expected to support running the test on Jenkins OR BrowserStack cloud. 

###### Built With
1. Selenium - Browser automation framework
2. Java - Programming language
3. Maven - Dependency management
4. TestNG - Testing framework
5. Extent Report - Reporting framework

###### Prerequisite 
1. Selenium - Version 4 or higher
2. Java - Version 1.7 or higher
3. TestNG Plugin - Latest
4. Maven
5. Jenkins
6. Chrome/Edge browser installed - Any Version
7. JAVA_HOME and MAVEN_HOME Environment variable configured
8. Jenkins OR BrowserStack User ID and Access Key - Optional (If needs to run on BrowserStack)

###### Installation and Framework Set-Up
1. Download the zip or clone the Git repository.
2. Unzip the zip file (if you downloaded one).
3. Open the Eclipse and Import the Maven project
4. Navigate to the .\resources folder and open the Config.properties file, change the details like User credentials, Environment name, and check the application details like URL, application credentials (Username, Password) and application test data.
5. Keep the "platFormName" as "local" if you want to test on a local machine.
7. Open the Jenkins UI and configure the project (if needs to be executed from Jenkins)

###### Running Example

###### A. Using TestNG
Right-click on the testNG.xml file and Run as TestNG Suite

###### B. Using CI/CD
Right-click on the Project name and Run as Maven Test

###### C. Using Maven
Access the Jenkins project and click on Build Now

######D. Using Browser Stack


######Execution Report
Extent report HTML file 'ExtentReportResults.html' can be accessed from the test-output folder.

###### Email Extent report
User can get the extent reports via email
