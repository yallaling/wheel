Connecting to the postgres service instance of the predix
----------------------------------------------------------
go to the directory
open manifest.yml in gedit


	---
	applications:
	- name: <phppgadmin_app_name> ef: abc
	  memory: 256M 
	  instances: 1
	  path: .
	  buildpack: php_buildpack
	  port: 80
	  services:
	  - <postgres_service_name>
	  
	  
cf push

cf a

get the link
go to chrome
put https://<link>

cf env <phppgadmin_app_name> 

get database, username, password - keep it in notes


-----------------------------------------------

postgres url: https://phppgadmin-pgdb.run.aws-usw02-pr.ice.predix.io

userName: u62a0a638a38a4867a85f455fa664f23a

Password: 943e27ded2f24f65a5306f1eced2dae3

DatabaseName: d856c51b447cf4ff1a483798f519ab8b0