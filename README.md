# mqDemo
 ActiveMQ Demo
 
## 启动MQ

从 http://activemq.apache.org/download.html下载MQ的最新版本，本教程使用版本为5.5。
解压后，可以看到MQ目录下有以下文件和目录

activemq-all-5.5.0.jar:所有MQ JAR包的集合，用于用户系统调用
bin:其中包含MQ的启动脚本
conf:包含MQ的所有配置文件
data:日志文件及持久性消息数据
example:MQ的示例
lib:MQ运行所需的所有Lib
webapps:MQ的Web控制台及一些相关的DEMO

启动MQ：
双击bin目录下的activemq.bat文件即可启动MQ

## 启动MQ
先运行Consumer.java, 输入参数ORCL，然后运行Publisher.java，输入参数ORCL，
就可以看到Publisher在发送消息，Consumer在接收消息了。
