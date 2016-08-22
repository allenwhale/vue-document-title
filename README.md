# vue-document-title

> Vue.js version of [react-document-title](https://github.com/gaearon/react-document-title)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## Usage

```vue
<template>
<document-title :title="caption">...sub...</document-title>
</template>

<script>
import DocumentTitle from 'vue-document-title'

const data = {caption: 'first title'}
export default {
  data: function () {
    return data
  }
}

setTimeout(function () {
  data.caption = 'next title'
}, 2000)
</script>
```





## TODO

- [ ] test
- [ ] flowtype
