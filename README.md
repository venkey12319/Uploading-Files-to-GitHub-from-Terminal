# Uploading-Files-to-GitHub-from-Terminal
Guide to Uploading Files from Terminal to GitHub UI

How to Upload Files from Terminal to GitHub UI

Create a GitHub Repository:

Log in to your GitHub account and create a new repository. You can choose to make it public or private.
Open Your Terminal:

Open your Linux terminal or any other terminal you prefer to use.

Clone the Repository:

Copy the HTTPS link from the "CODE" section of your newly created GitHub repository.

Run the following command to clone the repository to your local machine:

**git clone https://github.com/venkey12319/CI-CD-Pipeline-With-EC2-Node-Js.git**

Navigate to the Cloned Repository:

Change your directory to the cloned repository:

**cd CI-CD-Pipeline-With-EC2-Node-Js**

Create the Desired Directory Structure:

Create the directory structure as needed:

**my-node-app/
├── src/
│   └── app.js
├── appspec.yml
├── buildspec.yml
└── scripts/
    ├── install_dependencies.sh
    └── start_server.sh
    **
Add Files and Folders to Git:

Add the created files and folders to the staging area:

**git add .**

Commit the Changes:

Commit the staged files with a message:

**git commit -m "Initial commit"**

Push the Changes to GitHub:

Push the committed changes to the GitHub repository:

**git push origin main
or
git push origin master**

Successfully Uploaded Directory

Following these steps, you successfully uploaded the desired directory to your GitHub repository.

Note:

You can also create a new repository directly from your local machine using Git commands.



