# V2Board User 前端项目

一个美观、现代的V2Board管理后台前端项目，基于Vue 3开发。

## 🥳自动化打包技术
#### 我们基于Actions实现了自动化打包技术，只需要两分钟就能零成本获取“ez-theme-dist”，新手也能轻松部署完成！

[![Build EZ-Theme](https://github.com/ExcellentCloud/EZ-Theme/actions/workflows/main.yml/badge.svg)](https://github.com/ExcellentCloud/EZ-Theme/actions/workflows/main.yml)

## 特性

- 🎨 美观的UI设计，简约高端
- 🌓 支持亮色/暗色主题切换
- 🌍 内置国际化支持（中文/英文）
- 📱 响应式设计，适配各种设备
- 🔒 完善的登录认证系统
- 🚀 模块化的代码结构，易于维护

## 技术栈

- Vue 3 - 渐进式JavaScript框架
- Vue Router - 官方路由管理器
- Vuex - 状态管理模式
- Axios - 基于Promise的HTTP客户端
- Sass - CSS预处理器
- Vue I18n - 国际化解决方案

## 项目结构

```
src/
├── api/                # API接口
├── assets/             # 静态资源
│   └── styles/         # 样式文件
│       ├── base/       # 基础样式
│       ├── components/ # 组件样式
│       └── layouts/    # 布局样式
├── components/         # 公共组件
├── composables/        # 组合式API
├── i18n/               # 国际化
│   └── locales/        # 语言包
├── router/             # 路由配置
├── store/              # Vuex存储
├── utils/              # 工具函数
└── views/              # 页面视图
```

## 开始使用

### 🚫不好意思，我们不需要这种浪费时间与资源的打包方式！

## 自定义配置

### 主题配置

主题颜色和其他配置可以在 `src/utils/baseConfig.js` 文件中修改。

### API配置

API基础URL可以在 `src/utils/baseConfig.js` 文件中修改。

## 开源万岁



