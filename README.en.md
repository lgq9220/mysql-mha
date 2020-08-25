# mysql-mha

#### Description
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



#### Software Architecture
Software architecture description

#### Installation

1.  xxxx
2.  xxxx
3.  xxxx

#### Instructions

1.  xxxx
2.  xxxx
3.  xxxx

#### Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


#### Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
