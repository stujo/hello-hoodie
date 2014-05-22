hello-hoodie
============

A Hoodie Example Application - Hello World Tutorial


#Install Hoodie and Pre-Requisites

Following: [http://hood.ie/#installation](http://hood.ie/#installation)

  brew update
  brew install git
  brew install node
  brew install couchdb

That all took 5 minutes or so!

  npm install -g hoodie-cli

  npm install -g local-tld

#Creating a New Hoodie App

```

$ hoodie new hello-hoodie

.d$b.  .d$b.  .d$$$$$$b.    .d$$$$$$b.  .d$$$$$$b.  .d$b..d$$$$$$$$b.
$$$$$..$$$$$.$$$$$$$$$$$b .$$$$$$$$$$$b $$$$$$$$$$b $$$$$$$$$$$$$$$P'
$$$$$$$$$$$$d$$$$$$$$$$$$bd$$$$$$$$$$$$b$$$$$$$$$$$b$$$$$$$$$$$$$$$b.
$$$$$$$$$$$$Q$$$$$$$$$$$$PQ$$$$$$$$$$$$P$$$$$$$$$$$P$$$$$$$$$$$$$$$P'
$$$$$´`$$$$$'$$$$$$$$$$$$''$$$$$$$$$$$$'$$$$$$$$$$P $$$$$$$$$$$$$$$b.
'Q$P'  'Q$P'  'Q$$$$$$P'    'Q$$$$$$P'  'Q$$$$$$$P  'Q$P''Q$$$$$$$$P'

Version: 0.4.10 (node v0.10.21, npm 1.3.11, platform: darwin)

[hoodie] Updated package.json
[hoodie] fetching npm dependencies
[hoodie] removing .git folder
[hoodie] Error installing dependencies:

Something's wrong here...

Try running the following commands to resolve possible issues:

  hoodie cache clean

  npm cache clean

If none of the above works, run "hoodie new hello-hoodie --verbose"
and come talk to us on freenode #hoodie 

$ hoodie cache clean
[hoodie] cleaning cache...
[hoodie] done
$ npm cache clean
```

Trying again:

```

$ hoodie new hello-hoodie

.d$b.  .d$b.  .d$$$$$$b.    .d$$$$$$b.  .d$$$$$$b.  .d$b..d$$$$$$$$b.
$$$$$..$$$$$.$$$$$$$$$$$b .$$$$$$$$$$$b $$$$$$$$$$b $$$$$$$$$$$$$$$P'
$$$$$$$$$$$$d$$$$$$$$$$$$bd$$$$$$$$$$$$b$$$$$$$$$$$b$$$$$$$$$$$$$$$b.
$$$$$$$$$$$$Q$$$$$$$$$$$$PQ$$$$$$$$$$$$P$$$$$$$$$$$P$$$$$$$$$$$$$$$P'
$$$$$´`$$$$$'$$$$$$$$$$$$''$$$$$$$$$$$$'$$$$$$$$$$P $$$$$$$$$$$$$$$b.
'Q$P'  'Q$P'  'Q$$$$$$P'    'Q$$$$$$P'  'Q$$$$$$$P  'Q$P''Q$$$$$$$$P'

Version: 0.4.10 (node v0.10.21, npm 1.3.11, platform: darwin)

[hoodie] Updated package.json
[hoodie] fetching npm dependencies
[hoodie] removing .git folder
[hoodie] preparing hello-hoodie ...
[hoodie] created project at /work/projects/hoodie/hello-hoodie/
[hoodie] Installed all dependencies

You can now start using your hoodie app

  cd hello-hoodie
  hoodie start

```

Success!

  $ cd hoodie-hello
  $ hoodie start

And the app starts and a browser opens pointing to ```http://127.0.0.1:6001/```

