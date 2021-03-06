# vcustomers

> Vue2.0-Vue.js用户管理系统

## :book: 技术栈

【前端】
- **Bootstrap**：构建用户界面
- **Vue**：构建用户界面的 MVVM 框架，核心是响应的数据绑定和组系统件
- **vue-router**：为单页面应用提供的路由系统，项目上线前使用了路由懒加载技术，来异步加载路由优化性能
- **vue-resource**：服务端通讯，项目后期改用 `axios`
- **axios**：服务端通讯。基于 `Promise` 的网络请求插件
- **ES6**：ECMAScript 新一代语法，模块化、解构赋值、Promise、Class 等方法非常好用

【后端及数据库】

- **JSONSERVER**：利用 本地JSONSERVER 储存数据 http://localhost:3000/users 
- **JSONSERVER**：JSONSERVER文件单独提取出来 命令行开启服务 npm run json:servar

【自动化构建及其他工具】

- **vue-cli**：Vue 脚手架工具，快速初始化项目代码

## :pencil: 实现细节

主要功能：主页、关于我们、用户添加、详情、用户修改、删除

![首页](https://github.com/MsJun/vcustomers/blob/master/src/assets/1.png)
![添加用户](https://github.com/MsJun/vcustomers/blob/master/src/assets/2.png)

## :closed_book: 收获

1. 对 vue 的组件、指令、选项、模版渲染、事件绑定、计算属性等有了一定了解
2. 了解了 vue 组件之间的交互、传值
3. 熟悉了在 vue 项目中使用第三方插件（组件）
4. 熟悉了组件化、模块化的开发思维
5. 熟悉了 vue-router 控制路由和子路由的方式
6. 再次熟悉项目开发流程：项目分析设计 -> 项目环境搭建 -> 依赖安装 -> 页面架构设计 -> 组件开发 -> 测试联调 -> 发布上线
7. 体会到组件化、模块化开发带来的便捷


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
