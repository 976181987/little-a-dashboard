# Little A Dashboard

a little material-style dashboard build upon reactjs, ant design, dva.js. 基于 react.js, ant design, dva.js 开发的类 material 风格的 dashboard。

## Quick Start   


#### Clone 

    git clone https://github.com/huzzbuzz/little-a-dashboard.git

#### Install 

    cd little-a-dashboard
    npm i or yarn install

#### Run    
> before run this，you might need to installed roadhog cli，otherwise `npm i roadhog -g`
```bash
npm start
``` 
> it will automatically open http://localhost:8000

#### Build 
```bash
npm run build
``` 
> it will automatically generated dist directory


## Already Done
- [x] 类 material-ui 风格
- [x] 登录、退出、锁屏（模拟）
- [x] 主页及其他示例页
- [x] 菜单折叠、换肤
- [x] redux 完整使用示例
- [x] 动态路由，按需加载
- [x] 简易 Mock 功能
- [x] 打包后，Filename Hash

## Further Plan
- [] Automatically select the menu based on the url
- [] Responsive Sidebar
- [] Full RESTful API

## Screenshot
> 图有些大


## Acknowledge 

- [Ant Design](https://github.com/ant-design/ant-design)
- [Creative Tim](https://github.com/creativetimofficial)
- [Angular Material Dashboard](https://github.com/wangdicoder/angular-material-dashboard)
- [Antd Admin](https://github.com/zuiidea/antd-admin)
- [Sweet Alert 2](https://github.com/limonte/sweetalert2)


## Project Structure

```bash
├── /dist/           # 打包输出
├── /mock/           # mock数据
├── /public/         # 公共文件
├── /src/            # 项目源码
│ ├── /components/  # UI组件
│ ├── /models/      # 数据模型
│ ├── /routes/      # 路由组件
│ │ └── app.js      # 入口
│ ├── /services/    # 数据接口
│ ├── /themes/      # 项目样式
│ ├── /utils/       # 工具函数
│ │ ├── config.js    # 项目配置
│ │ └── request.js   # 异步请求函数
│ ├── route.js      # 路由配置
│ ├── index.js      # 入口文件
│ └── index.html     
├── package.json     # 项目信息
├── .roadhogrc.js    # roadhog配置
├── .roadhogrc.mock.js # roadhog mock
├── theme.config.js  # 更改 ant 主题
└── webpack.config.js
```

## License

MIT

