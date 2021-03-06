### electron-vue 引入 websdk

`注:` [electron-vue](https://github.com/SimulatedGREG/electron-vue) 本身已经长时间不维护, 且 issues 无人处理. 正常情况下, 不建议使用. 如集成桌面版项目, 可直接使用 [electron](https://www.electronjs.org/) 和 [vue](https://cn.vuejs.org/)

#### 开发环境

node 8.12.0 及以上版本

#### 启动

1、安装依赖包

```
npm install electron@2.0.4 --save-dev
npm install
```

2、运行

```
npm run dev
```

3、打包

```
npm run build
```

#### 相关文件

```
src/renderer/components/init.vue
```

#### 注意

1、此 Demo 仅为 electron-vue 引入融云 websdk 示例, 非完整项目

2、electron-vue 具体环境安装、打包配置等问题, 请参考 [electron-vue](https://github.com/SimulatedGREG/electron-vue) 文档

3、使用 electron-vue 时, 为避免遇到问题无排查方向, 建议提前了解以下知识:

> Electron: [https://electronjs.org/docs](https://electronjs.org/docs)

> electron-builder: [https://github.com/electron-userland/electron-builder](https://github.com/electron-userland/electron-builder)

> Vue.js: [https://cn.vuejs.org](https://cn.vuejs.org)

> webpack: [https://webpack.js.org](https://webpack.js.org)

