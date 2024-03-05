# Quipu/ Automation Practice application
 
Please read me completely to ensure that test automation process executes with no issues.
This framework - Page Object Model with Cucumber supports Test automation on Web Applications. However, the framework can be easily extended to support executions on Mobile Device, API and Desktop(using Java) and configured to support execution on Windows, Linux and Mac OS as well.
You are welcome to enhance and upgrade the framework based on your needs.
We also encourage your valuable contributions as well in upgrading this framework.
If you intend to make some changes or upgrade, please follow the below instructions:
- Fork the repository
- Apply and commit the changes to the forked remote repository
- Raise a pull request and assign it to us, DO NOT commit the changes to the original repository unless approved
- Please inform us at the earliest so that the changes are reviewed and approved
 
# Pre-requisites:
- JDK 1.8 or above
- IDE of choice with Maven Support enabled
 
# How to set up and execute the framework on your system:
1. Launch Git Bash in an empty folder
2. Clone repo using HTTPS or SSH
3. Open the project in an IDE and build as Maven project
 
Note: If you find additional folders(.idea, .eclipse, .iml files), please do not delete as they are the configurations for running in the respective IDEs(.idea - IntelliJ IDEA, .eclipse - Eclipse IDE).
 
# How to create(or add) a test case into the existing framework:
1. Create New feature under src/test/java/feature
2. Add Test Steps as scenarios in the added feature file
3. Declare and define the methods in appropriate packages inside src/test/java/steps
4. Add Associated methods for the feature in the existing or new step definitions based on the page/functionlity

# Execution
# Goals : clean install compile test
# Steps:
1.Open the runner class - CucumberRunner inside src/test/java/runner
2.Add required features, tags as per your execution needs
3.Run the CucumberRunner.java runner file
 
 
# Output reports:
1. Cucumber reports link will be generated during runtime and available in the console