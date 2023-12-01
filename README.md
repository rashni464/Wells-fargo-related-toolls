Autosys: It a Job scheduling tool 
ART: Art is used to raise access to lower environments
Wanda: To request any software use Wanda.
AIMS: This is access request tool for PROD and DB acess
Beeline: Time sheet for Randstard
Stamp: Timesheet for Wells fargo
Jenkins: To check the build sucess when we commit in the github
Jfrog: Is the artifactory. Normally for installing node we use internet but in the work place if we want to install angular using npm then npm goes to internet to installteh angular framework but as we are working in  a organization we have firewall that stops to go to internet for sequirty reasons so need to tall npm that when ever we run npm go to aritifact repository . Example Jfrog or nexus. We need to create a .npmrc file in the c:\users\ folder by using the bash with linex commends. Because we can't create a file directly here. Once we create a file then we need to  ive the registry link of JFROG from wherewe run the command it will look into .npmrc and download the angular.
Maven: Aswe use npm in angular same way maven is used in Java as a pacakage module.
UCD: Urban code Deployment : In UCD we see all the components which are in dev, dev1,sit and UAT. We can redeploy the components with the required versions in UCD. We can also add properties in the UCD.
PCF: Pivotal cloud Foundry: This is where we can check the component is running or down. 
Threadfix: We use thread fix to check any Vulnerability issue is there or not. we can also upload the scans in Threadfix once that is sucesful in Jenkins.
Sonar: We use sonar to check the code coverage. Based on that we write the code.

HOW TO INSTALL ANGULAR:
Step1: Using bash create  a .npmrc file with linex commands in the c:\users\k064113 path.
Step2: Go to Jfrog
Step 3: At the top right,  click your username, then "set me up", for "package type" select npm and for "Repository" use "npm-external-virtual"
Step4: You can then enter your password and it will tell you what to include in your .npmrc to correctly download through artifactory.
Step5: Give the url and credientials in the command prompt it will update in.npmrc or  directly you can copy and paste in .npmrc file.
step 6: Now you are set to install angular.
