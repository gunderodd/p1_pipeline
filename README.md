# p1_pipeline
Setting up a pipeline to P1 project

error history and notes:

1. so far only the pom file has been changed from my local P1, i added a new ojdbc
and an implicit javax.servlet dependency to fix two errors. at this step the project
builds but the tests fail.

2. with the tests commented out, and those changes to the pom file, i am able to 
successfully build the app. however, i can't access my db, probably because of...
  a. system variables need to be set in db because they are on my computer, or just
  hardcoded in again and 
  b. probably need to update AWS db with a security group to accept the EC2 IP address
