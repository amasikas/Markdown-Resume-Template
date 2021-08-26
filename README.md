## <font size=5>毛潇潇</font>

* 性 别：男&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;年 龄：31
* 学 历：本科&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;岗 位：前端开发
* 手 机：18311038973&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;邮 箱：maoxiaoxiao916@outlook.com

## <font size=5>工作及教育经历</font>

__<font size=4>新东方教育集团&emsp;&emsp;&emsp;2021.07~至今</font>__  
__布局未来部&emsp;&emsp;前端开发__
  
  任职前端开发工程师，负责课件制作平台前端研发。

__<font size=4>VIPKID&emsp;&emsp;&emsp;2018.06~2021.07</font>__  
__在线教室/启蒙研发部&emsp;&emsp;前端开发__  
技术栈：react、redux、vue、vuex、vue-router、typescript  
任职前端开发工程师，参与开发互动公开课（互动视频）编辑器；
后担任互动公开课业务研发负责人，挖掘项目当下业务可改进需求点：

  * 重新设计项目架构，提高研发效率、降低对接其他业务课程的后期研发与维护的时间成本；
  * 重构编辑器，统一技术栈，方便搭建公共组件库提高业务后续迭代的开发人效；
  * 梳理课程制作的整个流程，制定新的优化方案，最终该方案对课程制作老师的工作效率至少提升1.6倍；

  公司业务调整后，转为负责超级小班课(1v3直播课)、效果外化视频编辑器、启蒙课程内容管理平台、启蒙增长业务线的前端开发工作。

__<font size=4>和合生活网&emsp;&emsp;&emsp;2016.05~2018.02</font>__  
__研发部&emsp;&emsp;研发经理__  
技术栈：react、redux、django  
合伙创业，负责分销会员系统、积分商城等项目的开发工作。

__<font size=4>创新工场&emsp;&emsp;&emsp;2014.04~2016.03</font>__  
__秘密app团队&emsp;&emsp;前端开发__  
技术栈：jquery、django  
任职前端开发工程师，负责开发秘密pc及hybrid app相关前端页面、活动H5的前后端开发等。

__<font size=4>自主创业&emsp;&emsp;&emsp;2013.07~2014.04</font>__
与研发工作无关

__<font size=4>成都信息工程大学（信息对抗专业-本科）&emsp;&emsp;&emsp;2009.09~2013.07</font>__

## <font size=5>主要项目介绍</font>

__一、互动公开课__

1.架构设计  

* 接手互动公开课业务，针对当前项目存在复用性差以及后期维护成本高等问题，重新设计该业务的前端项目架构。
* 新架构包含基础教室引擎tv-core、组件库tv-armory、上层各业务项目（即各业务课程教室、视频编辑器）三部分。

2.互动视频播放器组件tv-core  
技术栈：vue  

* 互动视频核心组件，支持功能：解析与处理编辑器输出的json文件，播放课程视频，题目通知等。
* 应用项目：互动视频业务教室、互动视频编辑器。

3.互动公开课组件库tv-armory  

技术栈：vue、lerna  

* 支持组件：单选题、判断题、连线题、填空题、语音题、拖拽题、个人信息面板、开课倒计时、得分排行榜等。
* 应用项目：互动视频业务教室、互动视频编辑器、超级小班课。

4.互动视频业务教室

技术栈：vue、vuex、vue-router

* 原互动视频在后台采用ffmpeg进行合成后，存在视频时间戳略微错位的问题，该问题会影响用户互动作答后跳转到的视频时间点与预期视频画面不符，差距在几帧（排查后发现是ffmpeg在对音频流部分进行合成处理时导致的）。后来在优化整个视频制作业务流程时，不再采用该合成方案后顺带解决了此问题。
  
5.互动视频编辑器

技术栈：react、redux、vue、vuex

* 用于编辑生成互动视频，支持视频与题目的增删改、互动视频预览等功能。
* 初期采用react开发，第一版上线后结合团队成员情况以及对新设计的项目架构综合考虑后，带领小组同学用vue进行重构，统一前端技术栈。

6.小组管理

* 统一ESLint采用standard config标准，引入git hook对每次commit的代码进行格式校验。
* 通过commitizen规范git commit的提交信息格式，并按最小功能点改动划分单次commit。
* 前后端协作解耦，调研并接入公司mock api平台。
* 人员配置：2.5前端人力，1.5后端人力

__二、启蒙课程内容管理平台__

技术栈：TypeScript、Vue、Vuex、Vue-Router、Element UI

* 该平台为启蒙课程业务相关的课程配置、资源素材管理、视频制作与审核、游戏资源编辑等内容的管理平台。
* 负责项目的前端技术选型与开发维护工作。

__三、启蒙增长业务相关__

技术栈：Vue、Vue-Router、微信小程序

* 负责钻石兑换裂变活动、转介绍激励活动、转盘抽奖活动、轻课裂变活动、新年盲盒活动、等增长营销类活动H5。
* 搭建活动H5组件库，支持：用户登录组件、地址选择组件、海报分享组件等。
