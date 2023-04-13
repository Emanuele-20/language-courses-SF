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
