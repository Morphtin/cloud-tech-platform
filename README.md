# Cloud-Tech-Platform
云平台构件 - 多租户科技资源及服务认证与授权  
服务课题 -  专业科技资源及服务集成技术（2017YFB1400804）
----
## 架构
![image](https://f.png)

----
## 技术特色
 本项目前端部分基于 vue.js elementUI 等技术实现  
 
----
## 代码结构
```
.
├── LICENSE
├── README.md
├── build
│   └── index.js
├── package.json
├── public
├── src
│   ├── App.vue
│   ├── api
│   ├── assets
│   ├── components
│   ├── directive
│   ├── icons
│   ├── layout
│   ├── main.js
│   ├── permission.js
│   ├── router
│   │   └── index.js
│   ├── settings.js
│   ├── store
│   ├── styles
│   ├── utils
│   │   ├── auth.js
│   │   ├── echarts.js
│   │   ├── get-page-title.js
│   │   ├── getResource.js
│   │   ├── index.js
│   │   ├── permission.js
│   │   ├── request.js
│   │   ├── scroll-to.js
│   │   └── validate.js
│   └── views
│       ├── 404.vue
│       ├── README.md
│       ├── dashboard
│       │   └── index.vue
│       ├── login
│       │   └── index.vue
│       ├── permission
│       │   ├── components
│       │   │   └── SwitchRoles.vue
│       │   ├── directive.vue
│       │   ├── page.vue
│       │   └── role.vue
│       ├── rbac
│       │   ├── role.vue
│       │   ├── rolebinding.vue
│       │   └── secret.vue
│       ├── routesOperation
│       │   └── index.vue
│       └── table
│           └── index.vue
└── vue.config.js
```
* /src/utils - 相关工具模块
* /src/views/permission - 用户访问权限管理页面
* /src/views/rbac - 集群角色管理页面

----
## 部署方式
```
git clone <url>
npm install   
npm run dev   
```
----
## 使用说明
平台截图  
![image](https://f.png)

