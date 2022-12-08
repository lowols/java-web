
## 学习目标：
1. 使用idea创建并发布一个java web项目
2. servlet初体验
3. 手撕一个Spring MVC框架，体验一个框架一步一步进化的过程及其设计指导思想

idea 打开一个项目步骤
1. Settings里指定Maven，版本不合适的Maven会导致依赖发现失败
2. Project Structure里，指定sdk，language level

idea 创建并运行一个web模块
1. 创建一个web模块
2. 添加sevelet库依赖，在Project Structure里添加tomcat的sevelet-api.jar 依赖,或者添加tomcat库依赖
3. 创建一个artifact
5. add a run configuration ，attach tomcat
6. 在Deploy选项卡下，选上建好的artifact

导入现有的模块到当前项目
拷贝至当前项目目录下，Project Structure->Import Module
注：如果web文件夹没有蓝色方块，需要到Project Structure里面添加Facets->web
