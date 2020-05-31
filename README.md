# Dango-Translator —— 团子翻译器
+ 目前最新版本：Ver3.4（更新时间2020.05.29）
+ 联系方式：QQ 394883561 —— Email 394883561@qq.com
+ 演示视频：https://www.bilibili.com/video/BV1gp4y1Q7Ts?from=search&seid=2515920591076249883
+ 百度盘下载：https://pan.baidu.com/s/1AD9JWSAKS69gOawwvMXXQw
+ 提取码：975h
+ 解压密码：Dango

### 交流QQ群：（获取最新版本、翻译器交流、解惑）  
①群：779594427【满】  
②群：1038904947【满】  
③群：1048646110【满】  
④群：939840254【满】  
⑤群：905382640【满】  
⑥群：434137389【满】  
⑦群：766694205【满】  
⑧群：1064777983【满】  
⑨群：1077282468【满】  
⑩群：1050705995【满】  
⑪群：835628840【可加】

### 更新内容（相比较上一个版本）：
#### 更新时间：2020-05-29
#### 新增的地方：
+ 点击翻译界面的最小化后，翻译器会隐藏至右下角系统托盘；
+ 加入了程序启动音（Dango~）；

#### 功能优化的地方：
+ 大大优化了翻译速度，多开翻译源时采用并行翻译；
+ 说明：假如你同时开了腾讯0.7s+百度1.1s+彩云0.8s，老版本需要2.6秒才会出翻译，新版本会在0.7秒先打印出腾讯翻译，1.1秒打印完全部翻译。3.4版本可同时打开所有翻译源，整体翻译时间约2s左右；
+ 翻译的时候，会根据文字内容，自动调整翻译框的大小，总之每次都会完整得显示完所有翻译的结果；
+ 点击保存设置后，提示成功的弹窗现在优先级会高于翻译框，解决了之前被挡住点不到的问题；
+ 高精度和竖排模式用光额度后现在会给出准确的提示；
+ 修复了某些高缩放比例的屏幕下会导致点击不到设置页面的保存按键的问题；
+ 更换背景图片现在会自动根据翻译界面的尺寸自动缩放和适配；

#### bug修复的地方：
+ 修复了3.3版本翻译有时候会消失的问题；
+ 修复了频繁弹出ocr代理错误的问题；
+ 修复了点击充电按钮时，会自动关闭翻译界面的bug；
<br/>

#### 和其他翻译软件比较有什么优缺点：
+ 适用范围全面，几乎所有出现在屏幕的东西都可以翻译；
+ 翻译接口多，目前有12个翻译接口；
+ 简洁美观的界面；
+ 及其简单傻瓜的操作方式；
+ 相比较其他OCR翻译器配置有自动翻译模式；
+ 需要联网，可能视网速不同翻译速度有差；

<br/>

### 效果截图：
#### 翻译界面：
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/1.png)

#### 翻译效果（翻译源为彩云小泽）：
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/2.png)

#### 设置-API设定：    
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/3.png)

#### 设置-翻译源：  
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/4.png)

#### 设置-翻译样式：  
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/5.png)

#### 设置-其他设定：  
![](https://github.com/PantsuDango/Dango-Translator/blob/master/git_image/Ver3.3/6.png)

<br/>

### 为什么想制作这个：
本身是个vnr翻译软件的忠实用户，但是遇到某些游戏无法提取文本，并且没有找到有热心人公开发布的特殊码，于是某天研究如何提取特殊码研究到了深夜还是失败了。然后发现有OCR（文字识别）技术的存在，下载了很多已经有的OCR翻译器，但是使用体验都觉得很不方便，于是萌生了自己制作一个自己喜欢的翻译器的想法

<br/>

### 简单地说明：
+ 原理：该软件为OCR翻译器，OCR利用了百度AI的文字识别，原理为通过识别图片上的外文文字并进行翻译；
+ 适用范围：包括但不限于，galgame、rpg游戏、模拟器游戏、外文视频、网页游戏、pdf图片版文献等等，一切能显示在电脑屏幕上的文字；
+ 翻译接口：百度、腾讯、彩云、google等等共12个翻译源；
+ 译文语种：日语、英语、韩文（会考虑加入其它的，但是目前必要性不大）；
+ 其它详细情况参见软件版内配置的使用教程；

<br/>

### 功能流程：
+ 通过截图的方式获取需要翻译的屏幕区域坐标；
+ 通过坐标截图（可自动），并发送至百度AI的文字识别接口；
+ 获取识别好的文字后发送给百度、腾讯、彩云等翻译接口；
+ 结果反馈至GUI界面；

<br/>

### 功能比较多，还请自行下载体会 ヾ(๑╹◡╹)ﾉ"

<br/>
