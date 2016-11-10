# Universal JavaScript
* SPA into UniversalJS
* Server Side Rendering at first time
* will do ajax after first request

# How to do UniversalJS
## 1. Router (server side)
` <RouterContext { ...renderProps} />`
## 2. Handle Ajax issues
Server render 必須等到 ajax 回傳才能 render
* 靜態屬性
 - async-props
 - redux-async-connect
 - React-enter

## 3. Handle Static Files
* webpack bundle server code
 - webpack-node-externals
 
## 4. Bundle node

## 5. Env variable
webpack:
server: false
SPA: true

## 好處？
* 更好的元件封裝
* Critical Render Path (分數網站)
  - isomorphic style loader
 
 
# Reference
* [async-props](https://github.com/ryanflorence/async-props)
* [css optimizing](https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery)
