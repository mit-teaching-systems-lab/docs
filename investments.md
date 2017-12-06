# Technical investments

## Overview
###### What is this?
Projects in the Teaching Systems Lab often have a technical component, even in the prototyping phase.  This is where we keep track of technical investments made across different projects.

###### Why do we have this?
This can help us be aware of investments we're making across different projects, and see if there are opportunities for collaboration or focus.  If you're starting a new project, you can look here to see if someone else has done something similar or has expertise that might help you out.

## Investments
##### Source control
- [mit-teaching-systems-lab](https://github.com/mit-teaching-systems-lab) is the GitHub organization for all lab projects.

##### Editors
- [Sublime](https://www.sublimetext.com/) with [Package Control](https://packagecontrol.io/)
- [babel-sublime](https://github.com/babel/babel-sublime)
- [SublimeLinter](http://www.sublimelinter.com/en/latest/) with [SublimeLinter-eslint](https://github.com/roadhump/SublimeLinter-eslint)

##### Working agreement
- A [working agreement](./working-agreement.md) is used as a starting point for how teams work together.

##### Design tools
- [LICEcap](https://www.cockos.com/licecap/) for animated GIFs showing product features

##### User interface tools
- [React](https://facebook.github.io/react/) for building web user interfaces.  See also our [Learning React](learning-react.md) doc.
- [Material UI](http://www.material-ui.com/#/) as a component library for React in the style of [Material design](https://material.google.com/).
- [Velocity React](https://github.com/twitter-fabric/velocity-react) for declaratively animating React components.
- [Styling React components in JavaScript](https://speakerdeck.com/vjeux/react-css-in-js) for rationale on styling for React components in JavaScript.
- [react-virtualized](https://github.com/bvaughn/react-virtualized) for rendering large tables of data

##### JavaScript tooling
- [yarn](https://yarnpkg.com/en/) for managing JS dependencies
- [ES6](https://babeljs.io/docs/learn-es2015/) using [Stage 2 presets](https://babeljs.io/docs/plugins/preset-stage-2/)
- [create-react-app](https://github.com/facebookincubator/create-react-app)
- [eslint](http://eslint.org/), to lint for errors, using [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) and [babel-eslint](https://github.com/babel/babel-eslint)
- [n](https://github.com/tj/n) for managing node.js versions
- [Flow](https://flowtype.org/), for type-checking JavaScript
- [Browserify](http://browserify.org/) for building JavaScript (deprecated, use create-react-app)
- [Babelify](https://github.com/babel/babelify) for compiling ES6 and JSX as a Browserify transform (deprecated, use create-react-app)
- [livereactload](https://github.com/milankinen/livereactload) for live reloading React code built with Browserify (deprecated, use create-react-app)

##### JavaScript testing
- [Jest](https://facebook.github.io/jest/)
- [Sinon](http://sinonjs.org/) for creating spies, mocks and stubs.
- [Enzyme](https://github.com/airbnb/enzyme) using [jsdom](https://github.com/airbnb/enzyme/blob/master/docs/guides/jsdom.md)
- [Mocha](https://mochajs.org/) with jsdom, using [Chai's](http://chaijs.com/) expect assertions (deprecated, use Jest)

##### Android development
- [Cordova](https://cordova.apache.org/)
- [Android Studio](https://developer.android.com/studio/index.html)
- [Gradle](https://gradle.org/)

##### Storage systems
- [PostgreSQL on Heroku](https://devcenter.heroku.com/articles/heroku-postgresql) for storing relational data or as a hybrid JSON document store.
- [Amazon S3](https://aws.amazon.com/s3/)

##### Web server
- [Rails](http://guides.rubyonrails.org/) for web services
- [express](http://expressjs.com/) for small node.js services

##### Continuous integration
- [Travis CI](https://travis-ci.org/)

##### Deployment
- [Heroku](https://www.heroku.com/)
- [Amazon S3](http://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)

##### Error reporting
- [Rollbar](https://rollbar.com/)

##### Sending email
- [Mailgun](https://mailgun.com/)

##### Data analysis and visualization
- [Jupyter](http://jupyter.org/) and [related stacks](https://github.com/jupyter/docker-stacks) like [jupyter/datascience-notebook](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook)

##### Local development
- [Docker for Mac](https://docs.docker.com/docker-for-mac/)
