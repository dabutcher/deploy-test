deploy-test
===========

Simple repo to test Jenkins jobs

Steps
-----
1) Setup jenkins job pull SCM (git) for changes set timing to @daily @hourly or what you need
2) Add Execute shell to run ./push-to-prod.sh user@production.hostname:/path_to_copy_files
