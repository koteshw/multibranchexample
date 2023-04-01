# What’s a Jenkins Multibranch Pipeline?
A multibranch job is simply a folder of pipeline jobs. For every branch you have, Jenkins will create a folder. So instead of creating a pipeline job for each of the branches you have in a git repository, you could use a multibranch job. This means that you’ll have to create only one job. You also need to define where the Jenkinsfile is, and it’s important that this file is at the same location in all the branches you create. Let’s create a job of this type to learn how to configure it.
# Cration of Multibranch Pipeline
Head over to your Jenkins instance and create a new item. Enter a name for the job, and select the “Multibranch Pipeline” option at the end of the screen. Then, click on the OK button.
In the next screen, go to the “Branch sources” tab, click on the “Add source” button, and choose “Git” from the dropdown menu. Then enter the repository URL. Because this is a public repository, we don’t need to configure any credentials.

We’ll use all the defaults for now. So, scroll down to the end of the screen and click on the “Save” button to finish creating the job. In the logs, you should see that Jenkins is cloning the repository and it creates the job successfully, even if it’s an empty repository.

