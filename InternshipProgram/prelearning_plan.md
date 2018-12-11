# 目标
使实习生在上项目前对QA在项目中的角色定位，职责有一个初步的认识和进行知识储备.

***
标记\*的为需要重点学习了解的知识，推荐所有的实习生都要阅读
<br/>
没有标记\*的, 推荐所有有充足学习时间的实习生学习

***
### 测试对象 - web应用程序
* \* 了解前端基础知识
[html](http://www.w3school.com.cn/html/index.asp)
[css](http://www.w3school.com.cn/css/index.asp)
[js](http://www.w3school.com.cn/js/)
* \* 了解RESTful的含义
[wiki](http://zh.wikipedia.org/wiki/REST)
[入门](http://www.cnblogs.com/shanyou/archive/2012/05/12/2496959.html)
* \* 了解HTTP
[入门](http://www.cnblogs.com/linzheng/archive/2011/01/25/1944914.html)
请熟悉POSTMAN或是http requester的使用，这是要写API level 自动化测试的基础
* 了解构建工具
 1. maven
    [材料1](http://juvenshun.iteye.com/blog/359256)
    [材料2](http://juvenshun.iteye.com/blog/376422)
    [材料3](http://somebody-hjh.iteye.com/blog/726086)
 2. gradle
    [材料1](http://gradle.org/)
    [材料2](http://gradle.org/getting-started-gradle-java/)
* 了解版本控制工具
 1. git
[材料1](http://git-scm.com/book/zh/v2)
[材料2](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
 2. gitflow
[材料1](http://www.ituring.com.cn/article/56870)
[材料2](http://nvie.com/posts/a-successful-git-branching-model/)

***
### 项目开发流程
* \* 敏捷开发 
  * [wiki](https://en.wikipedia.org/wiki/Agile_software_development)  
  * [宣言](http://www.agilemanifesto.org/) 
  * [流程和会议 standup/planning/retro](http://www.cnblogs.com/kkun/archive/2011/07/06/2099253.html)
* \* 了解敏捷实践 
  * [story card flow](http://www.scrumcn.com/agile/scrum/5006.html) 
  * [TDD](http://www.ibm.com/developerworks/cn/linux/l-tdd/)
* \* 持续集成 [wiki](https://en.wikipedia.org/wiki/Continuous_integration)
     * Jenkins 
       * [官网](http://jenkins-ci.org/) 
       * [官方教程](https://wiki.jenkins-ci.org/display/JENKINS/Home)

***
### 敏捷测试 [介绍](http://www.infoq.com/cn/news/2010/12/dn-agile-test-1)
* \* 敏捷项目里的QA
   * [敏捷中的QA](http://www.infoq.com/cn/articles/agility-of-qa/) 
   * [agile tester](http://www.thoughtworks.com/insights/blog/agile-tester-30) 
   * [培训视频](http://v.youku.com/v_show/id_XMjU3MzMzMzQw.html?from=s1.8-1-1.2) 
   * [敏捷测试实践](http://www.ibm.com/developerworks/cn/rational/r-cn-agiletestexplain/index.html?ca=drs) 
   * [be awesome qa](http://www.thoughtworks.com/insights/blog/6-golden-principles-be-awesome-qa)
* \* 敏捷测试四象限 
  * [材料1](http://s10.sinaimg.cn/mw690/001WtR7xgy6Mi5hXCWJe9&690) 
  * [材料2](http://blog.sina.com.cn/s/blog_671c968b0101q3a5.html)

***
### 测试基本概念理论 
* \* [软件测试方法概念汇总](http://blog.jobbole.com/18020/)
* \* [软件测试的7大原则](http://www.testwo.com/article/344)
* 非功能性测试
  * 性能测试 负载测试 压力测试 [概念](http://www.cnitblog.com/xijia0524/archive/2008/09/21/36298.html)
  * 性能测试工具
    * Jmeter [官网](http://jmeter.apache.org/)
    * Gatling [官网](http://www.infoq.com/cn/articles/new-generation-server-testing-tool-gatling/)
  * 安全测试 [渗透测试](http://baike.baidu.com/link?url=DSYiIEWnIX0lroGmgQmVi2Wofjyx0M_S3sADGu0SnwBRMn-OonhGrGA3zygJxU4D5we7y_skkBLcptZps6BFRq)

***
### 测试技术
* \* [测试用例方法](http://www.51testing.com/html/71/n-865171.html)
* \* [等价类,边界值](http://developer.51cto.com/art/201105/261890.htm)
* \* [决定表，因果图](http://developer.51cto.com/art/201105/261893.htm)
* \* [视频 - 如何更好的设计测试用例](http://v.youku.com/v_show/id_XMTI1MzcxMDQ1Ng==.html?from=s1.8-1-1.2)
* \* [探索性测试](http://pan.baidu.com/s/1kTN5Wdp)

***
### 测试建模
* pairwise testing PICT工具的使用 [材料1](http://www.cnblogs.com/liangshi/archive/2010/07/25/1784666.html) [材料2](http://www.infoq.com/cn/news/2011/08/combination-test)
* [HTSM](http://pan.baidu.com/s/1dDJEz1B)

***
### 自动化测试
* \*自动化测试策略金字塔 [材料1](http://martinfowler.com/bliki/TestPyramid.html) [材料2](http://www.51testing.com/attachments/2013/04/346836_201304181047071qDDB.jpg) [材料3](http://s1.sinaimg.cn/bmiddle/632d74e6g771f51d58fe0&690)
* UI测试框架 (\*请选以下其中一个深入了解)
  * [Concordion \(SBE\)](http://concordion.org/)
  * [Cucumber \(BDD\)](https://cucumber.io/)
  * [JBehave](http://jbehave.org/reference/stable/getting-started.html)
* UI测试工具 [Selenium Webdriver](http://seleniumhq.org)
* API 测试框架 
  * [材料1](http://pan.baidu.com/s/1qXy9636)
  * [Rest-assured](https://github.com/jayway/rest-assured)
* 集成测试方法 
  * [pact](https://github.com/realestate-com-au/pact) 
  * [consumerdriverncontranct](http://martinfowler.com/articles/consumerDrivenContracts.html)
* UT 测试框架
  * [Junit](http://junit.org/)

***
### 经典测试书籍PDF推荐
* 软件测试的艺术 [download link](http://pan.baidu.com/s/1hqQZWvM)
* 软件测试的经验与教训 [download link](http://pan.baidu.com/s/1i4bNnql)

***
### 专业测试网站
* testerhome [主页](https://testerhome.com/)
* 测试窝 [主页](http://www.testwo.com/)
