# Exercise Workflow
This page describes the workflow for afternoon exercises and projects at Boolean. When given an exercise, you will be provided with a link to a GitHub repository that contains the exercise instructions and any template code. 

Prior to following this guide you should have:

1. Signed up to a GitHub account
2. Been added to the relevant GitHub team for your Cohort (your instructor can invite you)
3. Have installed Git on your development machine
4. Have setup and configured SSH Keys

## 1. Fork the repository
The first step is **fork** the repository. You can do this from the repository page in GitHub by pressing the **fork** button in the top right corner:

![Forking](images/fork.png)

Forking the repository takes a copy of the repository and add's it to your own GitHub account.

If you cannot see the exercise page or get an error trying to access it, contact your instructor. The cause is likely to be one of the following:

* You are not signed in to your GitHub account
* You have not been added to the GitHub team for your cohort
* The Cohort GitHub team has not been given access to the repository

## 2. Clone the fork
One the repository has been forked, you then *clone* the repository to your local machine. Cloning takes a copy of the repository from GitHub and stores it on your local machine so you can start working on it.
 
To clone the repository, go to the **forked* repository page in GitHub. This is the copy of the repository that should exist on  your account. You can verify you are looking at the forked copy bu checking for the message underneath the repository name:

![View Forked](images/view-forked.png)

From here, we want to press the green code button, then select the `SSH` tab, and then the copy icon to copy the repository SSH URL to the clipboard:

![Clone Address](images/clone-address.png)

The repository SSH URL is what we need to provide to the Git command on our local machine to do the clone.

Once this is copied, open up your terminal on Mac or GitBash on Windows. Navigate in the terminal to the directory where you want to repository code to be cloned to and then use the `git clone` command with the copied SSH url (you should be able to right-click in your terminal to paste the url you copied) to clone the repository. Here is how it should look on GitBash on windows:

![Clone](images/clone-command.png)

## 4. Work on the project in VS Code

## 5. Stage and commit your changes

## 6. Push your changes

## Additional reading
