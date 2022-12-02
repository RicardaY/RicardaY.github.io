# YYS_ASSIST 使用文档
## 前言
<b><font color="skyblue">一款基于C++结合MFC开发的阴阳师图色识别助手，模拟人手点击操作，使用大量的随机延迟函数和随机延迟点击，稳定防封。</font></b>
## 准备工作
>1.首先，下载雷电4/5或者mumu模拟器，在模拟器设置中将分辨率设为960*540 160dpi，<font color = "#42b983">若使用mumu模拟器，请在桌面右键mumu模拟器图标->点击属性->点击兼容性->勾选以兼容模式运行->下拉框选择win7->点击应用。</font></br><font color = "#a107a4">注：若电脑是win7系统，需将主题改为Windows经典：桌面右键->个性化->双击Windows经典</font>

>2.下载阴阳师apk:雷电推荐此优化版本 【[点我下载](https://g37.gdl.netease.com/onmyoji_cps_mumu_1.7.46.apk)】，mumu可在模拟器商店自行下载。下载完启动阴阳师，进入游戏界面。</br><font color = "#a107a4">注：游戏内庭院皮肤需使用默认皮或者帝释天皮；若式神委派没领，会有一只红色蝴蝶导致识别不到探索灯笼</font>

>3.助手下载链接：[蓝奏云][点我下载](https://ricarda.lanzouq.com/b01vbp6te)，<font color = "#f00">密码1234</font>打开助手后点击<font color = "#42b983">注册</font>获取试用时长。然后点击<font color = "#42b983">登录</font>，输入刚注册的账密即可。

>4.拖动助手内<font color = "#42b983">绿色句柄图标</font>对准模拟器内部的游戏窗口，待右侧文本框出现模拟器名称即可。

>5.到此，准备工作已完成。
## 使用手册
### 御魂、觉醒等普通副本
>游戏保持在庭院界面，在脚本御魂功能处输入好<font color = "#42b983">次数</font>、选择好<font color = "#42b983">层数</font>、是否开<font color = "#42b983">加成</font>、<font color = "#42b983">身份</font>(单刷|组队受邀|创建队伍)、<font color = "#42b983">邀请方式</font>(最近组队好友  <font color = "#a107a4">固定好友</font>])，然后点击<font color = "#42b983">添加单任务到列表</font>，点击<font color = "#42b983">开始启动</font>即可！<font color = "#42b983">【觉醒、日轮之陨、永生之海、妖气封印、业原火、御灵】</font>设置与御魂相同，可参考御魂设置。</br>

<img src= "img/御魂.png" style="zoom: 80%;"></img></br>
><font color = "#42b983">注：若是三人组队，请勾选三人组队并配合其左侧的固定队友使用。若修改配置，需重新添加到任务列表，并重新启动任务。</font>
### 探索
>探索功能的使用基本与御魂设置相同，可参照御魂设置。</br>注意点：</br>&nbsp;&nbsp;&nbsp;&nbsp;1.自动狗粮后面的百分比默认是5%，意思是在换狗粮界面时，先将下方<font color = "#00f">进度条</font>向右拖动5%，然后再开始识别狗粮，目的是排除前面的一些有等级的狗粮的影响。一般保持默认就行。</br>&nbsp;&nbsp;&nbsp;&nbsp;2.在双开的情况下，若两个号是组队刷探索，且开启了<font color = "#00f">拾取宝箱</font>功能，则需在<font color = "#00f">全局设置</font>里勾选<font color = "#00f">游戏一与游戏二为组队关系</font>，单刷则不用。</br>

<img src= "img/探索.png" style="zoom: 80%;"></img>
### 突破
>突破分为<font color = "#42b983">个人突破</font>和<font color = "#B95EE6">寮突</font>，若选择个人突破，则右侧寮突不生效，反之亦然。</br><font color = "#42b983">个人突破</font>：分为<font color = "#42b983">正常突破</font>与<font color = "#42b983">退四打九</font>(<font color = "#F973BF">解释：卡57级，勋章多、且好打</font>)，根据个人需求选择即可。</br>
<font color = "#B95EE6">寮突</font>：若选择<font color = "#B95EE6">等待冷却</font>：6次用完则会原地等待；若选择<font color = "#B95EE6">不等待冷却</font>，次数用尽会退出寮突，继续任务列表的下一个任务。</br>

<img src= "img/突破.png" style="zoom: 80%;"></img>
### 休息
><font color = "#42b983">休息功能</font>可以配合<font color = "#42b983">定时功能</font>使用，如开启了<font color = "#F98873 ">自动寄养</font>，则会在<font color = "#F98873 ">休息开始前</font>执行(任务列表有多条休息任务时，<font color = "#F98873 ">每次休息前都会检测寄养</font>)，可以通过合理分配休息时间灵活控制寄养。</br>

<img src= "img/休息.png" style="zoom: 80%;"></img></br>
><font color = "#F973BF">举例</font>：定时功能开启了自动寄养，在任务列表添加10条休息60分钟的任务，那么将会先检测一次寄养，然后开始休息，60分钟后会再检测一次寄养，继续第二次休息......，直到10次休息完毕为止。
### 御魂预设
>开启<font color = "#42b983">御魂预设</font>功能后，将会在每次任务开始前进式神录切换队伍的御魂。</br>
<font color = "#42b983">组</font>代表<font color = "#F973BF">右边的分组</font>；<font color = "#42b983">队</font>代表<font color = "#F973BF ">左边的队伍</font>。</br>

<img src= "img/预设.png" style="zoom: 50%;"></img></br>
><font color = "#FF5733">注意：式神录皮肤需设为默认</font>
### 独立功能
待完善......
### 定时功能
待完善......
### 全局设置
待完善......
### 双开
待完善......
### 激活码购买与添加时长
>点击<font color = "#42b983">购买激活码</font>会自动跳转到购买界面，购买后，点击<font color = "#42b983">添加时长</font>会弹出如下界面，输入注册的账号与刚购买的激活码即可添加。</br>

<img src= "img/添加时长.png" style="zoom: 80%;"></img></br>
>也可在此购买：购买链接-[[点我](http://www.sakurayys.com/#shop)]</br>
## API文档
待完善......
## 常见问题
待完善......
## 交流群
<font color="#09dfae" size = "6px"><b>QQ交流群：753472503</b></font>
