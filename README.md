universalviewer-toolforge
=========================

A simple deployment of [UniversalViewer](https://github.com/UniversalViewer/universalviewer) for the Wikimedia Toolforge.

Mostly dumbed-down from [uv-app-starter](https://github.com/UniversalViewer/uv-app-starter/)

Deployment
----------

The Ansible playbook will only take you so far. Per [Wikitech](https://wikitech.wikimedia.org/wiki/Help:Toolforge/Web#Running_npm_with_webservice_shell), to deploy the NPM dependencies:

```
webservice --backend=kubernetes nodejs shell
cd $HOME/src
npm install
```
