# ssm
springMvc + spring + Mybatis + pageHelper + druid 整合
springMvc + spring + Mybatis + pageHelper + druid 整合
spring 和druid整合，spring 整合druid
spring 和Mybatis 整合，spring 整合Mybatis 
Mybatis 和pageHelper  整合，Mybatis 整合pageHelper 
Mybatis和 druid整合，Mybatis整合druid
Mybatis和 通用Mapper整合，Mybatis通用Mapper
Mybatis整合 通用Dao


本框架整合使用Maven方式构建，Jdk版本为JDK7，各插件版本如下：

<spring.version>4.3.13.RELEASE</spring.version>  
          
<mybatis.version>3.4.6</mybatis.version>  
<mybatis.spring.version>1.3.1</mybatis.spring.version>  
<mybatis.generator.version>1.3.6</mybatis.generator.version>  
<pagehelper.version>5.1.2</pagehelper.version>  
<mybatis.mapper.version>3.5.3</mybatis.mapper.version>  
  
<druid.version>1.1.9</druid.version>  
<mysql.version>5.1.45</mysql.version>  
 
框架内置了Mybatis自动生成Mapper.xml、Java Bean、Dao插件，在Java类：MybatisGenerator中
生成代码直接运行该Java类即可，运行后F5刷新项目，直接生成在项目中，代码生成详细配置见：mybatis-mapper-generator.xml，根据自己需求修改
