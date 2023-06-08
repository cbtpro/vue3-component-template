# vue3-component-template

## 安装依赖

```sh
# 全局安装pnpm管理器
npm install -g pnpm
# 安装项目依赖
pnpm i
```

## 文档

## 编写文档

```sh
pnpm run docs:dev
```

## 编译文档

```sh
pnpm run docs:build
```

## 预览文档

预览前必须要先执行编译文档`pnpm run docs:build`

```sh
pnpm run docs:preview
```

## 发布

### 私服

#### 启动npm私服

```sh
pnpm run start:verdaccio
```

> 通过浏览器访问[http://localhost:4873/](http://localhost:4873/)
在右上角的齿轮中可以设置界面展示为中文，[更多文档verdaccio](https://verdaccio.org/zh-CN/docs/what-is-verdaccio)

#### 发布到私服

```sh
pnpm pub:local
```

### npm

```sh
npm publish
```
