 <center>
     <h1>王兴龙</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13576149791
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             1941779441@qq.com
         </span>
         ·
     </div>
 </center>



 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男，1997 年出生
 - 求职意向：Java 后台实习，可实习六个月

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士，吉林大学，计算机技术专业，2019.7~2022.7
- 学士，东华理工大学，计算机科学与技术专业，2015.9~2019.7
- 通过了 CET4/6，成绩均500+
- 曾获江西省计算机赛三等奖，研究生第一学年奖学金

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **SpringBoot商城秒杀项目**

  *项目介绍*：本项目是由SpringBoot+RabbitMQ+Redis+MySQL搭建，实现了用户登录、注销、商品列表、详情页面展示、秒杀商品异步下单、订单详情展示功能。

  *项目技术*：

  1. 用户登录部分采用了分布式Session、明文密码两次MD5处理，JSR303自定义参数校验等技术。
  2. 通过采用用户手机号+商品id联合主键的方式保证用户一次只能秒杀同一件商品。
  3. 采用Redis进行页面缓存、存储热点数据、 提前把商品的库存加载到Redis中后进行预减库存等操作。
  4. 使用RabbitMQ队列缓冲，消息队列异步下单逐级削减对数据库的访问，提高用户体验。
  5. 图形验证码、对秒杀接口地址进行加盐值隐藏，采用拦截器进行接口防刷，多种安全机制以拒绝机器人进行恶意访问。

- **仿知乎类资讯网站**

  *项目介绍*：本项目是由SpringBoot搭建后端，数据库使用MySQL和Redis，实现了注册登录、点赞踩赞、关注、评论站内信、Timeline事件流等功能，同时通过一个异步消息框架来实现事件的异步处理。

  *项目技术*：
  
  1. 利用salt及md5加密算法对用户登录密码进行安全性加密，提升了系统安全性。
  2. 通过AOP设置权限校验拦截器，在拦截器中通过ThreadLocal类封装请求用户的身份信息，降低了后续开发成本。
  3. 发表问题功能， 发布问题时检查标题和内容，防止xss注入，并且建立一个字典树，读取一份保存敏感词的文本文件，对敏感词识别过滤。 
  4. 利用Redis实现了一个异步消息队列框架， 有些不需要实时执行的操作或者任务，把它们改造成异步消息来进行发送。如点赞和踩赞，关注用户和问题、粉丝列表之后需要执行的通知功能。
  5. 使用推拉模式实现了TimeLine流，即对活跃的用户采用推模式，对不活跃用户采用拉模式，大大缓解了后端的压力。
  6. 使用Python中的Pyspider框架爬取V2ex论坛数据，再插入进后台数据库问题表中，以填充首页数据。

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 熟悉Java内存模型以及垃圾回收策略，熟悉Java多线程与锁的概念
- 熟悉Mysql，熟悉Mysql的增删改查，熟悉索引机制，了解sql的优化
- 熟悉使用Spring、SpringBoot、Mybatis，熟悉这三种框架之间的集成使用
- 熟悉基本设计模式，例如单例模式、代理模式、适配器模式、工厂模式等
- 熟悉基本数据结构与算法
- 熟悉计算机网络与操作系统等相关知识
- 了解Redis 的基本使用
- 了解Linux常用命令操作
- 了解并会使用Spring cloud分布式框架的搭建集成