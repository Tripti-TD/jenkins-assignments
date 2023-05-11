# jenkins-assignments
this is intelipaat jenkins-assignments

Assignment-1:
I have Trigered a pipeline using Git when push on Develop Branch which pulled Git content to a folder "jenkins/workplace/DEvelop_push"

Assignment-2:
Added to nodes in Jenkins Master and created two jobs-- 
      1. push_to_test which copy files to Test-server when push is made to test branch
      2. push_to_prod which copy files to prod-server when push is made to master branch
      
      
 Assignment3:
 created a pipeline which do the following tasks-
 1. triggered job "test" when push is made to develop branch, this will copy files to test-server
 2. if "test" job is successful then "prod" job triggered which copies the file to prod-server
 
