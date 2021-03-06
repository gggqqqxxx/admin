

## 简介

[admin]是一个后台前端解决方案，它基于 [vue] 和 [element-ui]实现。动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型


## 功能

```
- 登录 / 注销

- 权限验证
  - 页面权限

- 全局功能
  - 多种动态换肤
  - 动态侧边栏（支持多级路由嵌套）
  - 动态面包屑
  - 快捷导航(标签页)
  - 本地/后端 mock 数据


- 错误页面
  - 401
  - 404

- 組件
  - 返回顶部
- 错误日志
- Dashboard
- 引导页
- ECharts 图表
```

## 开发

```bash
# 克隆项目
git clone https://github.com/PanJiaChen/vue-element-admin.git

# 进入项目目录
cd vue-element-admin

# 安装依赖
npm install

# 启动服务
npm run dev
```

浏览器访问 http://localhost:9527

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```
