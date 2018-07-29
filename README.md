## Just a simple PWA test ##
https://www.telerik.com/blogs/building-pwas-with-vuejs

https://www.telerik.com/blogs/a-gentle-and-practical-introduction-to-progressive-web-apps

yarn global add @vue/cli    // latest cli

- cd ..
- vue create
- (saved template as pwa-rout-vuex)
- cd xxx
- yarn run serve
- yarn run build
- yarn run serve -s dist

scutil --get ComputerName   // to get host name

for remote client on iMac server need vue.config.js
```
module.exports = {
  devServer: {
    disableHostCheck: true
  }
}
```