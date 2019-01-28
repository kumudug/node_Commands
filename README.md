# node_Commands

* Nodes REPL Mode
    * Single tab for auto complete
    * Double tab for available options
* `node -p "os.cpus().length"`
* `node -p "process.versions.v8"`
* To see all options
    * `node -h | more` or in linux `node -h | less`
* To see v8 options
    * `node --v8-options | more` 
    * To search this list
        * `node --v8-options | findstr "in progress"` or in linux `node --v8-options | grep "in progress"`
* Setting a module to debug
    * `NODE_DEBUG="http" node app.js` [Didn't work on windows]
* 