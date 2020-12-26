
<p align="center">
  <a href="https://www.steedos.com/cn">
    <img alt="华炎费用管理系统" src="https://steedos.github.io/assets/logo.png" width="120" />
  </a>
</p>
<h1 align="center">
  华炎费用管理系统
</h1>

<p align="center" style="border-top: solid 1px #cccccc">
  帮助您管理费用记录、费用审批及费用统计。系统使用华炎魔方平台可视化配置实现，基于元数据驱动，可以快速自定义。

</p>

<h3 align="center">
 🤖 🎨 🚀
</h3>

# 项目管理系统案例




## ✨系统功能

- **费用**：费用明细的集合，类似于费用报销单。

- **费用明细**：明细费用记录，有相应的财务单据相对应。

## 关于华炎魔方

华炎魔方是一套可视化建模、描述式编程的开发工具。设计目标是降低应用构建门槛，让每个人都能参与开发。系统内置了数据建模以及一系列自动化工具，包括验证规则、公式计算、工作流规则、自动化操作、批准过程、报表引擎等等。

- [华炎魔方概述](https://www-steedos-com.oss-accelerate.aliyuncs.com/videos/steedos/steedos-open-source.mp4)
- [华炎魔方文档](https://www.steedos.com/help/)

## 依赖包

- [MongoDB](https://www.mongodb.com/try/download/) version >= 3.4. MongoDB is a general purpose, document-based, distributed database built for modern application developers and for the cloud era.
- [Node.js](https://nodejs.org/en/download/) version >= 10.15.1 or above (which can be checked by running `node -v`). You can use [nvm](https://github.com/nvm-sh/nvm) for managing multiple Node versions on a single machine installed
- [Yarn](https://yarnpkg.com/en/) version >= 1.5 (which can be checked by running `yarn version`). Yarn is a performant package manager for JavaScript and replaces the `npm` client. It is not strictly necessary but highly encouraged.


## 项目目录

```sh
project-management-app
├── steedos-app/main/default
│   ├── applications
│   │   └── project.app.yml
│   └── objects
│       └── project__c
│           ├── buttons
│           │   └── print.button.yml
│           │   └── print.button.js
│           ├── fields
│           │   └── name.field.yml
│           │   └── description.field.yml
│           │   └── isDone.field.yml
│           │   └── status__c.field
│           │   └── ...
│           ├── listviews
│           │   └── all.listview.yml
│           │   └── recent.listview.yml
│           │   └── my.listview.yml
│           ├── permissions
│           │   └── user.permission.yml
│           │   └── admin.permission.yml
│           │   └── project_manager.permission.yml
│           └── project.object.yml
│           └──...
├── .env
├── .gitignore
├── package.json
├── README.md
├── server.js
├── steedos-config.yml
└── yarn.lock
```

## 项目运行

项目源码依赖 nodejs 环境，使用 mongodb 数据库，需先部署相应的运行环境。

1、 启动数据库

2、安装依赖软件包

```
yarn
```

3、运行项目

```
yarn start
```

4、使用浏览器访问 http://127.0.0.1:5000/

第一次使用时，数据库为空，需注册一个账户，并选择创建一个企业。

## 保持联系

如果您有任何疑问或想与其他华炎魔方用户交谈，请[点击进入讨论](https://github.com/steedos/steedos-platform/discussions)或扫码添加以下联系方式与我们联系！
##### 开发人员微信群
![开发者微信交流群](https://steedos.github.io/assets/github/project_management_app/cn/QR_wechat_developers.jpg)

##### 商务咨询
![商务咨询](https://steedos.github.io/assets/github/project_management_app/cn/business_consulting.jpg)

##### 微信公众号
![微信公众号](https://www.steedos.com/assets/github/platform/cn/public_number.jpg)
