# **污水排污监测与预警平台**
`vue2.0`  `JavaScript`  `Pinia`  `Element-UI`

[在线演示](https://lujiuwu.github.io/SewageControlProject/dist/index.html)

## 项目简介
污水排污监测与预警平台是一款以污水处理为设计主题的后台管理系统，完全采用 ECMAScrip 模块（ESM）规范来编写和组织代码，基于 Vue2、Element-vue2、JavaScript、Pinia、等主流技术开发

## 目录结构描述
```
├── Readme.md                   // help
└── src                         // 配置
├── assets                      // 静态资源
    ├── components              // 全局组件
    ├── router                  // 路由
    ├── show_data
    │   └── map.json            // 地图数据
    ├── store                   // 状态管理库
    ├── views                   // 页面目录
    ├── web_data                // 主要静态数据
    └── App.vue                 // 设置路由出口
```

## 安装使用
### 从GitHub上拉取
```
git clone git@github.com:lujiuwu/SewageControlProject.git
```

### 安装依赖
```
npm install
```

### 启动平台
```
npm run serve
```

### 项目打包
```
npm run build
```

## 如何贡献

非常欢迎您的加入！[提一个 Issue]([Issues · lujiuwu/SewageControlProject (github.com)](https://github.com/lujiuwu/SewageControlProject/issues)) 或者提交一个 `Pull Request`

**Pull Request:**

1. Fork 代码!
2. 创建自己的分支: `git checkout -b feat/xxxx`
3. 提交您的修改: `git commit -am 'feat(function): add xxxxx'`
4. 推送您的分支: `git push origin feat/xxxx`
5. 提交`pull request`
