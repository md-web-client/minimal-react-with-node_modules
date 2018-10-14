Minimal React
=============
This is a template for building React.js web apps **without browserify, babel, and JSX**.

## Installation
```bash
git clone https://github.com/MichaelDimmitt/minimal-react-with-node_modules.git
npm install
open index.html
```

## Why is this project so minimal?
More for understanding how everything works behind the scenes.

Coding is hard without babel:</br>
Correct this project is more about understanding that babel is transpiling your code into: [yikes!](https://github.com/MichaelDimmitt/express_serving_minimal_react/blob/with-express/js/helloWorldComponents.js)


## Why "with-node_modules"
HTML link's to the browser compatable javascript in the node_modules folder.
<br/>Previously it would have linked to a cdn. check out [minimal-react](https://github.com/shinglyu/minimal-react)
<br/>However, that cdn can go down. 
<br/>Additionally it gives the latest stable.
<br/>Using node-modules allows an easier way to quickly try out different releases.
<br/>It also enables a specific version to be defined and never changed.

Note: I have added the package-lock.json to the .gitignore.
<br/>Your project should probably keep this file.
<br/>However, it would be best implemented in a package-lock.json included branch.
<br/>So as not to clutter the git history.

## View next Project/Progression
For a strategy regarding returning only what a user with specific roles will ever view.
<br/>Make sure to check out [express_serving_minimal_react](https://github.com/MichaelDimmitt/express_serving_minimal_react), [specifically: server.js](https://github.com/MichaelDimmitt/express_serving_minimal_react/blob/master/server.js)
<br/>Where only one html file will be sent to a user. but it will be the one for their security role.

