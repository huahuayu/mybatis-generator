## Mybatis generator命令行运行配置
配置简单，附详细配置说明

## Usage
### step1:克隆项目

### step2:修改配置文件
打开配置文件`generatorConfig.xml`
1. 修改配置文件中jdbcConnection标签的数据库连接参数
2. 修改javaModelGenerator标签的包名
3. 修改table标签的表名和object名

### step3:执行代码生成命令
```
java -jar mybatis-generator-core-1.3.7.jar -configfile generatorConfig.xml -overwrite
```
生成的代码会在`src`目录下