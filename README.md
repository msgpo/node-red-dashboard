# node-red-dashboard

This module provides a set of nodes in Node-RED to quickly create a live data
dashboard.

It is a continuation of the work done by Andrei Tatar under the node-red-contrib-ui module.


## Install

```
cd ~\.node-red
npm install node-red-dashboard
```

Open your Node-RED instance and you should have UI nodes available at the bottom.
The UI interface is available at <http://localhost:1880/ui> (if default Node-RED settings are used).

## Migration from node-red-contrib-ui

These nodes will replace the contrib-ui versions. node-red-contrib-ui
should be uninstalled before installing node-red-dashboard.

 ```
 cd ~\.node-red
 npm uninstall node-red-contrib-ui
 ```
 In addition - some functionality is not exactly equivalent...

### New features

 (( Lots more details to be added here ))

### Changed

 (( Lots more details to be added here ))

## Discussions and suggestions

There is a google group: <https://groups.google.com/forum/#!forum/node-red>

## Contributing

Before raising a pull-request, please read our
[contributing guide](https://github.com/node-red/node-red-dashboard/blob/master/CONTRIBUTING.md).

This project adheres to the [Contributor Covenant 1.4](http://contributor-covenant.org/version/1/4/).
 By participating, you are expected to uphold this code. Please report unacceptable
 behaviour to any of the [project's core team](https://github.com/orgs/node-red/teams/core).

## Developers

```
cd ~\.node-red\node-modules
git clone https://github.com/node-red/node-red-dashboard.git
cd node-red-dashboard
npm install
```
The plugin uses the ```dist``` folder if it exists and contains an ```index.html``` file. Make sure to delete it if you want to use the non-minified version.
After changing the front-end code in the src folder, ```gulp build``` will update the minified files.
