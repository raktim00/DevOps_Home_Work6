# The Full procedure of doing this practical you can find in below link :

## “DevOps - The Real Need (Jenkins Scripting Automation)” by Raktim Midya - https://link.medium.com/qC3Twvm7bab

### Problem Statement :

##### Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins.
- 1. Seed Job : Pull the GitHub repo automatically when some developers push repo to GitHub which contains Groovy Script.
- 2. Further on jobs should be pipeline using written code using Groovy language by the developer.
- 3. Job1 : Fetches the code from GitHub and store on the Workspace.
- 4. Job2 :
By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed ).
Expose your pod so that testing team could perform the testing on the pod.
Make the data to remain persistent using PVC ( If server collects some data like logs, other user information )
- 5. Job3 : Test your app if it is working or not.
- 6. Job4 : If app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer.
