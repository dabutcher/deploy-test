deploy-test
===========

Simple repo to test Jenkins jobs

Steps
-----
1) Setup jenkins job pull SCM (git) for changes set timing to @daily @hourly or what you need  
2) Add Execute shell to run ./push-to-prod.sh user@production.hostname:/path_to_copy_files  

Found out that line break can be applied with two or more spaces at end of line  
I added that to my Steps list to see if the are now on different lines.  

Added a prod branch to test only pushing changes to production host when prod branch is updated.  
