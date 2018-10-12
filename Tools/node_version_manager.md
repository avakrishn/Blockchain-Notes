# Node Version Manager (nvm)
*  Node version manager allows you to use different versions of node for different projects

##Resource: 
* https://github.com/creationix/nvm (For Mac)

## Install/ Update nvm
* install script using cURL:
	- curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
* verify installation
	* command -v nvm

## nvm Commands:
1. To download, compile, and install the latest release of node, do this:
	* `nvm install node `
	- # "node" is an alias for the latest version

2. To install a specific version of node:
	* `nvm install 6.14.4` 
	- # or 10.10.0, 8.9.1, etc

3. You can list available versions using ls-remote:
	* `nvm ls-remote`

4. And then in any new shell just use the installed version:
	* `nvm use node`

5. Or you can just run it:
	* `nvm run node --version`

6. Or, you can run any arbitrary command in a subshell with the desired version of node:
	* `nvm exec 4.2 node --version`

7. You can also get the path to the executable to where it was installed:
	* `nvm which 5.0`