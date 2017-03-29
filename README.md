# dr-comp-package-cli
The drcp command line interface.

This tool helps you to initialize your project environment, and also helps to upgrade project environment for a newly updated drcp version.

1. ### Start your development by installing this command line interface and drcp module.

	```
	npm install -g dr-comp-package-cli

	npm install --save-dev drcp
	```
2. ### Show help information.
	```
	drcp -h
	```

2. ### Initialize a new environment
	This will copy some files to your project directory, but first of all, make sure you have your very `package.json` in it.

	```
	drcp init
	```
3. ### Upgrade to a new version of drcp
	
	```
	npm install drcp@<new version>
	drcp update
	```
