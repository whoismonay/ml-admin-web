# ml-admin-web

* 这是一个基于ml-admin管理后台的前端页面。它包含了登录、认证、组织机构、用户帐号、角色权限、菜单、操作日志，这些搭建后台必要的东西。
* 基于 ElementUI 和 vue 进行开发，使用vue-admin-template模板

## 代码
* github地址： https://github.com/whoismonay/ml-admin-web
* 服务端github地址： https://github.com/whoismonay/ml-admin

## 项目使用

```bash
# 克隆项目
git clone https://github.com/whoismonay/ml-admin-web

# 进入项目目录
cd gmanager-web

# 安装依赖
npm install

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9529](http://localhost:9529)

## 打包发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```
## 功能模块

1. 登录、认证、登出
2. 组织机构管理
3. 用户管理
4. 角色管理
5. 菜单管理
6. 支持登录、登出、业务增删改操作记录