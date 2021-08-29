![](assets/markdown-img-paste-2021082918532916.png)

#### ROS通信架构

master与node

启动ros master

```shell
roscore
```

node为ros中的进程，pkg中运行的实例，以功能划分

```shell
rosrun
rosnode
rosnode list
rosnode info node_name
```

启动master与多个node

```shell
roslaunch
```

#### ROS通信方式

###### Topic通信方式
异步通信方式

调用publish发布topic

调用subscribe接受topic

都可以有多个

###### Topic内容的数据类型——Message

定义在*.msg文件中

基本msg


![](assets/markdown-img-paste-20210829212903309.png)
