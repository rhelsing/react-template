#Ryan's React Template

* create-react-app Base
* Redux + Other Dependencies
* Organized src/
  * components
  * containers
  * actions
  * reducers
  * services (for live reloading)
  * index.js
* s3-website for quick initial deploy (See below)


run locally:
```
yarn install && yarn start
```
TODO:

* Yet to install:

    "react-redux": "4.3.0",
    "react-router": "^2.0.1",
    "react-router-dom": "^4.0.0",
    "redux": "^3.0.4",
    "redux-form": "^6.6.3",
    "redux-promise": "^0.5.3"
    "axios": "^0.16.2",
    "lodash": "^3.10.1",

* CSS Sort out
* Security, auth, communicate with api/graphql
* SSL Deploy
* ServerSide Rendering

#To Deploy:
Create:
```
s3-website create [name-of-site]
```
Update:
```
yarn build
s3-website deploy build
```
