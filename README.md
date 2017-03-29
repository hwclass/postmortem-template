# postmortem-template

Notes for the future challenges.

This file is representing a default template for posmortem reports to be used as guides for problem-solving steps for now and the future. Editor may choose every guide style about what it is being expected to be noted.

### Title

ex. Resolve how to update Webpack to version 2 with tree-shaking and other new, stunning features

### Date

ex. 27.12.2016

### Authors

ex. John Doe, Black Magic Woman, Doctor Who

### Impact

ex. With this new update, we have added the tree-shaking feature for removing redundant codes from our bundled source as Javascript.

### Resolution
ex.
* **Step 1:** Get the latest webpack 2 (now ) by the package manager: npm i webpack@2.1.0-beta.25 & npm i webpack-dev-server@2.1.0-beta.10
* **Step 2:** Create a webpack config file with necessarry parameters.
* **Step 3:** Run or define it as an npm script : webpack -p
