 <center>
     <h1>姜文佳</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             17366383766
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             wen_jia_jiang@163.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/coderjiangjiang">coderjiangjiang</a>
         </span>
         <!-- ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="#">My Blog</a>
         </span> -->
     </div>
 </center>

## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息

- 男，32岁
- 政治面貌：党员
- 求职意向： Web开发工程师
- 工作经验：10 年

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 本科学士，湖北工业大学，电子信息科学与技术专业，2009.9~2013.7
- 通过了 CET6 英语等级考试

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **北京优锘科技有限公司（Uino），研发中心/应用工具/图表，Web高级开发工程师，2022.5~至今**
    - ***工作内容：***
      - web端图表生产工具相关开发工作
      - node服务端对于图表代码资源编译的相关开发工作
      - 技术文档分享

- **杭州博联智能科技股份有限公司（Broadlink），南京研发中心/H5小组，移动前端工程师、H5小组长，2016.2~2022.5**
    - ***工作内容：***
      - 智能家具产品平台移动端SPA开发环境搭建
      - 负责移动端JSSDK接口库开发与维护
      - 负责通用组件库开发
      - 负责代码review，技术文档分享

- **武汉松果科技有限公司，前端开发工程师，2014.8~2015.12**
    - ***工作内容：***
      - 负责公司官网开发
      - 新生入学报名系统

- **南京安普利网络系统服务有限公司，运维工程师，2013.7~2014.06**
    - ***工作内容：***
      - 服务器硬件问题定位监测(硬盘坏块测试等)以及系统软件升级
      - 服务器配件更换等机房维护工作


## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **Uino图表Web应用工具项目**

    - ***主要技术***
    *Vue、Webpack、monaco-editor、web worker、service worker、iframe、stylus等*
    - ***主要功能***
      - 为公司大屏平台提供基础的各种图表资源生产能力
      - 提供实时在线代码编辑预览图表资源的能力
      - 为公司零代码平台提供基础二维图表等物料生产能力
    - **个人贡献**
      - 为图表在线编辑器（基于monaco-editor）提供vue2语法扩展(后期升级支持了vue的setup语法糖)，完成了包括vue的语法高亮、快捷代码、代码补全提示、eslint错误校验、prettier格式化代码等等一系列工作，将公司原本通过原生js+jsx的图表资源开发方式转向采用主流的Vue单文件的开发方式提供基础
      - 利用monaco-editor的某些特性封装出变量替换的相关接口，以提供图表开发各种快捷功能的技术基础
      - 使用service worker技术完成图表项目在本地与图表node编译服务本地的功能联调，减少了图表项目与node编译项目需要频繁推送测试环境导致的测试资源冲突以及联调效率问题
      - 通过减少项目中导致重绘与回流的操作以及解决render重复调用的问题，图表js资源阻塞加载问题，以优化图表运行时速度问题

- **Uino图表应用node编译服务项目**

    - ***主要技术***
    *Node、Egg.js、Babel、Esbuild、@vue/compiler-sfc等*
    - ***主要功能***
      - 为图表工具提供父类基类的静态文件
      - 为图表在线编辑器预览功能提供代码编译功能
    - **个人贡献**
      - 为图表实时预览页面提供vue语法父类基类方法
      - 为图表在线编辑器输出的图表代码提供vue2语法(以及vue的setup语法)代码的编译功能，以支持图表采用Vue单文件开发方式实现浏览器端的实时预览功能
      - 利用babel ast语法分析树技术解决vue setup语法图表代码在运行之前变量值获取问题
      - 通过缓存/编译工具以及流程调整以优化首次预览以及图表编译速度问题

- **Uino图表应用画布容器库**

    - ***主要技术***
    *Node、gulp、Babel等*
    - ***主要功能***
      - 为图表渲染提供容器
      - 为图表容器提供各种拖、拉、拽、旋转等等基础功能实现
    - **个人贡献**
      - 为容器层增加水印插件以实现图表、大屏等平台的水印功能
  
- **BL智能家居产品控制SPA通用开发**

    - ***主要技术***
    *Webpack、React、Redux、TypeScript、Less等*
    - ***主要功能***
      - 为智能电器控制SPA提供统一快速开发脚手架
      - 为智能电器控制SPA提供通用云定时以及设备定时模块
    - **个人贡献**
      - 平台通用组件封装及维护
      - JSBridge 相关的 JSSDK 接口库封装，开发维护 TS 版 NPM 库: broadlink-dna-jssdk
      - 新平台脚手架环境搭建


## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- ★★★★★ Javascript、Vue、React、CSS(Less/Sass)
- ★★★★☆ Node、Webpack、TypeScript
- ★★★☆☆ Python、Redis、MongoDB
