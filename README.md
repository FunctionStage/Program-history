# Program-history

## 1、带着一个问题思考，云计算给编程带来了什么样的变化

## 介绍Serverless，无服务器并不是真的无服务器

   ### 2、Serverless是什么
   * Serverless直译为中文是“无服务器”，但是实际上它仍需要服务器，只不过服务器的管理以及资源分配部分对用户不可见。
   * The phrase “serverless” doesn’t mean servers are no longer involved. It simply means that developers no longer have to think that much about them. [from 'Why The Future Of Software And Apps Is Serverless'](https://readwrite.com/2012/10/15/why-the-future-of-software-and-apps-is-serverless/)
   * Serverless提供的技术基础，从最初的物理服务器进化到虚拟化提供的虚拟机，由虚拟机进化到容器，而Serverless 架构又提供一个比容器更轻量、更简单的环境。
   ### 8、Serverless的特征
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
   ### 2、Serverless的由来
   * 2012 在《Why The Future Of Software And Apps Is Serverless》中第一次出现Serverless，主要在讲Developer在云上不需要关心资源运维
   * 2014 AWS推出AWS Lambda服务，一种对Serverless的全新实现
   * 2015 AWS re:invent CMP302 AWS Lambda and the Serverless Cloud
   * 当前aws,azure,ali,hws,tenent,google,ibm...都提供了函数服务
   * [2018初CNCF Serverless working group发布Serverless whitepaper 1.0](https://github.com/cncf/wg-serverless/tree/master/whitepaper)
   
   

## 编程的历史

  ### 3、回顾计算机的发展及软件伴随着软件开发的变化
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

  ### 4、自身的经历
  * 以自身的亲身经历，讲述传统的IT运维，服务器在身边 -> 松山湖、D2区机房 ->数据中心 -> 应用直接上云；机器资源每年规划两次，提前申购，搬运，安装，调测，维护，经常年节都要下电，上班前一天还要安排值班人员恢复环境。

  ### 5、企业面临的挑战
  * 中小企业公共基础能力的构建成本（比如通过机器学习训练的通过图片库、敏感词汇库。。）；特殊行业面对的成本压力（比如基因企业，需要大量的计算量）
  * IT成本高，资源浪费（“长板理论”，比如提前准备支持双十一流量的机器）
  * 上线时间的要求
  * 更灵活的变更
  * 成本控制（多数企业考虑第一位的是成本而非技术的先进性）
  * 企业IT运维管理压力（加一张aws服务依赖关系图）
  
  ### 6、引出一个问题，如何更好的解决持续增加的企业IT问题呢？
  
  ### 7、想一想，未来的网络是什么样的？
  * 引出ROADS
  * 7.2 引出网络就是一台计算机，引出五朵云
  * 引出云上体验（云桌面、google doc，google book）
  
  ### 8、Serverless应该是云服务提供者提供的一个基础的体验要求
  * 说明Serverless的特征
  
  ### 互联网企业的结构
  
  ### 公有云
  
## 云上编程的畅想
  ### 7.1 网络就是计算机 ROADS体验
  * 实时 RealTime
  * 按需 OnDmand 
  * 实时在线 All Online？？
  * 自助 DIY
  * 社交 Social
  
  ### 7.3 我们自身的云上体验
  * 云桌面，园区各地办公
  * google doc
  * google 笔记本
  
  ### no-Architecture（无架构师）、no-Ops （无运维）
  * 系统架构中最为复杂的扩展性、高可用性、任务调度以及及运维等工作已经由服务提供者代为管理
  
  ### 9、介绍函数服务
  
  ### 11、讲解cloudnative
  
  ### 10、云上基础服务开发者要实时思考提供应用开发者的的体验

  * 线上的应用开发体验
  
  * 线下线上的编程体验
  
  * Lambda带来的一个开发者的编程体验，流水线上只考虑UT即可
  
  ### 12、点题，大家在后面继续思考云计算给开发者带来了怎么样的改变，我们要做什么。
  
## 

#### 参考：
* AWS云计算 https://www.zhihu.com/question/19588115/answer/196359285
* 'Why The Future Of Software And Apps Is Serverless'  https://readwrite.com/2012/10/15/why-the-future-of-software-and-apps-is-serverless/
* Serverless Architectures https://martinfowler.com/articles/serverless.html#InherentDrawbacks

###### 素材
* IBM创始人托马斯·沃森(Thomas J. Watson)当初“全球只需5台计算机
* 但Sun首席技术官格雷格（Greg Papadopoulos）认为，就一主意最终会成为现实。他在自己的博客中写道：世界只需要5 台计算机。
* cloudnative
