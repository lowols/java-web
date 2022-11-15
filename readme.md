
404 ：找不到对应的资源

idea 打开一个项目步骤
1. Settings里指定Maven，版本不合适的Maven会导致依赖发现失败
2. Project Structure里，指定sdk，language level

idea 创建并运行一个web模块
1. 创建一个web模块
2. 添加tomcat的sevelet-api.jar 依赖
3. 创建一个artifact
5. add a run configuration ，attach tomcat
6. 在Deploy选项卡下，选上建好的artifact

导入现有的模块到当前项目
拷贝至当前项目目录下，Project Structure->Import Module
注：如果web文件夹没有蓝色方块，需要到Project Structure里面添加Facets->web
