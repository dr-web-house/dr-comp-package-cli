# dr-comp-package-cli
The drcp command line interface.

This tool helps you to manange your workspace environment.

1. ### Start your development by installing this command line interface and drcp module.

	```
	npm install -g dr-comp-package-cli
	npm install --save dr-comp-package
	```
2. ### Show help information.
	```
	drcp -h
	```

2. ### Initialize a new environment
	```
	drcp init
	```
3. ### Link project repo folders to current workspace
	
	```
	drcp add <project-directory> [<project-directory> ...]
	```
