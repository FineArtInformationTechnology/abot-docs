# Abot 简介

## 技术栈

+ 后端web框架：[Meteor](https://www.meteor.com/)
+ 前端框架：[Element](https://element.eleme.cn/#/zh-CN) + [VueJS](https://cn.vuejs.org/)
+ 数据库：[Mongodb](https://www.mongodb.com/)

## 代码结构
<pre>
├── build                          // 构建相关  
├── server
├── client
│   ├── config                     // 配置相关
│   ├── src                        // 源代码
│   │   ├── api                    // 所有请求
│   │   ├── assets                 // 主题 字体等静态资源
│   │   ├── components             // 全局公用组件
│   │   ├── filtres                // 全局 filter
│   │   ├── icons                  // 项目所有 svg icons
│   │   ├── lang                   // 国际化 language
│   │   ├── mock                   // 项目mock 模拟数据
│   │   ├── router                 // 路由
│   │   ├── store                  // 全局 store管理
│   │   ├── styles                 // 全局样式
│   │   ├── utils                  // 全局公用方法
│   │   ├── views                  // 视图
│   │   ├── App.vue                // 入口页面
│   │   ├── main.js                // 入口 加载组件 初始化等
│   │   └── permission.js          // 权限管理
│   ├── static                     // 第三方不打包资源
│       └── 
├── tests
├── .gitignore                      // git 忽略项
└── package.json                    // package.json
</pre>
