## 当前规划

🎉 **Features**

- [ ] 老的文档迁移与更新
- [ ] 完成邮箱验证登录功能
- [x] 使用 `yapi` 搭建接口管理平台，提供数据 `mock` 环境
  - [-->接口地址](https://yapi.xwhx.top/)
  - 因个人服务器保存数据能力有限，所以不提供注册功能，查看接口文档请使用下方账号密码登录
  - 账号：`visitor` 密码：`visitor`

📚 **Docs**

- [x] [vscode 插件推荐]()
- [x] [charles 抓包工具]()
- [x] [在 vscode 中调试]()

🐛 **Bugs**

- [x] 修复 `node-sass` 依赖包老是本地安装报错的问题。改用 `dart-sass` 作为 `css` 预处理器。文档：[-->使用 dart-sass]()
- [x] 修复 `8080` 端口冲突问题，移除掉 `vue.config.js` 中 `devServer.port` 的设值，使用默认配置。

## 更新日志

### [v2.0.0](https://github.com/Ewall1106/panda-server/tree/2.0.0)

`2020-09-12`

🎉 **Features**

- 使用`vue+axios+vant`完成迭代版开发。
- 添加了一系列的新组件，诸如 `svg` 图标、`scroll` 滑动组件等。
- `axios` 请求封装及 `api` 模块封装和使用。
- `vant` 引入及使用。
- 骨架屏渲染及其它优化。
- 说明文档的编写与更新。

🐛 **Bugs**

- 修复 `yapi` 数据 `mock` 问题，暂时先使用自己搭建的 `panda-server` 后端服务。
- 其它。

⚠️ **Notice**

- 目前商城还不够完善，整个购买交易流程还没有走完。

### [v1.0.0](https://github.com/Ewall1106/panda-server/tree/1.0.0)

`2020-05-17`

🎉 **Features**

- `vue-cli2.0` 构建的项目
- axios 的使用
- vuex 的基础使用
- 其它

🐛 **Bugs**

- 暂无
