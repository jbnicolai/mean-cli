MEANP-CLI
================

A simple command line tool for creating front-end modules on the meanp-seed project. Proud to be part of Making Sense.

Screen casts highlithing the main two use cases

<a href="http://screencast.com/t/fMgu8TjOh" >yo meanp</a>

<a href="http://screencast.com/t/k1Dmfzx1R" >yo meanp:modules</a>
 
 <a href="http://screencast.com/t/nBOxhCwejOh" >yo meanp:todo</a>
 
 <a href="http://screencast.com/t/kK9n6I85EW" >yo meanp:blog</a>
 
### Setup:
```
npm install -g generator-meanp
```

### Commands:
```yo meanp <name>```
Clones the meanp-seed project to a new directory with the name you enter.

```yo meanp:modules <name>```
Creates a new module on the current application //TODO: Ensure that we are located at the project

```yo meanp:todo <name>```
Creates a new todo module on the current application, this generates a todo-list module.

```yo meanp:blog <name>```
Creates a new blog on the current application, this will generate a client-side blog module.
