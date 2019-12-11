# 博物馆产品需求文档
|产品的PRD设计|原型设计|机器学习之API的输出入展示
|---------- | --- |---------- 
|[PRD1-加值宣言](#chapter1) |[产品功能架构](#chapter1)|---------- 
|[PRE2-核心价值](#chapter2) |[流程图](#chapter1)|---------- 
|[PRD3-用户痛点宣言](#chapter3) |[全局说明](#chapter1)|----------
|[产品简介](#chapter11) |[原型1.交互及界面设计](#chapter1) |---------- 
|[产品背景](#chapter11) |[原型2.信息设计](#chapter1)|----------
|[产品目标](#chapter11) |[原型3.原型文档](#chapter1)|---------- 
|[用户画像](#chapter11) |[原型4.口头操作说明](#chapter1) |---------- 
|[用户需求](#chapter11) |[Axure交互及设计低保真原型](#chapter1) |---------- 
|[情景假设](#chapter11) | --- |----------
|[PRD4-人工智能概率性与用户痛点](#chapter11) | --- |---------- 
|[PRD5-需求列表与人工智能API加值](#chapter4)| --- |---------- 
|[](#chapter5)| --- |----------

## 产品的PRD设计
<h3 id="chapter1">一、PRD1-加值宣言 </h3>

- 该产品还调用了人流量统计api的价值在于：
> 为残障人士规划和推荐最佳的路线。避免因为拥堵而造成的不便。

- 该产品调用语音合成API的价值在于：
> 为残障人士进行物品介绍进行语音播报，避免因解说文字的距离和高度问题而无法尽情的浏览的烦恼。而且有明确的指导，能快速且准确的到达解决身心需求的区域

- 该产品调用百度API的价值在于：
> 除为残障人士提供智能的游览线路外，还需要提供休息、饮食、洗手间等解决生理需求的区域的导航，减少残障人士因为身体原因以及对展区不熟悉带来的不方便。

<h3 id="chapter1">二、PRD2-核心价值</h3>

- 为残障人士推荐浏览的最佳路线，结合百度地图，在浏览的过程中到达特定区域时，对物品进行语音播报或文本呈现，还提供休息、饮食、洗手间等解决生理需求的区域的导航，减少残障人士因为身体原因以及对展区不熟悉带来的不方便。
- 在观览过程中感到不适或者需要寻求帮助时只需要一键求助.

<h3 id="chapter1">三、PRD3-用户痛点宣言</h3>

- 残障人士参观博物馆时，无法避免因访客多而无法尽情的浏览物品的情况。
- 有时候物品的解说放的位置让残障人士不方便阅读，他们只能观看物品，这样给他们的体验感很差。
- 在寻找解决身心需求的区域总是困难重重，要不不知道在哪，要么不知怎么去。

<h3 id="chapter1">四、产品简介</h3>

- 该产品可以为残障人士提供最的浏览路线，尽量避开人流量较多的区域。
- 该产品提供休息、饮食、洗手间等解决生理需求的区域的导航，减少残障人士因为身体原因以及对展区不熟悉带来的不方便。
- 该产品结合地图，为残障人士就特定区域的物品的介绍进行语音播报或文本呈现；

<h3 id="chapter1">五、产品背景</h3>

- 残障人士是一个特殊的社会群体，他们本身的不便导致于在进行社会活动时困难重重。
- 残障人士一般不想出门游玩的理由就是没有能够规划最佳出行路线的系统或者软件。当他们在游玩或是观赏时，总是存在因为物品的位置和距离导致自己扫兴而归的问题。


<h3 id="chapter1">六、产品目标</h3>

- 为他们在浏览时推荐最佳路线，既能避免人多给他们带来安全隐患，还能让他们尽情的观赏。
- 还提供休息、饮食、洗手间等解决生理需求的区域的导航，减少残障人士因为身体原因以及对展区不熟悉带来的不方便。
- 在观赏的过程提供语音播报或者文本呈现，避免他们因物品解说词的距离和高度的问题而苦恼。
- 在观览过程中感到不适或者需要寻求帮助时只需要一键求助.


<h3 id="chapter1">七、用户画像</h3>

类别 | 详情
---|---
群体 | 残障人士
日常 |  出行游玩、观赏
痛点 | 1、无法最大程度避开人流，尽情的观赏和游玩；2、一些物品的位置和距离让他们无法了解更多。3、在遇到困难时，无法总是第一时间找到工作人员。

<h3 id="chapter1">八、目标用户</h3>

- 残障人士。
> 残障人士：
> - 定义：游由于残损或残疾程度严重，身心功能严重障碍，不但个人生活不能自理，而且影响参加社会生活和工作，“残疾人士”包含“残障人士”，只是“残障人士”专指严重程度的残疾人，生理功能部分或完全丧失。
> - 痛点：生理功能部分或完全丧失,在参观展览的时候可能会出现以下问题，心智障碍，无法理解遵守博物馆相关规定；视觉障碍，无法通过视觉感知博物馆藏品；听觉障碍，无法接受语音信息；哑巴，无法通过语言向展区工作人员寻求帮助，身体障碍，身体移动不方便，无法长时间游览展区。

<h3 id="chapter1">九、用户需求</h3>

- 需要一个智能的路线推荐系统，基于人流量统计的数据，为残障人士智能的推荐游览的最佳路线，避免高峰期发生安全事故的可能，提升残障人士的用户体验。

- 需要可以实时解说物品的功能，避免因位置和高度等问题而带来的困扰。
- 需要有明确的指导，为他们快速且准确的到达解决身心需求的区域。

<h3 id="chapter1">十、情景假设</h3>

|名字|身份|面临的问题|
| ---------- | --- |----------- |
|小刘|身体障碍|因腿不方便所以需要乘坐轮椅，到哪里都需要借助轮椅出行。
|小李|身体障碍|因意外失去双手的小李，无法和正常人一样使用手机，只能进行简单的按钮操作。
|小郑|视力障碍|小郑因视力障碍无法看到细小和距离较远的东西，常常需要放大字号和借助语音播报来辅助自己。


<h3 id="chapter1">十一、PRD4-人工智能概率性与用户痛点</h3>

###### 人工智能概率性
- 目前人类对ImageNet图像的识别错误率大约在5%，微软的人工智能系统的错误率为4.94%，谷歌为4.8%。百度在2015年的时候已将这一错误率进一步降至4.58%，实现了质的飞跃。
- [百度超级计算机图像识别超人类水平 错误率低于微软谷歌](http://tech.ifeng.com/a/20150512/41080218_0.shtml)

###### 用户痛点

- 残障人士参观博物馆时，无法避免因访客多而无法尽情的浏览物品的情况。
- 有时候物品的解说放的位置让残障人士不方便阅读，他们只能观看物品，这样给他们的体验感很差。
- 在寻找解决身心需求的区域总是困难重重，要不不知道在哪，要么不知怎么去。

<h3 id="chapter1">十二、PRD5-需求列表与人工智能API加值</h3>

|优先级|用户需求|功能实现|api加值|
| ---------- | --------- |----------- |-----------|
|重要|推荐游览的最佳路线|智能规划|人流量统计API
|次重要|实时解说物品|语音播报功能|语音合成API
|次重要|有明确的指导，能快速且准确的到达解决身心需求的区域|语音合成API

## 原型设计
<h3 id="chapter14">一、产品架构图</h3>

![产品架构图](img/kuang.png)

<h3 id="chapter15">二、产品流程图</h3>

![产品流程图](img/liu.png)

<h3 id="chapter17">四、Axure原型文档交互展示</h3>

### [原型1.交互及界面设计](http://nfunm104.gitee.io/api_graduation)
### [原型2.信息设计](http://nfunm104.gitee.io/api_graduation)
### 产品原型
### [原型3.原型文档](http://nfunm104.gitee.io/api_graduation)
### [原型下载的地址](https://gitee.com/NFUNM104/API_Graduation)

## API的输出入展示

<h3 id="chapter18">一、API输入与输出</h3>

## API的输出入展示

<h3 id="chapter18">一、API输入与输出</h3>

- 人流量统计api：
> 为残障人士规划和推荐最佳的路线。避免因为拥堵而造成的不便。
##### [详细代码示例](https://github.com/zhengxiaopingzxp/API_ML_PM_museum/blob/master/tongji.ipynb)

该产品调用语音合成API的价值在于：
> 为残障人士进行物品介绍进行语音播报，避免因解说文字的距离和高度问题而无法尽情的浏览的烦恼。而且有明确的指导，能快速且准确的到达解决身心需求的区域
##### [详细代码示例](https://github.com/zhengxiaopingzxp/API_ML_PM_Graduation/blob/master/%E5%9C%B0%E6%A0%87%E8%AF%86%E5%88%AB.ipynb)

<h3 id="chapter19">二、API1.使用水平</h3>

- 输入：现在拍照；输出：大头贴选择
- 输入：本地照片；输出：大头贴选择和编辑
- 输入：故事；输出：详细信息，比如位置、详细说明等

##### [所有代码示例](https://github.com/zhengxiaopingzxp/API_ML_PM_Graduation/blob/master/%E5%9C%B0%E6%A0%87%E8%AF%86%E5%88%AB.ipynb)

<h3 id="chapter20">四、API3.使用后风险报告</h3>

> 百度的地标识别api:
- 有的人所处之地太偏僻，有时候识别不出他（她）的位置。
> 腾讯云的大头贴api：
- 大头贴的样式不是很多，难以满足用户需求。


<h3 id="chapter22">五、API4.加分项</h3>

- 用到的的api有地标识别api、大头贴拍照api、百度地图api
- [所有代码示例](https://github.com/zhengxiaopingzxp/API_ML_PM_Graduation/blob/master/%E5%9C%B0%E6%A0%87%E8%AF%86%E5%88%AB.ipynb)

<h3 id="chapter22">五、API5.最小完成项目</h3>

- 地标识别：
![地标识别.png](https://upload-images.jianshu.io/upload_images/7563229-f6832fc51538093f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




## 最小完成项
- 人流量统计
- 人脸识别
![人脸识别.png](https://upload-images.jianshu.io/upload_images/7563229-3900175fa5537dad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![人脸识别1.png](https://upload-images.jianshu.io/upload_images/7563229-58f8b892077db2c5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![人脸识别2.png](https://upload-images.jianshu.io/upload_images/7563229-ed0b8d64ce57740d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


