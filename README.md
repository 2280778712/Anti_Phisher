## ”华为杯“第一届中国研究生网络安全创新大赛全国三等奖项目介绍、演示视频及证书<br>

`Flask` `Vue` `Python` `SQLite`<br>

<hr style="height:2px;border:none;border-top:2px dotted #185598;" />

<div align=center><img style="height:300px;width:300px;" src="https://github.com/2280778712/Anti_Phisher/assets/40905976/81a0297b-e159-4584-a31c-8adc09f1d30b"></div>

# Anti_Phisher

基于国内目前缺少公开钓鱼网站检测平台，检测方法仅停留在理论阶段的现状，本团队开发了一款具有自主高效检测钓鱼网站的平台。不仅能够为普通民众提供钓鱼网站检测服务，本平台还对安全专业人员提供相关服务，例如提供平台检测的钓鱼网站历史数据、检测api、钓鱼url解析以及钓鱼网站热点统计等功能。<br>

我们想分别从检测模块、信息服务模块以及用户模块进行介绍：<br>
<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/107e87c6-cb39-4f36-aca8-c3108a953f26"></div>

<div align=center>钓鱼URL检测模块实现原理图</div>

<br>

- 检测模块：<br>

钓鱼url检测为平台的核心功能，我们结合了**黑名单检测**以及**基于深度学习的检测方法**构成双重检测。对于黑名单检测，我们提取了三个活跃的钓鱼网站黑名单，并进行每日后台更新以维持黑名单检测的有效性。除此之外，我们提出了基于url功能区分割的钓鱼网站检测方法，相较于传统的对URL整体进行字符序列特征提取方式预测准确率以及召回率均有一定的提升。<br>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/97b4c6a2-d4c2-4d96-8be0-862a5171fd37"></div>
<div align=center>钓鱼URL检测模块实现原理图-1</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/87a683f0-8b0b-4ca1-89ec-92ed681b82d7"></div>
<div align=center>钓鱼URL检测模块实现原理图-2</div>

 - 信息服务模块：<br>

除了针对普通民众提供钓鱼url检测服务外，我们试图为相关网络安全研究人员、部分知名网站提供信息收集和统计服务。针对相关网络安全研究人员，我们提供了本平台的**钓鱼网站数据下载服务**、**钓鱼url常见特征解析服务**、**快速检测api**、以及**钓鱼url趋势统计分析报告**。针对知名企业，我们对钓鱼网站数据进行分析，统计各大企业的**受攻击次数**及对应的**钓鱼url**以期能够提升企业对应网站的安全意识。
<div align=center><img src=""></div>
<div align=center>钓鱼URL检测模块实现原理图-1</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/5fcbf568-7c72-462a-b33a-8316852c195f"></div>
<div align=center>数据集下载模块-1</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/07ebf02d-bea3-4f97-b8ea-7a324b544751"></div>
<div align=center>数据集下载模块-2</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/4d1c7d66-f860-4f2e-b089-d17460a773f4"></div>
<div align=center>数据集下载模块-3</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/086d4f14-b842-4542-97a4-3a14109fecc8"></div>
<div align=center>热点统计模块</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/2e552002-fe8b-45ab-8e6d-da9a971ffd08"></div>
<div align=center>钓鱼特征解析模块</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/24ffff84-011d-468d-a5dc-91a275f0dbd1"></div>
<div align=center>检测API公开模块</div>

 - 用户模块：<br>

仅凭技术手段是无法100%检测出所有钓鱼网站的，我们需要更多用户参与到检测中来，共同对抗钓鱼网站。针对每个钓鱼网站的检测查询，我们**在检测结果页面均设立了评论区和验证区**，用户**注册登陆**后便可以对平台的检测结果进行表示支持或者不支持以及评论。用户登录后能够在**后台维护自身信息，查看历史检测记录、评论记录、Api key(只有使用api key才能够调用平台提供的接口信息)等**。

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/625b6b09-bbb8-4431-a4aa-d4d4e50a8e4c"></div>
<div align=center>社区交流模块-1</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/5f149e2f-786c-4bf4-b0c1-82d1a189fc66"></div>
<div align=center>社区交流模块-2</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/fa1364fe-756f-4016-a1af-b4bc5e7df0b0"></div>
<div align=center>社区交流模块-3</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/a0af58f4-8c50-454a-9e79-67710d52eca6"></div>
<div align=center>社区交流模块-4</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/16030965-e292-4af7-abb3-14025cae938c"></div>
<div align=center>社区交流模块-5</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/04481841-8b1f-4984-9c42-829b1914b64f"></div>
<div align=center>社区交流模块-6</div>

<div align=center><img src="https://github.com/2280778712/Anti_Phisher/assets/40905976/ab10caf6-a9d9-489e-8a09-3cfca4e160a4"></div>
<div align=center>用户还可以查询以往查询的记录。</div>
