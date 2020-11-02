#### 本项目包含 Finchley版本 第九篇 的内容

### Quick Start
#### 1.运行 zipkin server的jar包：java -jar zipkin-server-2.10.1-exec.jar
#### 2.访问浏览器 http://localhost:9411  即zipkin的管理页面
#### 3.启动service-hi 和 service-miya这两个服务
#### 4.访问 http://localhost:8988/hi  和 http://localhost:8989/miya
#### 5.查看 zipkin的管理页面，可以看到服务的依赖关系


#### 说明：在spring Cloud为F版本的时候，已经不需要自己构建Zipkin Server了，只需要下载jar即可
