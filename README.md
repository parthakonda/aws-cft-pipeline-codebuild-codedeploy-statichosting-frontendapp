# aws-cft-pipeline-codebuild-codedeploy-statichosting-frontendapp
Template for hosting a Vue app into s3 using cloudformation, codebuild, codedeploy and codepipeline.

Note:
1. Get Access Token
This pipeline will take the source code from the github. So you need get a developer access token (make sure it is having read access).

2. Place your code in Github
Make sure your vue code is placed in a github repo. And you need to have a username/orgname and reponame as input parameters to your cft.

# Setup
Use the frontend-pipeline-cft.yml and give as an input in the cloudformation. Provide appropriate values.