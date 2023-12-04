# manager

## 启动前准备

启动前复制.env文件,命名为.env.local,根据后端提供的接口地址自行修改`VUE_APP_BASE_URL`参数,该参数为后端接口统一前缀,项目中如需用到,使用`process.env.VUE_APP_BASE_URL`

参考文档 :  
https://cli.vuejs.org/zh/guide/mode-and-env.html#%E6%A8%A1%E5%BC%8F

## 启动命令
```
npm run local
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
 
