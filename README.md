##	oasys(OA自动化办公系统)
 办公自动化（OA）是面向组织的日常运作和管理，员工及管理者使用频率最高的应用系统，极大提高公司的办公效率。




###	1.项目介绍
oasys是一个OA办公自动化系统，使用Maven进行项目管理，基于springboot框架开发的项目，mysql底层数据库，前端采用freemarker模板引擎，Bootstrap作为前端UI框架，集成了jpa、mybatis等框架。作为初学springboot的同学是一个很不错的项目，如果想在此基础上面进行OA的增强，也是一个不错的方案。
### 2.框架介绍
#### 项目结构
![项目结构](https://images.gitee.com/uploads/images/2018/0926/164310_e781580c_1277461.png "项目结构目录.png")
#### 前端

| 技术      |    名称| 版本|	官网|
| :--------: | :--------:| :--: |:--:|
| freemarker|模板引擎|springboot1.5.6.RELEASE集成版本|https://freemarker.apache.org/|
| Bootstrap|前端UI框架|3.3.7|http://www.bootcss.com/|
| Jquery|快速的JavaScript框架|1.11.3|https://jquery.com/|
|kindeditor|HTML可视化编辑器|4.1.10|http://kindeditor.net|
|My97 DatePicker|时间选择器|4.8 Beta4|http://www.my97.net/|

#### 后端

| 技术 | 名称 | 版本 | 官网 |
| :--------: | :--------:|:---:|:------:|
|SpringBoot|SpringBoot框架|1.5.6.RELEASE|https://spring.io/projects/spring-boot|
|JPA|spring-data-jpa|1.5.6.RELEASE|https://projects.spring.io/spring-data-jpa|
|Mybatis|Mybatis框架|1.3.0|http://www.mybatis.org/mybatis-3|
|fastjson|json解析包|1.2.36|https://github.com/alibaba/fastjson|
|pagehelper|Mybatis分页插件|1.0.0|https://pagehelper.github.io|

### 3.部署流程

	    1.下载项目、把oasys.sql(原tr18lx.sql)导入本地数据库
		2. 修改application.properties，
		3. 修改数据源，oasys——>自己本地的库名，用户名和密码修改成自己的
		4. 修改相关路径，配置图片路径、文件路径、附件路径
		5. OasysApplication.java中的main方法运行，控制台没有报错信息，数据启动时间多久即运行成功
		6. 在浏览器中输入localhost:8088/logins
		
### 4. 演示地址

#####     演示地址链接：http://125.91.33.25:8989
#####     账号：admin      密码：123456
#####     账号：soli      密码：123456

<!-- ps:有问题可以反馈 -->

如果对项目感兴趣，请Watch、Star项目

<!-- ### 5.友链

1. ##### AgileBPM 敏捷工作流开发平台 https://gitee.com/agile-bpm/agile-bpm-basic
    ###### 后续OA系统流程模块将采用该工作流
    企业级流程解决方案， 前后端分离，模块化，超低耦合。 基于activiti5.22，零java代码即可做到复杂业务的流程实现


2. ##### Spring boot2 脚手架项目V1.x https://gitee.com/bdj/SpringBoot_v2
    ###### 该项目会进行模块化改造、前后端分离、与 AgileBPM 底层 API 一致化改造，也会适时会增加一些新的可选模块（如组织架构） 
    AgileBPM 的相关组件可以自由依附于该软件，并基于该 springboot 应用起步软件为基础不断 构建更多应用组件 -->


###  6.项目截图

![演示1.gif](https://images.gitee.com/uploads/images/2019/0927/141250_aeec4d38_1277461.gif)
![演示4.gif](https://i.loli.net/2018/09/26/5bab4565b121e.gif)
![演示3.gif](https://images.gitee.com/uploads/images/2019/0927/141251_4ef0327c_1277461.gif)

![主页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_2286d104_1277461.png)
![登陆页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_f5277aa8_1277461.png)
![文件管理.png](https://images.gitee.com/uploads/images/2019/0927/141250_491ce25d_1277461.png)
![讨论区.png](https://images.gitee.com/uploads/images/2019/0927/141251_d4992cd4_1277461.png)
![新建流程.png](https://images.gitee.com/uploads/images/2019/0927/141251_c7d89853_1277461.png)
![通讯录.png](https://images.gitee.com/uploads/images/2019/0927/141251_bcf9cbda_1277461.png)
java -noverify -Dspring.output.ansi.enabled=always   :/Users/x99mac/.m2/repository/org/springframework/spring-tx/4.3.10.RELEASE/spring-tx-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/spring-beans/4.3.10.RELEASE/spring-beans-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar:/Users/x99mac/.m2/repository/org/slf4j/jcl-over-slf4j/1.7.25/jcl-over-slf4j-1.7.25.jar:/Users/x99mac/.m2/repository/org/springframework/spring-aspects/4.3.10.RELEASE/spring-aspects-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-starter-freemarker/1.5.6.RELEASE/spring-boot-starter-freemarker-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/freemarker/freemarker/2.3.26-incubating/freemarker-2.3.26-incubating.jar:/Users/x99mac/.m2/repository/org/springframework/spring-context-support/4.3.10.RELEASE/spring-context-support-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/eu/bitwalker/UserAgentUtils/1.20/UserAgentUtils-1.20.jar:/Users/x99mac/.m2/repository/com/github/stuxuhai/jpinyin/1.1.8/jpinyin-1.1.8.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-starter-mail/1.5.6.RELEASE/spring-boot-starter-mail-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/spring-context/4.3.10.RELEASE/spring-context-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/spring-expression/4.3.10.RELEASE/spring-expression-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/com/sun/mail/javax.mail/1.5.6/javax.mail-1.5.6.jar:/Users/x99mac/.m2/repository/javax/activation/activation/1.1/activation-1.1.jar:/Users/x99mac/.m2/repository/org/mybatis/spring/boot/mybatis-spring-boot-starter/1.3.0/mybatis-spring-boot-starter-1.3.0.jar:/Users/x99mac/.m2/repository/org/mybatis/spring/boot/mybatis-spring-boot-autoconfigure/1.3.0/mybatis-spring-boot-autoconfigure-1.3.0.jar:/Users/x99mac/.m2/repository/org/mybatis/mybatis/3.4.4/mybatis-3.4.4.jar:/Users/x99mac/.m2/repository/org/mybatis/mybatis-spring/1.3.1/mybatis-spring-1.3.1.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-starter-web/1.5.6.RELEASE/spring-boot-starter-web-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-starter-tomcat/1.5.6.RELEASE/spring-boot-starter-tomcat-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/apache/tomcat/embed/tomcat-embed-core/8.5.16/tomcat-embed-core-8.5.16.jar:/Users/x99mac/.m2/repository/org/apache/tomcat/embed/tomcat-embed-el/8.5.16/tomcat-embed-el-8.5.16.jar:/Users/x99mac/.m2/repository/org/apache/tomcat/embed/tomcat-embed-websocket/8.5.16/tomcat-embed-websocket-8.5.16.jar:/Users/x99mac/.m2/repository/org/hibernate/hibernate-validator/5.3.5.Final/hibernate-validator-5.3.5.Final.jar:/Users/x99mac/.m2/repository/javax/validation/validation-api/1.1.0.Final/validation-api-1.1.0.Final.jar:/Users/x99mac/.m2/repository/com/fasterxml/classmate/1.3.3/classmate-1.3.3.jar:/Users/x99mac/.m2/repository/com/fasterxml/jackson/core/jackson-databind/2.8.9/jackson-databind-2.8.9.jar:/Users/x99mac/.m2/repository/com/fasterxml/jackson/core/jackson-annotations/2.8.0/jackson-annotations-2.8.0.jar:/Users/x99mac/.m2/repository/com/fasterxml/jackson/core/jackson-core/2.8.9/jackson-core-2.8.9.jar:/Users/x99mac/.m2/repository/org/springframework/spring-web/4.3.10.RELEASE/spring-web-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/spring-webmvc/4.3.10.RELEASE/spring-webmvc-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/mysql/mysql-connector-java/5.1.43/mysql-connector-java-5.1.43.jar:/Users/x99mac/.m2/repository/org/springframework/spring-core/4.3.10.RELEASE/spring-core-4.3.10.RELEASE.jar:/Users/x99mac/.m2/repository/com/github/pagehelper/pagehelper-spring-boot-starter/1.0.0/pagehelper-spring-boot-starter-1.0.0.jar:/Users/x99mac/.m2/repository/com/github/pagehelper/pagehelper-spring-boot-autoconfigure/1.0.0/pagehelper-spring-boot-autoconfigure-1.0.0.jar:/Users/x99mac/.m2/repository/com/github/pagehelper/pagehelper/5.0.0/pagehelper-5.0.0.jar:/Users/x99mac/.m2/repository/com/github/jsqlparser/jsqlparser/0.9.5/jsqlparser-0.9.5.jar:/Users/x99mac/.m2/repository/com/squareup/retrofit2/converter-gson/2.3.0/converter-gson-2.3.0.jar:/Users/x99mac/.m2/repository/com/squareup/retrofit2/retrofit/2.3.0/retrofit-2.3.0.jar:/Users/x99mac/.m2/repository/com/squareup/okhttp3/okhttp/3.8.0/okhttp-3.8.0.jar:/Users/x99mac/.m2/repository/com/squareup/okio/okio/1.13.0/okio-1.13.0.jar:/Users/x99mac/.m2/repository/com/google/code/gson/gson/2.8.1/gson-2.8.1.jar:/Users/x99mac/.m2/repository/com/alibaba/fastjson/1.2.36/fastjson-1.2.36.jar:/Users/x99mac/.m2/repository/org/hibernate/hibernate-jpamodelgen/5.0.12.Final/hibernate-jpamodelgen-5.0.12.Final.jar:/Users/x99mac/.m2/repository/org/jboss/logging/jboss-logging/3.3.1.Final/jboss-logging-3.3.1.Final.jar:/Users/x99mac/.m2/repository/commons-fileupload/commons-fileupload/1.3.2/commons-fileupload-1.3.2.jar:/Users/x99mac/.m2/repository/commons-io/commons-io/2.5/commons-io-2.5.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-devtools/1.5.6.RELEASE/spring-boot-devtools-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot/1.5.6.RELEASE/spring-boot-1.5.6.RELEASE.jar:/Users/x99mac/.m2/repository/org/springframework/boot/spring-boot-autoconfigure/1.5.6.RELEASE/spring-boot-autoconfigure-1.5.6.RELEASE.jar cn.gson.oasys.OasysApplication
