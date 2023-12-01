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


How to add path in the environment variables:
Step1: Go into environment variables
Step2: add the path in the user varaibale c:\users\k064113\appdara\roaming\npm\nide_modules
Step3: Now you can useng it won't show any error.

How to clone project from GITHUB:
Step1: Go to github and take project and clone the uRL
Step 2: Go to c:\users\k064113\projects and open CMD in serach
Step 3: In the cmd type git clone url
Step4: go to vs open that project
Step5: We need to use main-app so go to terminal and type cd main-app
step6: you will be in main-app then istall all the packages by typing npm i
step 7: It will istall all the packages now. you need to type npm run start.

How to stash the cde in VS code to github:
Step1: $git stash save -u "backedchages"
 Note1; to check stash happend or not
 $git stash list
 Note2: To get the saved stash code in your local
 $git stash apply stash2{1}
 stash number various based on stash ist we need to pick it.

 How to push the code in github and raise the PR request and merge the branch:
 Step1: Go to project and open the terminal
 Step2: git status
 step3: git add.
 step4: git commit -a -m "added code"
 step5: git push
 step 6: if you want to get the pushed code
 step 7: git pull

 How to create a new feature brach

 Step1: Go to github and click on branch fropdown
 step3: goto find or create abranch. in that type feature/xxx
 step4: A new branch is created now go to VS and in the terminal type git checkout feature/vvvvdv

 How to pass the lint:
 Step1: go to main-app
 Step2: ng lint

 How to push the code in intellij
 Step1: git status
 step2: git add file1
 Step3: git status
 step4: git commit -m "made changes"
 Step5 : git push -f origin branch name.
 
 

