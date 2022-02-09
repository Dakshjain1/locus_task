# Locus Task

The following links contain the code files:

Sample backend application code
https://github.com/Dakshjain1/locus_task

Jenkinsfile repository
https://github.com/Dakshjain1/locus_task_jenkinsfile

Some Key Points:

1. I have setup Jenkins Server on an AWS Instance.
2. Backend Application is a JAVA Code that is being compiled using Maven tool.
3. Jenkinsfile is present in another repository. When this code is updated in Jenkins GitHub repository, the pipeline code gets updated in Jenkins.
4. This job is hooked to the backend source code repository and is triggered on every commit push in the branch.

Features of CI Pipeline:
1. Clones the repo and keeps check on every commit.
2. Runs Unit Testing and prepared JUnit graph on Jenkins Dashboard
3. Builds archive of JAR.
4. Sends email to developer for success or failure of Job
