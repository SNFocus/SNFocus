
## 个人信息
- 本科 / 2019届xxxxxx信息管理与信息系统专业
- Github：github.com/SNFocus
- 期望职位：前端开发
- 期望城市：北京

## 项目经验
### 2018 宿主机管理平台
项目描述：虚拟主机管理平台，提供可视化信息展示。
1. 独立开发，改版前使用Jquery + Bootstrap， 新版使用angular.js重构
2. 使用Echarts展示主机网络，CPU占用等元信息和统计数据

### 2019-2020 企业协同运营平台（含网盘，业务流程，OA等）
项目描述：，整合公司较为重要的业务流程体系和OA系统（Vue + ElementUI）
1. 应用自定义指令，实现**按钮级权限控制**
2. 开发**命令式弹窗**等组件。
3. **独立负责**云盘模块，应用虚拟列表优化加载方式，提升用户体验。
4. 为了提高可重用性，抽离公共业务组件作为**组件库**发布到`npm package`，供后续多个项目使用。
5. 运用**逆波兰表达式**，开发计算公式组件，动态计算指定组件集合的值总和。


## 开源项目
### 仿钉钉审批表单及流程创建（开源 Star 140+）
预览地址-http://soning.gitee.io/approvalflow/
1. 基于Form-Generator并扩展自定义组件（表单表格，计算器等十余种，支持定制化）**，拖拽生成表单**，可视化配置属性。生成JSON格式数据。
2. **可视化配置流程节点**（发起人，审批人，抄送人，条件）及节点详细信息，生成JSON格式数据。
3. 校验流程条件，应用VUEX同步条件节点与表单必填组件信息，配置不同节点的表单控制权限。
4. 使用VUE模板代码生成和JSX渲染两种模式**生成动态表单**，并实现必填数据验证，表格数据验证等。
5. **GitHub Action** 自动部署。

### 简注（注释生成器）
预览地址-http://soning.gitee.io/simplecomment
1. 使用 Vue + Ant Design + TypeScript，commitizen规范git提交信息， conventional-changelog 生成提交历史等。
2. **可视化配置文本注释**，包含表格，列表（树），文本边框包裹，图片转文本功能。能对边框（表格）四角，上下分割线，左右分割线做细致配置。
3. 使用分组+异步的方式绘制（Canvas）百余个注释图形，解决了canvas高度自适应问题，将首屏时间从**4s**降低到**0.4**秒。

## 练习作品
### 文件服务DEMO
1. Node + Express + MySql + CentOS(阿里云) 搭建后台服务
2. Vue + ElementUI + Axios + Nginx 部署前端网站
3. 配合Node实现**分片上传**(sparkMd5生成MD5)，**断点续传**，**进度展示**
4. Github **WebHook** + Node（**child_process**）实现自动部署到阿里云

### 静态博客
__require.context__**自动注册路由**， 自定义**Webpack Plugin + Loader**, 实现获取md文件头部自定义信息并整合输出为文件，作为文章索引数据。

### 自习打卡小程序
**云开发** + **ColorUI**，打卡定位时间记录，**Echarts**展示周打卡统计及考试成绩曲线等

## 技能清单
- 熟悉：Vue ES6 ElementUI SASS
- 了解：小程序 Webpack Node Express MySql
- 工具：Git Photoshop
