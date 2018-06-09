# plcmdlink
To attach any command line Link

link:
https://medium.com/netscape/a-guide-to-create-a-nodejs-command-line-package-c2166ad0452e

steps:
create a folder called bin , inside folder add a sample script file (ex:cmdlink.js) 

Now in package.json add following json:
 "bin": {
    "mylink": "./bin/cmdlink.js"
  },

now run : npm link

if there is some issue to unlink and link again:
> npm unlink
then do some changes in package.json

>npm link
