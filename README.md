#**Hotel OTA Platform**
>在线旅游（OTA，全称为Online Travel Agency），是旅游电子商务行业的专业词语。 
>指“旅游消费者通过网络向旅游服务提供商预定旅游产品或服务，
>并通过网上支付或者线下付费，即各旅游主体可以通过网络进行产品营销或产品销售”。<br>

> 后台主要使用技术有Springboot/SSM/Redis/postgresql/RabbitMQ/Shiro/Docker/Gradle/HttpClient等技术


###开发人员
>主要开发人员 袁金, 刘文超（附加开发jack.zhao, 陈巩涛, 相一鹤)

###运维人员
>张梁

###测试人员
>高苗苗，肖俊，高红丹

###需求方
>陈晓俊，蔡蔡

##项目说明

####开发规范
>内部服务调用/inner/api/ 外部服务调用/outter/api/打头 <br>
>遵循阿里巴巴开发手册规范<br>


####项目结构规范
目前的目录需要做调整，期望目录如下：
###########目录结构描述
├── Readme.md                   // help
├── app                         // 应用
├── config                      // 配置
│   ├── default.json
│   ├── dev.json                // 开发环境
│   ├── experiment.json         // 实验
│   ├── index.js                // 配置控制
│   ├── local.json              // 本地
│   ├── production.json         // 生产环境
│   └── test.json               // 测试环境
├── data
├── doc                         // 文档
├── environment
├── gulpfile.js
├── locales
├── logger-service.js           // 启动日志配置
├── node_modules
├── package.json
├── app-service.js              // 启动应用配置
├── static                      // web静态资源加载
│   └── initjson
│   	└── config.js 		// 提供给前端的配置
├── test
├── test-service.js
└── tools
   