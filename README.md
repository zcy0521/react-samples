# create-react-app

[create-react-app](https://github.com/facebookincubator/create-react-app) 是业界最优秀的 React 应用开发工具之一。

## 安装

安装 [cnpm](https://www.npmjs.com/package/cnpm)

```bash
$ npm install cnpm -g --registry=https://registry.npm.taobao.org
$ cnpm -v
```

安装 [create-react-app](https://github.com/facebook/create-react-app)。

```bash
$ npm install -g create-react-app
$ create-react-app -V
1.5.2
```

安装 [yarn](https://github.com/yarnpkg/yarn)。

```bash
$ npm install -g create-react-app yarn
```

## 新建项目

安装完 create-react-app 之后，就可以在命令行里访问到 `create-react-app` 命令。现在可以通过 `create-react-app` 创建新应用。

```bash
$ create-react-app react-samples
```

工具会自动初始化一个脚手架并安装 React 项目的各种必要依赖，如果在过程中出现网络问题，请尝试配置代理或使用其他 npm registry。

## 初始化项目

`cd` 进入 `react-samples` 目录，安装依赖。

```bash
$ cd react-samples
$ yarn install
```

## 启动

`cd` 进入 `react-samples` 目录，并启动开发服务器。

```bash
$ cd react-samples
$ yarn start
```

此时浏览器会访问 http://localhost:3000/ ，看到 `Welcome to React` 的界面。
