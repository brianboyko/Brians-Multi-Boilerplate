# Brian's Multi-Boilerplate
=====================

A minimized dev environment to enable live-editing using different technologies.

Keep in mind, the "master" branch contains only this README.  To get access to
a particular boilerplate, you must select the branch you want.

## Branches:

* boilerplate-react
  * Based off of [Gaearon's React Hot Boilerplate](https://github.com/gaearon/react-hot-boilerplate)
  *  Contains Webpack, React.
* boilerplate-react-redux
  * Contains the above boilerplate-react
  * Adds a very basic redux implimentation with one "counter" reducer
  * Uses react-logger
  * Has support for redux-thunk and redux-multi, but the base app does not use these tools.

### Usage

```
npm install
npm start
open http://localhost:3000
```
