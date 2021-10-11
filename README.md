# Code Forensics wrapper

This project wraps [Code Forensics](https://github.com/smontanari/code-forensics)
in an easy to setup and use manner.

This is pre-configured to optimize for analyzing Python or Javascript code bases.


# Setup

1. Install [requirements](https://github.com/smontanari/code-forensics#pre-requisites), namely
  - `node`
  - `npm`
  - `java` (JRE)
2. `npm install yarn` (if you've got no `yarn`)
3. `yarn install`


# How To Use

1. Copy `./gulpfile.js.sample` to `./gulpfile.js`
1. Edit `./gulpfile.js`, adjust `rootPath` to the correct path.
2. `yarn run gulp <tasks> --dateFrom=2016-01-01`, refer [here](https://github.com/smontanari/code-forensics/wiki) for `<tasks>`.
3. `yarn run gulp webserver`; open http://localhost:3000

Come [here](https://github.com/smontanari/code-forensics) more instructions.
