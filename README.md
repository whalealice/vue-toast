# vue-toast

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

import Toast from 'vue-toast-b'

Vue.use(Toast)

this.$toast.show("hello, toast")

this.$toast.show("hello, toast", {
    duration: 3000
}) 

this.$toast.show("hello, toast", funcion() {

})