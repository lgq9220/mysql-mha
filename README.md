# mysql-mha

#### 视频地址：https://pan.baidu.com/s/1yykMFHoZxP9qiL-h_Tt9vg

#### 视频提取码：bx10

#### 介绍

搭建一个MySQL高可用架构集群环境（4台主机，1主、2从、1 MHA）

首先实现一主两从的同步复制功能（采用半同步复制机制）

然后采用MHA实现主机出故障，从库能自动切换功能

MHA高可用搭建后，在主库新建商品表进行效果测试

在拉勾业务中职位表相当于电商系统的商品表，投递表相当于电商系统的订单表。职位表我们采用垂直拆分方法分为position（职位描述表）和 position_detail（职位详情表），表结构结构如下：

position：id(int)、name(varchar)、salary(varchar)、city(varchar)


position_detail：id(int)、pid(int)、description(text)

作业需要提交集群环境搭建手册和效果演示视频

手册：包含环境软件版本和架构介绍、环境安装过程、操作的问题和注意事项等。

视频：仅录制环境介绍和效果演示。

----------------------------------------------------------------------------

作业资料说明：

1. 1、提供资料：说明文档、验证及讲解视频。

2. 2、讲解内容包含：题目分析、实现思路、环境介绍。

3. 3、说明文档包含：

4. l 环境软件版本、架构介绍

5. l 环境安装过程（各个配置加注释）

6. l 操作过程中遇到的问题

7. l 操作注意事项

8. 4、效果视频验证：

9. l 集群环境

10. \* 4台

11. \* 1主，2从，1MHA

12. 一主两从的半同步复制功能

13. MHA实现主机出故障，从库能自动切换功能

14. l 环境介绍

15.  \* 介绍涉及的各个软件的版本

16.  \* 介绍各个机器对应角色&作用&ip地址

17. l 主库新建商品表

18. l 添加数据，演示半同步复制

19. ​    \* 先查询主从库数据

20. ​    \* 添加后，再次查询主从库数据

21. ​    \* 查看log，是否显示半同步

22. l 主机出故障，从库能自动切换功能

23.   \* 关闭 主服务器，查看MHA服务器是否正常切换

24. App1:mysql Master failower 之前主ip(之前主ip:3306) to 切换后ip(切换后ip:3306) succeeded

25.   \* 在切换后的主节点机器上查看状态展示效果

26.   \* 在切换后的主节点机器数据库添加数据，分别查询主从库数据一致

27. \------------------------------------------------------------------------------------------------------------

28. 

Wed Sep  2 01:53:26 2020 - [info]  mysql-bin.000002:2676