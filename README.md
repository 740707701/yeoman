### yeoman angular grunt bower
在安装Yeoman之前，你需要确认以下配置：
  * Node.js 版本在0.10以上
  * npm 版本在1.3.7以上  
```npm install -g yo  ```    
如果你看到了’permission errors’或者’access errors’，你需要在这条命令前面加上’sudo’通过    
可以通过执行以下命令检查是否安装成功    
    ```yo --version && bower --version && grunt --version  ```    
你会看到四个版本号打印出来,就代表安装成功.    
现在执行      
   ``` yo  ```  
根据项目需要选择`true`或`false `,用上下箭头选择安装的生成器        
如果知道生成器的名称,可以直接用npm来安装      
    ``` npm install -g generator-angular  ```    
可以指定版本的生成器      
   ```  npm install -g generator-angular@0.7.0  ```      
使用生成器generator搭建你的应用      
   ```  yo  ```  
   ``` yo angular  ```  
    

