## At the very beginning
1. Set your machine
    - Install Salesforce CLI
    - Install VS Code + Salesforce Extensions for Visual Studio Code
    - Install and Setup Git
    - Create GitHub account and link a Github folder project to the folder project on you machine

2. Create locally a project folder and set everything to be pushed into your verson controll system
   - SFDX: Create Project with Manifest ( command to “create” a new folder and set it up for SFDX )
   - Initialize the repositoy ( git init command OR Source Control Button in the Editor --> Initialize repository )
   - COMMIT - Add all files to be commited ( git add . command OR manually add the file changed to the stage --> Commit button )
   - Publish branch 
   - Push ( command to “push” your local changes to the remote origin )

3. now that we have a remote folder on Git-Hub, each developer can branch out and work on their own version of the code

4. From the developer local machine:
    - Git Clone the remote repository, to have locally all the data. Do that by using git clone https://github.com/[username]/[repository name].git OR Plaette --> Git Clone

5. Branch out from master
    - Palette --> git create branch OR by using git commands
    - Publish the branch ( as we did before )

6. Authorize an ORG
    - Link your folder to an Environment ( Test, Prod ....)
    -  SFDX: Authorize an Org

7. Start work on the new features !!!!!!!
----

## Ella Features
1. Create a new custom Object - "Language Course Instructor" & "Language Course"
2. Select a tab for them
3. Create a M/D field on the "Language Course" object related to the "Language Course Instructor" object
4. Track the chenges of needed
5. Retrieve the changes from the Sandbox to the local SD project 
 - Via Editor ( Org Browser )
 - Via Salesforce CLI
6. Commint and push on Git-hub branch
7. Make a Pull request to merge the new feature in the master branch

----

Ella Environment: https://mycompanyltd-dev-ed.develop.lightning.force.com/lightning/page/home
Juan Environment: https://empathetic-koala-ia8o57-dev-ed.lightning.force.com/

----

## Juan Features
 1. First, Juan deploys Ella’s changes to his Developer sandbox
  - Select the new object created, right click deploy 
   OR
  - sfdx force:source:deploy --metadata CustomObject:Language_Course_Instructor__c, \
    CustomField:Language_Course__c.Course_Instructor__c

2. Juan will developed the Trigger









# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
