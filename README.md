# Clicks are Code: Participant Repository and Workshop Details

This repository is for the workshop program for ["Clicks, Not Code" to “Clicks are Code”: Add Git to your #Admin Superpowers](https://www.meetup.com/Salesforce-Philly/events/258124509/) with David Reed and Andrés Catalán. Participants should fork this repository to join in the workshop. The full details for participants are below.

## Participant Handout

You’re going to start with the core of a small application, supplied in source code form. You’ll be given a sheet with a small, administrative Salesforce task to achieve. Your goal is to push the source you’re given into a new Salesforce DX scratch org, perform your task, retrieve your updated source, and commit it to Git to share it with your team.

### Pre-Work

We hope you’ve completed this work prior to the workshop to get your computer ready to participate. If you didn’t already, please try to complete these steps during the talk and demo portions of the program so you’ll be ready to get hands-on during the workshop.

- Sign up for a new Salesforce Developer Edition (https://developer.salesforce.com/signup) or use an existing one if you wish. Do not use your Production Salesforce account.
 - In your Developer Edition, turn on Dev Hub (https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_enable_devhub.htm)
 - Sign up for a free GitHub account (https://github.com/join) and validate your email.
 - Install the Salesforce DX tools (https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_install_cli.htm#sfdx_setup_install_cli)
 - Install Visual Studio Code (https://code.visualstudio.com)
 - Install the Salesforce DX extension pack in Visual Studio Code (https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode)

You may need to close and reopen Visual Studio Code after completing the pre-work above before you begin. 

### Workshop Steps

For Visual Studio Code commands (> below), open the Command Palette with Control-Shift-P (Command-Shift-P on a Mac) to start typing.

- Log in to your GitHub account and navigate to the workshop repository: https://github.com/davidmreed/clicks-are-code
- Click the **Fork** button in the upper right corner to create your own copy of the workshop repository. You’ll work inside your own copy, which is called a fork.
- In your copy, click the **Clone or Download** button. Copy the HTTPS URL.
- Open Visual Studio Code and execute **> Git: Clone**. Hit enter and paste your repository URL, then Enter again. Choose a location. 
- Click Open Repository when VS Code finishes.
- Authenticate your Dev Hub (Developer Edition) with **> SFDX: Authorize a Dev Hub**
- Spin up a scratch org with **> SFDX: Create a Default Scratch Org…** (Accept the defaults with Enter).
- Push the project to your empty scratch org with **> SFDX: Push Source to Default Scratch Org**.
- Open your scratch org with **> SFDX: Open Default Org**
- Assign yourself the permission set **Git Project Management** (you’ll be User User).
- Perform the administrative task on your card. Feel free to edit page layouts and create records - we’ve excluded them from this demo for now.
- Pull your changes with **> SFDX: Pull Source from Default Scratch Org**
- Commit your changes with **> Git: Commit All** (or click the Y-shaped icon in the left to build a commit in the Git pane). If you’ve made changes you didn’t want to commit and share, we’ll help you pick only the files you need to commit.
- Use **> Git: Push** to push your work back to your repository on GitHub. Enter your GitHub username and password, if prompted.
- Open GitHub and find your repository. Under the green Clone or Download button, click the **Pull Request** button. Look at what you’ve changed in the source code, and send us the pull request.
- We’ll merge all of the pull requests together and demo a complete app!
