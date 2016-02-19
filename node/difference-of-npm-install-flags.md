#Difference-of-npm-install-flags

Install flags are helpful for building your package.json file, so that at a
glance you can tell what node modules you have installed and which your
project relies on. Furthermore, it allows other developers to simply run
`npm install` to install all of the necessary node modules via one command.

Types of install flags:

`-g` stands for global and should be used if you are going to be using
the npm package in the command line and is not a direct dependency of your
project

`--save` installs the packages as a dependency for your project and should be
used if the package is needed for your project to run

`--save-dev` installs the package as a developer dependency and should be used
for packages that you will used when developing your project, such as testing
frameworks, loaders, debuggers etc.  

> 2.18.16
