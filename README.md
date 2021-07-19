# TechProjectWX
Created by Deepa Kiran on 18Jul2021

# UI Automation
Tools used: Sahi Pro\
Language: java script\

# Pre-requesites
Java 1.6 or above\
Sahi Pro 8.0 above

# Installation and Setup for Sahi pro trial license
Open [Download sahi trial](https://www.sahipro.com/free-trial)\
Register with your details (please enter office email id)\
Download Sahi pro trial version via link sent in your email\
Install Sahi pro\
Open Sahi pro and enter product key you received in email\
Check for chrome and necessary browsers visible in Sahi dashbaord\
If not visible, Click on link "configure" in sahi dashboard and set up right path for each browser and restart Sahi\
Click on SSL link in Sahi dashboard

# Setting up project
Navigate to Sahi installation folder\
Navigate to userdata/scripts/\
Download techProject_Deepa from Git\
Copy project folder in scripts/ folder

# Running Test suite - "covidGameRegressionSuite.dd.csv"
Click on "bin" in sahi dashboard to open command line\
type "testrunner" and enter to see different ways or running test suite OR\
run command - testrunner techProject_Deepa\testScenarios\covidGameRegressionSuite.dd.csv https://responsivefight.herokuapp.com/ chrome\
Click "Logs" in sahi dashboard to view logs

# Framework and Test Scenario Details
Page object model and Hybrid Framework\
Different approaches have been taken to design test scenarios like: End to end scenarios, Data driven with fixed and dynamic data sets, simple function with parameterised data etc.\
Different ways of test suite creation in Sahi tool has been demonstrated\
Tagged test scenarios to run happy path or full scenario\
To try running happy path of Bus game scenario - run below command in command line as mentioned above - \
testrunner techProject_Deepa\testScenarios\busGame.xlsx https://responsivefight.herokuapp.com/ chrome "happy"

# Known Issues
1. User not able to create warrior in Internet explorer\
2. First game (Danger one) is not working correctly, hence not automated\
\
Other issues due to which you see script failures in the logs have been reported in Defects.md file

# Challenges
## Resolved ones
1. Handling same question with different set of answers in Bus Game\
2. Identifying newly created warrior on Leaderboard page if more than one warrior of same name exists\
3. Planning test scenarios
## Unresolved ones
1. Wrong Answer modal dialog that just shows up on screen and immediately diappears when navigating to between pages\
2. More detailed test scenarios could not be added due to time constraints\
3. Running the developed scripts in sahi's open source version

# High level report
![RegressionSuiteReport](https://github.com/deepakiran1116/TechProjectWX/blob/main/techProject_Deepa/techProjectReportWX.JPG)

# API Automation
Tool used: Postman\
Tests written in: Java script\

# Pre-requisites
Download Postman [here](https://www.postman.com/downloads/)\
Install and Open Postman\
Download Postman collection and environment files from github\
Navigate to File > Import\
Import downloaded postman collection and environment\
Run collection and see the results\

# Known issues
Delete user API is throwing 400 error code
