# mysql-mha

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



#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
