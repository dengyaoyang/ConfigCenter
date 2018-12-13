###  idea 热部署

- 首先在compiler中配置自己动build

  ![1544683544073](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1544683544073.png)

- 然后ctrl+shift+a rigistry里面 选中这些选项

  ![1544683704988](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1544683704988.png)

- 开启IDEA热部署策略

  ![1544683764047](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1544683764047.png)

- 添加热部署插件

  ```java
  <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-devtools</artifactId>
     <scope>runtime</scope>
  </dependency>
  ```

- 关闭游览器缓存

  ![1544683924600](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1544683924600.png)
