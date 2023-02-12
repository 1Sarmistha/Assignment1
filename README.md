# Automation of Oppenheimer Project Assignment

## Pre-requisite:
##### 1. Java needs to be installed/setup
##### 2. Set the PATH

## How to Install the required Software:
##### 1. Install pip
##### 2. Check the PIP version and it should be the latest version(PIP --version)
##### 3. Install python using PIP 
##### 4. Set the Python path in the environmental variable path.
##### 5. Check the Python version using Python --version
##### 6. Install robot framework using PIP
##### 7. Check the location for robot framework and update the same in environmental variable
##### 8. Install robotframework-seleniumlibrary 
##### 9. Install the selenium Chrome driver and set the path in the environmental variable
##### 10. check all the installation using PIP -list
##### 11. Install the dependent libraries
##### 12. Open the ‘assignment1’ project (downloaded from Github)

## How to Run the Test Cases:
##### 1. Keep the jar OppenheimerProjectDev.jar file under “Automation” folder.
##### 2. Run the application- “<java -jar OppenheimerProjectDev.jar>” to start the Sprint-Boot project.
##### 3. Give it a min or two to boot up 
##### 4. For execution of specific file Execute command: - “python -m robot -d results <location(File name).robot>”
e.g python -m robot -d results .\Automation\Scenario3_AC3_POST_Upload.robot
