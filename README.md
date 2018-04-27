# dubbo-demo

edu-service-user is  provider
edu-web-boss is consumer
edu-facade-user is facade

1.change jdbc.properties

jdbc.url=jdbc\:mysql\://localhost\:3306/test2?useUnicode\=true&characterEncoding\=utf-8
jdbc.username=root
jdbc.password=111111

2.change server.properties

dubbo.registry.address=10.211.55.52:2181
此处为zookeeper地址，要运行此项目需要依赖zookeeper

3.init mysql

edu-common-parent/doc/SQL/初始化脚本(MYSQL).sql

4.用tomcat启动edu-service-user，在启动edu-web-boss。
