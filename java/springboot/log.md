# springboot日志配置

### lombok 对日志的支持

@slf4j  申明以后可以直接只用 log变量![1543371023772](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1543371023772.png)

###  springboot 默认的logging配置没有滚动策略的支持所以想要很灵活还是需要自定义

#### 正确加载配置文件的名字应该按如下规范

- Logback：logback-spring.xml, logback-spring.groovy, logback.xml, logback.groovy

- Log4j：log4j-spring.properties, log4j-spring.xml, log4j.properties, log4j.xml  

### 详细配置见logback-spring.xml







