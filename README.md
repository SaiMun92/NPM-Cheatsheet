# NPM-Cheatsheet

npm -v

npm init # create package.json & add -y is yes to all requirements

npm install # install all packages in package.json

npm install <package> # install in package but not written in package.json

npm install <package> --save-dev # install in modules only in develop dependencies

npm install <package>  --save # install in modules in dependencies

npm install <package>@<version> # install specific version of package

npm cache clean # clear npm cache

npm ls -g # list all modules installed globally

npm ls #  list all modules locally

npm list --depth 0 # list all npm modules with depth 0

npm show <package> # show versions, maintainers

npm outdated # show all outdated modules

npm prune #removes "extraneous" packages. Extraneous packages are packages that are not listed on the parent package's dependencies list.
