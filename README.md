# wwt-xen-eth

Created with CodeSandbox

# 依赖项功能说明

"dependencies": {

//RainbowKit 是一个 React 库，可以轻松地将钱包连接添加到您的 dapp。

//https://github.com/rainbow-me/rainbowkit#readme

"@rainbow-me/rainbowkit": "0.7.1",

//ReactJS 的官方 Sentry SDK

//https://github.com/getsentry/sentry-javascript/tree/master/packages/react

"@sentry/react": "7.14.2",

//分布式跟踪( Distributed tracing )通过捕获软件系统之间的交互来提供相关错误和事务的连接视图。

//https://github.com/getsentry/sentry-javascript/tree/master/packages/tracing

"@sentry/tracing": "7.14.2",

//一种在 Javascript 中添加浮点数的跨浏览器、数值稳定的方法。产生总和的忠实四舍五入（结果是真值的直接浮点邻居）。

//https://github.com/ben-ng/add

"add": "2.0.6",

//最流行、免费和开源的 Tailwind CSS 组件库

//https://daisyui.com/

"daisyui": "2.31.0",

//JavaScript（和 TypeScript）中完整的以太坊钱包实现和实用程序。

//https://www.npmjs.com/package/ethers

"ethers": "5.7.1",

//一个声明式，高效且灵活的用于构建用户界面的 JavaScript 库。 使用 React 可以将一些简短、独立的代码片段组合成复杂的 UI 界面，这些代码片段被称作“组件”。

"react": "18.2.0",

//将虚拟 DOM 渲染到文档中变成实际 DOM；“react-dom”是 react 开发项目时需要使用的工具包，提供了 DOM 特定的方法，可以在应用程序的顶层使用，也可以作为 React 模型之外的特殊操作 DOM 的接口。

"react-dom": "18.2.0",

//React Hot Toast 是一个热门的通知库，包含很多通知的样式。

"react-hot-toast": "2.4.0",

//create-react-app 入门包中的一组脚本。 create-react-app 可帮助启动项目而无需进行配置，因此不必自己设置项目。 react-scripts start 设置开发环境并启动服务器，以及热模块重新加载。

"react-scripts": "4.0.0",

//Recoil 是 React 的实验性状态管理框架。

"recoil": "0.7.5",

//用于连接以太坊的 React Hooks，20 多个用于处理钱包、ENS、合同、交易、签名等的钩子。

//https://github.com/wagmi-dev/wagmi

"wagmi": "0.6.8",

//Hadoop 架构中的资源调度引擎模块，从这个模块名字就可以看出来，YARN 是用来为应用提供资源管理和调度的。

"yarn": "1.22.19"

},

"devDependencies": {

//将开发者依赖的全局内置对象等，抽取成单独的模块，并通过模块导入的方式引入，避免了对全局作用域的修改（污染）。

//是开发库、工具，一般考虑使用 babel-runtime。

"@babel/runtime": "7.13.8",

//用于项目打包的插件

"@vitejs/plugin-react-refresh": "^1.3.6",

//css 中一些属性标准规范还没有发布，每个浏览器厂商同一个样式支持的写法不同，所以要加前缀来达到各个浏览器兼容。

//帮我们自动补齐前缀，它属于后置处理器，是在代码打包生成后再进行处理，其实是 postcss 的一个插件

"autoprefixer": "^10.4.12",

//提供了一种方式用 JavaScript 代码来处理 CSS。 它负责把 CSS 代码解析成抽象语法树结构（Abstract Syntax Tree，AST），再交由插件来进行处理。

"postcss": "^8.4.17",

//Tailwind 能够快速将样式添加到 HTML 元素中，并提供了大量的开箱即用的设计样式。 tailwindcss 基于比组件更小、更灵活的工具类思想的 CSS 框架。

"tailwindcss": "^3.1.8",

//TypeScript 可以被编译为 JavaScript。 因此，TypeScript 可以在任何可以使用 JavaScript 的地方使用：包括前端和后端。

//JavaScript 是用于为应用程序和网页的前端实现脚本的最流行的语言。 因此，TypeScript 可以用于相同的目的，但是它在服务器端的复杂企业项目中很有用。

"typescript": "4.1.3",

//一个构建工具，改善前端开发体验。 你可以用 Vite 为 Vue 和 React 等框架建立一个开发环境，甚至可以用三个命令建立一个带有开发服务器和热重载的 vanilla JavaScript 应用。

"vite": "^3.1.7"

},
