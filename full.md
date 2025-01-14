 <center>
     <h1>郜修</h1>
     <div>
         <span>
             <img src="assets/icons/phone.svg" width="18px">17611583237
         </span>
         &nbsp;·&nbsp;
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             gaoxiu333@gmail.com
         </span>
         &nbsp;·&nbsp;
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/gaoxiu333">gaoxiu333</a>
         </span>
         &nbsp;·&nbsp;
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="https://www.gaoxiu.me/">我的博客</a>
         </span>
     </div>
 </center>

 ##  个人信息 

 - 求职意向：前端研发工程师
 - 工作经验：7 年
 - 到岗时间：两周内到岗

## 个人优势

- 掌握前端流行框架，具备 Vue 和 React 从 0 到 1 的项目开发到上线的实战经验
- 具备一定的 Node 开发能力，熟悉 Express 和 Mongodb 的使用。
- 有带小组经验，技术方案能拍板，敢于决策，有能力让技术方案落地。
- 熟悉前端工程化，有丰富的性能优化实战经验。

## 工作经历

**宝马汽车金融（中国）有限公司 ｜ 驻场 ｜ 前端开发**（2022\.03-2023.04 ）

- 负责前端基建，先后搭建了金融服务系统、Chat 微前端，推动项目从 0 到 1 落地到上线

- 主导前端架构设计，技术选型，负责前端面试，面试超 30+ 人，入职 2 人

**北京爱云校 | 新高考研发部门 | 前端组**（2018\.08\-2021.12 ）

- 项目核心开发，主导公司核心项目的搭建、开发、迭代维护。
- 日常需求评估，任务拆分，人力协调，技术攻关。

**北京微瑞科技有限公司 ｜ 北京软件研发部 ｜ 前端**（2017.06-2018.08 ）

- 推动前后台分离，先后独立完成多个前端系统的搭建和开发

**南京稻盛弘网络科技有限公司 ｜ 研发部 ｜ 前端**（2015.07-2017.05 ）

- 前端开发，负责公司生产系统的开发、迭代维护。

## 项目经历

- **日本宝马金融服务系统（JP-SCP 系统）**

  *技术栈：*`Angular` \| `Typescript` \| `Ant Design` \| `Lodash` \| `Immer` \| `ngx-translate` 

  描述：提供给日本宝马经销商和销售使用的金融报价和管理系统，支持国际化、权限、审批、站内通知等功能，满足用户需求，提升销售和内部用户对系统的使用体验。

  - 搭建项目，并使用 eslint + prettier 统一代码项目代码风格

  - 设计不同角色权限、接口拦截器、多语言配置等核心模块的封装和常用工具函数的封装

  - 因为系统中存在大量表单，提出抽象表单类，简化表单模块开发，提升开发效率 30%-50%。

- **话务系统（微前端）**

  *技术栈：*`Rollup` \| `TypeScript` \| `Preact` 

  描述：服务于宝马话务员系统，搭建微前端平台进行项目拆分与集成，生成统一的报表数据。

  - 复用其他已有项目模块，抽离登陆、鉴权能模块
  - 负责话务数据收集、话务报表模块等功能的实现
  - 使用 npm 包进行版本管理，统一管理，通过一键升级所有的子系统相关的功能。

- **拼渤数据分析平台**

  *技术栈：*`Vue3` \| `Typescript` \| `Vite` \| `Vue-Router` \| `Ant Design` \| `Lodash` \| `ECharts` \| `PDF.js` \| `QRCode.js`

  描述：一个营销系统，以多种模式分析微博、抖音、快手、小红书等赞助推广 IP 价值的平台，帮助品牌/IP 方获取有用的信息，支持会员在线支付、套餐升级，订单管理等功能。

  - 为了解决就项目代码臃肿和迭代困难的问题，实现旧项目的完全重构，减少了大于60%的臃肿代码
  - 通过引入 EChats ，可视化数据，提升用户体验
  - 通过封装虚拟化渲染，提高长列表渲染性能

- **学生成绩分析系统**

  *技术栈：*`Vue` \| `Vue Router`\| `Vuex` \| `ExcelJS` \| `Lodash` \| `ECharts` 

  描述：提供给教育局、教师、学生使用的成绩分析系统；支持权限、根据权限生成不同维度不同报表的生成。

  - 通过劫持修改 VirtualDOM ，对所有报表生成 PDF 分页和目录，实现前端导出 PDF 功能，节省了业务的工作量，从原来几天才能生成一张报表到现在的点一点。
  - 抽离封装鉴权、通用方法等封装成 NPM 包管理，方便小程序等多端代码的逻辑的复用。
  - 使用 Nodejs 作为服务端，设计任务队列，调试浏览器导出 Excel 性能瓶颈，数据量过大时（5M），使用后台生成 Excel  ，提升用户体验。
  - 由于 Exceljs 的性能问题，过大的 Excle 生成耗时过长（大于500M），修改 Exceljs 解析和生成表头部分逻辑，降低约 60% Excel 生成时间，降低服务端生成 Excel 的压力。

- **区域数据大屏**

  技术栈：`React`|`React-Router`|`React-Redux`｜`Webpack`|`ECharts`｜`WebSocket`

  描述：给教育局提供的数据大屏可视化系统，分析呈现各个区域学生成绩信息，实时显示联考信息。

  - 使用 WebSocket 实时接入数据，完成热点地图、区域排名、联考排名等模块的可视化开发。
  - 通过浏览器  `performance` 面板调试性能瓶颈，解决低性能平台大屏卡顿问题

- **埋点**

- **PCB贴片报价系统**

  描述：一个面向海外的电路板贴片报价的商城类网站，支持国际化。

  *技术栈：*`webpack`|`React.js` | `jsp` | `BootStrap` | `jQuary`

  - 负责订单模块、账户、在线支付模块，与后台联调沟通，完成功能的开发。
  - 接入物流云平台，实现物流查询模块，完成在订单中查看物流状态的功能。

- **车辆管理系统**

  描述：一个车载设备的管理系统，收集车辆运行信息，提供车辆状态和运行轨迹分析等功能。

  *技术栈：*`React`|`React-Router`|`React-Redux`|`Google Map`｜`Nodejs`|`Express`|`Mongodb`

  - 独立负责前后台的搭建，分析车辆的运行参数数据，完成对车辆状态参数和历史轨迹等参数的模块开发。
  - 前端引入`Google Map`，通过对轨迹参数信息，完成在地图上绘制出车辆的运行轨迹，自定义标识等功能

##  技能清单

- ★★★ JavaScript、TypeScript
- ★★★ Vue、React
- ★★☆ Angular、Nextjs
- ★☆☆ Nodejs、Express

## 教育经历

<div style="display:flex;justify-content:space-between;"><strong>2012.09-2015.06</strong><strong>河南工业职业技术学院</strong><strong>大专</strong></div>
