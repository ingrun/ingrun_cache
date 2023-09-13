# @ingrun/cache

## config
```js
import create from '@ingrun/cache'
import Vue from 'vue'

export default create(Vue)
```

## use
```js
import cache from 'utils/cache'
cache.set('username', 'zhangsan')

console.log(cache.get('username')) 
// zhangsan
```