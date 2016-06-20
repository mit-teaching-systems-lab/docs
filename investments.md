# Technical investments

## Overview
###### What is this?
Projects in the Teaching Systems Lab often have a technical component, even in the prototyping phase.  This is where we keep track of technical investments made across different projects.

###### Why do we have this?
This can help us be aware of investments we're making across different projects, and see if there are opportunities for collaboration or focus.  If you're starting a new project, you can look here to see if someone else has done something similar or has expertise that might help you out.

## Investments
##### Source control
- [mit-teaching-systems-lab](https://github.com/mit-teaching-systems-lab) is the GitHub organization for all lab projects.

##### Working agreement
- A [working agreement](./working-agreement.md) is used as a starting point for how teams work together.

##### User interface tools
- [React](https://facebook.github.io/react/) for building web user interfaces.
- [Material UI](http://www.material-ui.com/#/) as a component library for React in the style of [Material design](https://material.google.com/).
- [Styling React components in JavaScript](https://speakerdeck.com/vjeux/react-css-in-js) for rationale on styling for React components in JavaScript.


##### JavaScript tooling
- [ES6](https://babeljs.io/docs/learn-es2015/) using [Stage 2 presets](https://babeljs.io/docs/plugins/preset-stage-2/)
- [Flow](https://flowtype.org/), for type-checking JavaScript
- [eslint](http://eslint.org/), to lint for errors, using [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) and [babel-eslint](https://github.com/babel/babel-eslint)
- [Browserify](http://browserify.org/) for building JavaScript
- [Babelify](https://github.com/babel/babelify) for compiling ES6 and JSX as a Browserify transform
- [livereactload](https://github.com/milankinen/livereactload) for live reloading React code built with Browserify

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
