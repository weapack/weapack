# weapack

weapack 是一个小程序的模块打包器，它的目标是把 JavaScript、json、wxml、wxss 打包以便在小程序中使用，同时，它也能转换、打包任何文件资源。

## 目录

1. [安装](#安装)
2. [介绍](#介绍)
3. [概念](概念)
4. [TODO](#TODO)


### 安装
```bash
npm install weapack/weapack -D
```

### 介绍

### 概念

### TODO

- [ ] 依赖问题
  - [ ] 被依赖的其它 wxss 文件
  - [ ] 被 wxml import 的 wxml 片段
  - [ ] 多线程 Worker 依赖处理
- [ ] 新增 parser-entry 阶段
- [ ] 优化 parser-file 阶段
- [ ] 配置项新增 module 字段，对不同后缀文件匹配自定义 plugin 解析
- [ ] 修复 watch 模式