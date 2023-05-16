---
title: resume
date: 2023-03-24 20:29:36
---

## 个人信息

- 刘青松：男/1999.3
- 工作年限：2年
- 语雀：[polaris🔗](https://www.yuque.com/polarisink)
- 技术博客：[北辰代码海游记🔗](https://polaris.ink)
- Github：[polarisink🔗](http://github.com/polarisink)
- 期望职位：`Java初级开发`/`Golang初级开发`
- 期望薪资：税前月薪12k~14k，特别喜欢的公司可例外
- 期望城市：`成都`/`杭州`/`武汉`/`南京`

---

## 教育经历
- 本科：`安徽工业大学`/`数理科学与工程学院`/`信息与计算科学`    `2017.9-2021.7`


## 联系方式

- Email：`polarisink@163.com`
- 微信：`polarisink`

---

## 技能清单
- Java：熟练掌握Java基础，OOP/AOP思想，有良好的代码风格，熟练使用Debug进行程序调试
- Web后端：掌握SpringBoot、SpringCloud体系技术栈使用及相关常用注解方法，使用过Vert.x/Quarkus，有一点了解
- 数据库相关：掌握通用sql，熟练使用MySQL，包括sql性能优化，索引优化；掌握Redis常见使用；了解TdEngine的使用
- ORM：熟练使用JPA进行数据库全自动管理，快速实现业务；熟练使用MybatisPlus
- 版本管理、文档：Git、Swagger、ApiFox
- 部署工具：熟悉常用Linux命令，独立搭建运行环境、使用Docker进行服务部署
- Golang：了解语言基础、了解`Tcp服务器编写`、使用`go-zero`进行后端web服务开发

---

## 工作经历

### 武汉华中数控股份有限公司 （ 2021年11月 ~ 现在 ）

- 四位一体
- 远程运维

### 武汉理工光科股份有限公司 （ 2021年6月 ~ 2021年10月 ）

- 智慧消防

### 武汉一鹭网络科技有限公司 （ 2020年11月 ~ 2021年5月 ）

- IM相关实习


---
## 项目经历
### 四位一体
- 开发工具：Idea、Linux、Docker、Minio、ApiFox
- 应用技术：SpringBoot、Jpa、QueryDSL、Redis、Maven
- 项目描述：一个机床制造过程生命周期（装配、调试、补偿、健康保障）过程中的状态记录，处理存储与分析的应用
- 负责内容：
  - 负责整个项目的从0后端开发，包括库表设计、接口编写、数据excel导入导出、用户系统、日志记录、minio镜头资源服务器、文档编写。
  - 使用SpringBoot+SpringCloud的核心框架；<br/>Jpa对数据库实体进行全自动管理，包括字段注释，索引维护，只用关心业务开发；<br/>使用QueryDSL实现复杂查询SQL的编写，类型安全。
  - 规范项目中全局配置，包括`异常枚举断言`、`全局异常处理`、`日志切面`、`rest日志`、`日期类配置`、`通用树结构工具类`等。
  - 实现装配需要的树形模板，即动态可编辑有序子树形模板，包括新建子结构、复制、插入等多种功能；<br/>子模板动态拼装成大模板，再结合机床档案实现不同机床档案装配数据项数值的保存；<br/>使用excel进行树形结构的导入导出的上传及下载，通过测试后得到了机床厂使用人员的一致认可。
  - 使用mqtt读取机床在线状态，发起调试/补偿/健康保障数据的下发请求。
  - 配置多数据源，读取其他数据库调试/补偿/健康保障的数据，使用`RestTemplate`和`okhttp`调用远程rest接口。
  - 使用spring-cache对装配模板及机床档案及远程接口进行缓存性能优化，减少响应时间及数据库负担。
  - 使用`自定义注解`+`AOP切面`实现用户量不大的基于`RBAC`的用户鉴权系统，使用密码或验证码登录，实现前端的`动态路由`，使用jwt+redis实现用户的`实时封禁`。
  - 编写短信`sms-spring-boot-starter`，集成第三方云之讯短信服务，也便于以后可能切换阿里云短信。
  - 使用自定义注解实现重要业务的操作日志记录的存储。
  - 使用切面实现http入参出参的日志打印，方便开发者使用。
  - 自建`minio静态资源服务器`实现静态资源的存储，实现上传及下载功能。
  - 使用ApiFox读取JavaDoc实现开发文档的实时更新。
  - 使用springboot注解@Scheduled实现简单定时任务的编写。
  - 使用docker进行前后端服务部署。
  - 再次期间参与过出差，为甲方实现内部部署及用户培训。

### 远程运维
- 开发工具：Idea、Linux、Docker、ApiFox
- 应用技术：SpringBoot、MybatisPlus、Redis、Maven
- 项目描述：一个对机床出厂后的维护的系统，包括故障报修、常规保养、预测性维护等
- 负责内容：
  - 参与部分功能模块的开发。
  - 编写会议预约模块，对腾讯会议进行一个有效管理。
  - 对时序数据库TdEngine中存储的机床基本参数进行基本的处理，让数据分析人员更方便的获取数据并进行分析。
  - 将部分云机床的老旧项目接口重新编写，优化项目结构，使用MybatisPlus替换Jpa，进行性能优化。

### 智慧消防

- 开发工具：Idea、Docker、ApiFox
- 应用技术：SpringBoot、MybatisPlus、Vue.JS
- 项目描述：一个物联网相关的城市智慧消防系统
- 负责内容：
  - 熟悉公司项目类型及开发规范
  - 参与编写智慧消防项目中的相关服务接口
  - 参与小部分管理后台的vue开发相关工作

### IM相关实习
- 开发工具：Idea
- 应用技术：SpringBoot、MybatisPlus、Nacos、Node.JS、React、Golang
- 项目描述：一个物联网相关的城市智慧消防系统
- 负责内容：
  - 熟悉Java后端开发基本规范，学习前辈代码
  - 参与部分nodejs代码和golang代码向Java端重写
  - 维护一个小的内部使用管理系统，前端使用react进行简单开发，后端使用SpringBoot

---

## 开源项目

### [zinx🔗](https://github.com/polarisink/zinx)

- About Based on Golang Lightweight TCP Concurrent server framework

### [cloud-disk🔗](https://github.com/polarisink/cloud-disk)

- One based on Ali Cloud OSS, using Golang written cloud-disk application back-end

---

## 其他技能

- 摄影爱好者，有运营自己的账号
- 5km、半马爱好者

## 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事！
      