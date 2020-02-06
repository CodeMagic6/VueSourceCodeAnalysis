#### core项目结构：
* components 组件的一些功能实现，例如keep-alive
* global-api 全局的一些api功能实现
* instance 实例的实现
* obeserver 观察者的实现
* vdom 虚拟dom的实现

> 首先打开index.js文件，导入`import Vue from './instance/index'`Vue实例对象，initGlobalAPI(Vue)初始化Vue的全局api