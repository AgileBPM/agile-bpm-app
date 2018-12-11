# AgileBPM 移动端

> 与pc端无缝协同处理办公任务。pc端项目地址：https://gitee.com/agile-bpm/agile-bpm-basic

> pc、移动 协同，而且配置生成表单，支持在线修改，还不会失去表单js、html 扩展的灵活性。

它是一个比较完整的流程审批的移动端项目，如果您是第一次开发基于VUE的App，它是一个很好的基础项目模板。如果您正在开发协同办公类APP，那么它可以完全拿来使用

## 含基本的表单组件
- checkbox逗号分隔类型的实现
- 自定义对话框组件
- 登录失效弹框登录组件
- 数据字典组件
- 列表数据，下拉刷新，搜索，无线加载的组件
- 各种流程相关组件 eg:流程图，审批意见，审批处理等组件
- 组件运用很多vue高级用法，也可以让您得到借鉴：如动态组件、指令、指令与组件交互、组件间交互 等等

**欢迎star**

还可以参考到 **路由，跨域请求，axios封装，表单校验，表单权限处理 等技术**，可以让您减少学习成本 vue，尽快掌握vue 

#### 测试地址
![移动端测试地址](https://images.gitee.com/uploads/images/2018/0719/100556_de9bc8a4_1861740.png "屏幕截图.png")
账号密码 admin 1

[PC在线测试地址](http://test.agilebpm.cn/login.html)

[功能缺陷提测](http://zentao.agilebpm.cn账号test密码test123456)

[AgileBPM 实施文档]( http://doc.agilebpm.cn/ ) 

## 项目依赖
devDependencies 请参考package.json

"dependencies": {
    "axios": "^0.18.0",
    "fastclick": "^1.0.6",
    "vue": "^2.5.2",
    "vue-router": "^3.0.1",
    "vuex": "^2.1.1",
    "vuex-i18n": "^1.3.1",
    "vux": "^2.2.0"
  }

## 后端主工程项目地址
https://gitee.com/agile-bpm/agile-bpm-basic


## 工作流解决方案

**我们通过业务对象、表单、流程引擎共同协作来解决业务流难实施的痛点**
业务对象用来承载、持久化业务数据；表单则是业务数据的展示层；流程则用来驱动业务数据流转。三者协作完成流程实施。

## 安装步骤

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run e2e tests
npm run e2e

# run all tests
npm test

后端项目请求地址的配置 在 baseService.js  __ctx

```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## 

## 预览
  
<img src="https://images.gitee.com/uploads/images/2018/0719/123901_63529832_1861740.png" width="33%" hegiht="300" align=left /> 
<img src="https://images.gitee.com/uploads/images/2018/0719/123910_7bb9c708_1861740.png" width="33%" hegiht="300" align=left /> 
<img src="https://images.gitee.com/uploads/images/2018/0719/123917_3f24aedd_1861740.png" width="33%" hegiht="300" align=left /> 


## 致谢
感谢VUE，VUX等开源软件对社会做出的贡献!


