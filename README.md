# Program-history

## 带着一个问题思考，云计算给编程带来了什么样的变化

## 介绍Serverless，无服务器并不是真的无服务器

   ### Serverless是什么
   * Serverless直译为中文是“无服务器”，但是实际上它仍需要服务器，只不过服务器的管理以及资源分配部分对用户不可见。
   * The phrase “serverless” doesn’t mean servers are no longer involved. It simply means that developers no longer have to think that much about them. [from 'Why The Future Of Software And Apps Is Serverless'](https://readwrite.com/2012/10/15/why-the-future-of-software-and-apps-is-serverless/)
   * Serverless提供的技术基础，从最初的物理服务器进化到虚拟化提供的虚拟机，由虚拟机进化到容器，而Serverless 架构又提供一个比容器更轻量、更简单的环境。
   * Serverless的服务特征
     * 资源共享，资源对用户不可见
     * 短生命周期
     * 事件触发
     * 无状态
     * 免运维，用户不需要关心服务扩容、负载均衡、可靠性能力
   * Serverless的商业特征
     * 按需付费，不使用不付费
     * 资源利用率提升
     * 开展业务更灵活，上线更快捷
     * IT运维成本的下降
     * ‘节能环保’
   ### Serverless的由来
   * 2012 在《Why The Future Of Software And Apps Is Serverless》中第一次出现Serverless，主要在讲Developer在云上不需要关心资源运维
   * 2014 AWS推出AWS Lambda服务，一种对Serverless的全新实现
   * 2015 AWS re:invent CMP302 AWS Lambda and the Serverless Cloud
   * 当前aws,azure,ali,hws,tenent,google,ibm...都提供了函数服务
   * [2018初CNCF Serverless working group发布Serverless whitepaper 1.0](https://github.com/cncf/wg-serverless/tree/master/whitepaper)
   
   

## 编程的历史

  ### 资源集中，资源共享，大型机
  * 集中式，打孔、磁带，解决数学计算问题（全球5台计算机语言）
    * 20世纪40-50年代，真空管计算机，几十吨
    * 20世纪50年代后，晶体管计算机，几百公斤，产生了高级编程语言Fortran，Cobol
  * 大型机
    * 1965年，出现集成电路，产生C语言
    * 20世纪70年代，超大规模集成电路
    * 单体应用，瀑布
  * PC发展，数据中心  
    * 20世纪80年代以后，个人电脑，服务器，巨型机
    * C/S, B/S
    * CMM，CMMI
  * 互联网，云计算
    * 2000年后，google、facebook、aws
    * 实体机、虚拟化、容器
    * 分布式应用、微服务
    * 敏捷，devops
 
  ### PC小型化

  ### 数据中心
  * 以自身的亲身经历，讲述传统的IT运维，服务器在身边 -> 松山湖、D2区机房 ->数据中心 -> 应用直接上云；机器资源每年规划两次，提前申购，搬运，安装，调测，维护，经常年节都要下电，上班前一天还要安排值班人员恢复环境。

  ### 企业，IT部门的一般结构
  * IT资源的“长板理论”

  ### 互联网企业的结构
  
  ### 公有云
  
## 云上编程的畅想
  ### 网络就是计算机
  
  ### 我们自身的云上体验
  * 云桌面，园区各地办公
  * google doc
  * google 笔记本
  
  ### no-Architecture（无架构师）、no-Ops （无运维）
  * 系统架构中最为复杂的扩展性、高可用性、任务调度以及及运维等工作已经由服务提供者代为管理
  ### 编程体验

  * 线上的应用开发体验
  
  * 线下线上的编程体验
  
  * 流水线上只考虑UT即可
  
## 

#### 参考：
* AWS云计算 https://www.zhihu.com/question/19588115/answer/196359285
* 'Why The Future Of Software And Apps Is Serverless'  https://readwrite.com/2012/10/15/why-the-future-of-software-and-apps-is-serverless/
* Serverless Architectures https://martinfowler.com/articles/serverless.html#InherentDrawbacks

###### 素材
* IBM创始人托马斯·沃森(Thomas J. Watson)当初“全球只需5台计算机
* 但Sun首席技术官格雷格（Greg Papadopoulos）认为，就一主意最终会成为现实。他在自己的博客中写道：世界只需要5 台计算机。
* cloudnative
