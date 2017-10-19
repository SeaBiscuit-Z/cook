# 说明
[后端代码在这](https://github.com/SeaBiscuit-Z/cookServer "asp.net webapi") , 这是 [上线地址](http://47.94.224.249/)

# 技术栈:

### 前端
vue2.0全家桶 + stylus + webpack + [jsonServer](https://github.com/typicode/json-server) + [vueLazyload](https://github.com/hilongjw/vue-lazyload) 

### 后端
三层 + asp.net mvc WebApi + cors + sqlServer

# 项目运行

```Javascript
//main.js 里

//axios.defaults.baseURL = 'http://localhost:1528';   //取消此行代码的注释，将后面的路径改为后端后运行的路径
axios.defaults.baseURL = 'http://47.94.224.249:666';  //这是我线上的地址，把此行代码注释
```

