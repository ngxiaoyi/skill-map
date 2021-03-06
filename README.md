# StuQ 技能图谱
官网地址：**[http://www.stuq.org/subject/skill-map/](http://www.stuq.org/subject/skill-map/)**（V2.0 产品页面建设中。。。）

## 简介

StuQ 技能图谱是由 StuQ（[http://www.stuq.org/](http://www.stuq.org/)）发起的一个技术社区开源项目，志在汇集整理泛 IT 技术领域（云计算，大数据，运维，安全，开发语言，智能硬件等）及互联网产品、运营等领域学习技能图谱，帮助程序员梳理知识框架结构，并尝试提供路径指导和精华资源，方便技术人学习成长。

目前技能图谱已有下面几个领域：

**技能图谱**（点击预览）| **核心贡献者 ID** | **原创链接** |**路径指导&资源推荐**
------- | ---- | ---- | ---- | 
[**# Web 前端**](https://github.com/TeamStuQ/skill-map/blob/master/data/frontEnd.md)|[@jayli（拔赤）](https://github.com/jayli/)｜阿里巴巴前端资深技术专家|[原创链接](https://github.com/jayli/jayli.github.com/issues/16)|[提交](https://github.com/TeamStuQ/skill-map/issues/9)｜归档
||[@Jackson Tian ](https://github.com/JacksonTian)｜阿里巴巴前端技术工程师|[原创链接](https://github.com/JacksonTian/fks)|
[**# 云计算**](https://github.com/TeamStuQ/skill-map/blob/master/data/cloudComputing.md)|@费良宏｜AWS 首席云计算技术顾问||[提交](https://github.com/TeamStuQ/skill-map/issues/11)｜归档
|- OpenStack|@夏艳｜UnitedStack 公共关系总监||--
[- 容器 Container](https://github.com/TeamStuQ/skill-map/blob/master/data/Container.md)|[@林帆 ](https://github.com/linfan)｜ThoughtWorks DevOps 咨询师||--
[**# 安全**](https://github.com/TeamStuQ/skill-map/blob/master/data/security.md)|[@余弦 ](https://github.com/evilcos) ｜知道创宇技术 VP|[原创链接](http://blog.knownsec.com/Knownsec_RD_Checklist/v3.0.html)|[提交](https://github.com/TeamStuQ/skill-map/issues/13)｜归档
[**# 智能运维**](https://github.com/TeamStuQ/skill-map/blob/master/data/IOAM.md)|[@Tanky Woo ](https://github.com/tankywoo)｜知道创宇资深运维工程师|[原创链接](http://blog.knownsec.com/2015/03/how-many-basic-skills-should-a-operation-and-maintenance-engineer-get/)|[提交](https://github.com/TeamStuQ/skill-map/issues/10)｜归档
[**# 大数据**](https://github.com/TeamStuQ/skill-map/blob/master/data/big-data.md)|[@祝海林 ](https://github.com/allwefantasy)｜乐视云资深大数据工程师||[提交](https://github.com/TeamStuQ/skill-map/issues/12)｜归档
[**# 测试**]()|||||
[- 移动无线测试](https://github.com/TeamStuQ/skill-map/blob/master/data/mobile-wireless-testing.md)|[@陈晔（Monkey）](https://github.com/monkeytest15)｜蚂蚁金服资深测试开发专家||[提交](https://github.com/TeamStuQ/skill-map/issues/15)｜归档
[**# 移动开发**]()|||||
[- iOS 开发](https://github.com/TeamStuQ/skill-map/blob/master/data/mobile-dev-iOS.md)|[@唐巧](https://github.com/tangqiaoboy) ｜猿题库小猿搜题产品技术负责人|[原创链接](https://gist.github.com/tangqiaoboy/5fadd9ba398277680b87)|[提交](https://github.com/TeamStuQ/skill-map/issues/14)｜归档
[**# 智能硬件**]()|||||
[- 嵌入式开发](https://github.com/TeamStuQ/skill-map/blob/master/data/Embedded%EF%BC%8DEngineer.md)|[@Phodal（黄峰达）](https://github.com/phodal) ｜ThoughtWorks 咨询师|[原创链接](https://github.com/phodal/eks)|--
[**# 开发语言**]()|@吴坚 ｜无限极全栈工程师||--
[- Golang](https://github.com/TeamStuQ/skill-map/blob/master/data/dev-lang-Go.md)|[@谢孟军 ](https://github.com/astaxie) ｜Apple 资深技术专家|[原创链接](https://github.com/astaxie/build-web-application-with-golang)|--

以及**正在建设中**的领域：

- 架构师
- 服务端开发
- CTO
- 机器学习
- Hadoop
- 分布式数据库开发
- OpenResty
- Web 性能优化
- IoT 物联网
- Clojure 语言
- Haskell 语言
- Android 开发

欢迎贡献新领域技能图谱，有任何改进意见和建议，请发送邮件至 [stuq@stuq.org](mailto:stuq@stuq.org?subject=StuQ技能图谱)。

## 改进目标

1. 继续细化各领域的技能节点；
2. 提供各领域的参考学习路径；
3. 推荐各知识点相关优质资源；

## 版本信息

### v 0.1.2
云计算领域新增：OpenStack，容器技术；
移动开发领域新增：iOS 开发；
测试领域新增：移动无线测试；
智能硬件领域新增：嵌入式开发；

### v 0.1.1

StuQ 技能图谱第一版发布；

## 加入我们
- QQ群：254521819，加群时请备注姓名+职业。加入后请修改群名片为姓名+职业；
- 微信群：请加StuQ小助手（StuQxiaozhushou）并备注“技能图谱”，小助手会邀请您进群；

## 本地测试与发布

安装node依赖环境；

```
$ cd skill-map
$ npm i --save-dev
```

本地预览；

```
$ npm start
```

发布到git pages作为预览（最终以 StuQ 官网为主）；

```
$ npm run gulp 或 gulp 或 gulp deploy
```

## 许可
本技能图谱遵循 **[CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** 协议。*转载请注明[出处](http://www.stuq.org/subject/skill-map/)。*

最终解释权归 **StuQ** 所有。

