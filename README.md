# A Typescript library boilerplate for nodejs
Very minimal boilerplate with only the Typescript as dependency.
This is for those who wants to install private repositories from github / bitbucket instead of npm and want to use Typescript.

:warning: This is so simple you won't even need this.  

## Instructions


### Using the repo
- clone the repo 
- Remove .git folder and do git init if  you wanted to
- Modify the package.json to reflect your project
- Put your source files inside the src folder
- use the build script to build your library
- lib is the default output directory
- update the tsconfig.json for your needs
- If you update the output dir in tsconfig then you need to change the main file in package.json to reflect the same

### Preparing for private impor
- update the version no in package.json
- build the src "npm run build"
- commit the lib folder
- Depending upon your need, you may need to set the git tag. I prefer keeping the version in package.json and git tag same.

### Importing library as a private repo into you project
- npm install git+(your https url) to install the library this will copy the contents of lib folder to the .node_modules/project_name/lib/ directory.  Your source files will not be copied.  

TODO

- [ ] Command line interface like create-react-app


