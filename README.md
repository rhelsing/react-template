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

* Attempt: auth, chat (socket action cable), file upload, communicate with api/graphql (Rails) (http://graphql.org/learn/)
* RallyCoding, Avdanced, GraphQL
* CSS Sort out
* https://medium.com/@DrawandCode/building-a-graphql-api-in-rails-part-1-a40aaf7e165f
* SSL Deploy
* https://facebook.github.io/react/docs/installation.html
* ServerSide Rendering
* https://reactjsnews.com/how-to-make-your-react-apps-10x-faster
* ReduxThunk
* Basic Animation
* https://medium.com/@joethedave/achieving-ui-animations-with-react-the-right-way-562fa8a91935
* http://www.infoworld.com/article/2608181/javascript/react--making-faster--smoother-uis-for-data-driven-web-apps.html
* https://js.coach/?sort=popular
* https://github.com/Semantic-Org/Semantic-UI-React
* css grid/flexbox
* http://jxnblk.com/rebass/getting-started
* websockets, socket.io, actioncable
* https://medium.com/lexical-labs-engineering/redux-best-practices-64d59775802e
* https://github.com/wclittle/Rails5-ActionCable-Redux-React-ChatAppExample
* https://gridbyexample.com
* https://shoelace.style
* https://rachelandrew.co.uk/archives/2017/07/01/you-do-not-need-a-css-grid-based-grid-system/
* https://auth0.com/blog/secure-your-react-and-redux-app-with-jwt-authentication/
* https://sourcey.com/building-the-prefect-rails-5-api-only-app/
* https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one
* https://github.com/vasilakisfil/rails5_api_tutorial
* https://killring.org/2014/11/18/api-design-reading-list/
* https://www.quora.com/What-are-the-best-resources-articles-books-examples-on-designing-APIs-What-are-some-characteristics-of-a-beautiful-API
* https://gist.github.com/max-mykhailenko/41d0c3991d92f38dcbc6
* http://wesbos.com/emmet-react-jsx-sublime/
* https://flow.org/en/docs/getting-started/
* http://blog.littleblimp.com/post/119230396893/direct-uploads-to-s3-with-react-rails-and
* https://www.monterail.com/blog/2017/react-fiber-release
* https://www.howtographql.com
* https://github.com/blog/2412-learn-graphql-with-github
* https://www.youtube.com/watch?v=UBGzsb2UkeY

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
