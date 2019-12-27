# barrier-free

# 项目名称：无碍问答APP

### 所有人：陈淑铧


# 产品定位

本产品是为视障患者提供问答服务的平台，视障用户可以在此平台上分享着彼此的知识、经验和见解。

# 价值宣言

本产品旨在通过运用人工智能的部分功能（阿里云-智能语音交互-语音合成API）来实现更好的内容交互的效果。

# 价值主张

**一句话** 让视障人士可以扩大社交圈和获取消息的渠道。

**一分钟** 无碍问答APP的价值主张就是让视障人士在使用互联网时，在任何情况下都能平等地、方便地、无障碍的获取信息、利用信息。我们通过利用阿里云的语音合成API功能，为视障人士打造一个可以尽情畅快交流的问答社区。市面上的软件，不是所有的软件都可以和安卓系统的talkback，iOS系统的voiceove功能衔接。而且这个软件不仅仅是为视障人士开发，无视障人士也可以正常使用。我们不会因为某个软件没有无碍化功能，而失去这部分的用户。最终可以达成就是，视障人士和非视障人士都可以在APP内对任何事物进行讨论，前提是讨论的内容符合法律法规。视障者在使用这个APP的时候，通过长按屏幕，向上，向左或者向右“确定”朗读。在语音合成API功能中，用户向下滑动即可退出朗读。

# 用户痛点

- 针对性：

视障人士在使用软件时因为视力障碍导致导致不能看到文字，最好的办法是帮助他们从听力上接触到内容。

- 便捷性：

有的手机有TalkBack功能，这个功能用在华为P10或P10 Plus上时，则意味着手指点到触摸屏的哪个位置，手机语音会提示你，这个位置对应的是什么按钮，方便视力不好的用户来使用手机。
但是打开软件之后，如果该软件没有无碍化模式，那么对视障者来说，这个软件没有意义。

# 用户需求

- 显性需求

1、让视障用户也可以使用网络问答社区软件

2、解决视障人士看不到文字的问题

- 隐形需求

1、使视障人士围绕着某一感兴趣的话题进行相关的讨论，同时可以关注兴趣一致的人。

# 最小完成项

阿里云-智能语音交互-语音合成api：语音合成服务，通过先进的深度学习技术，将文本转换成自然流畅的语音。

# 产品原型

**产品架构**

![产品架构](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E4%BA%A7%E5%93%81%E6%9E%B6%E6%9E%84.png)

**首页**

![首页](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E9%A6%96%E9%A1%B5.png)

**添加问题**

![添加问题](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E6%B7%BB%E5%8A%A0%E9%97%AE%E9%A2%98.png)

**通知**

![通知页](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E9%80%9A%E7%9F%A5%E9%A1%B5.png)

**我的**

![我的](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E6%88%91%E7%9A%84.png)

**语音合成api使用**

![长按屏幕选择文字](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E9%95%BF%E6%8C%89.png)

![确定，识别，朗读](https://gitee.com/NFUNM008/sugwa_first_job_haha/raw/master/%E8%AF%86%E5%88%AB.png)

# 本产品主要运用的AI功能如下：

[阿里云-智能语音交互-语音合成API](https://ai.aliyun.com/nls/tts?spm=5176.233916.1243091.10.1cbd18f07Hl4FU)


# 人工智能概率性

- 语音合成API

用户使用语音合成的过程中，如果选择的文字范围不够精准，就不能正确识别出要语音播报的内容，这个容错率要在5%以内才能满足用户的基本需求。这种概率被用户接收的最低标准是在使用这个功能时正确识别文字并且将其转换为语音。能够超出用户预期的标准是用户选择的文字被识别后读出来时用户可以打断。这些判断决定对产品研发的投入策略：产品研发时要考虑到产品识别的错误率。


# 产品架构

![期末架构](https://gitee.com/NFUNM008/what/raw/master/%E6%9C%9F%E6%9C%AB%E6%9E%B6%E6%9E%84.png)

# API调用展示

- 语音服务

![语音合成](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90.png)


# API的使用价格

**语音合成价格**

![语音合成价格1](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%B7%E6%A0%BC1.png)

![语音合成价格2](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%B7%E6%A0%BC2.png)

# 目标用户
视障人士

# 内容范围

**语音合成**

通过将文字转成流畅动听的自然语言声音，使得视障人士可以用听觉代替视觉。


# 市场

国内现在进行无障碍化改造的APP大概有40多个，且没有一个是无碍化的问答社区类型的APP，对于视障者来说，这是远远不够的。

# 运营

**前期推广** 通过线上线下投放广告，吸纳视障人士，可向特殊教育学校、公众号“帮帮盲视障人士服务中心”宣传。

**后期运营**  用户进入稳定期后，我们可以根据不同需求再做进一步的无碍化改造。

# 清单

## 本产品用到的API代码如下


**语音合成API代码**

![语音合成代码1](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%A3%E7%A0%811.png)

![语音合成代码2](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%A3%E7%A0%812.png)

![语音合成代码3](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%A3%E7%A0%813.png)

![语音合成代码4](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%A3%E7%A0%814.png)

![语音合成代码5](https://gitee.com/NFUNM008/what/raw/master/%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90%E4%BB%A3%E7%A0%815.png)
