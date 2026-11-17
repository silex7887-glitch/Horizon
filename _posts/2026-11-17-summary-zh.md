---
layout: default
title: "Horizon Summary: 2026-11-17 (ZH)"
date: 2026-11-17
lang: zh
---

> 从 141 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [中大港理工等提出免训练长视频压缩方法 V-CAST](#item-tech-news-1) ⭐️ 7.0/10

**国际时事**
1. [塞尔维亚学生名单候选人将宣誓就任议员](#item-world-news-1) ⭐️ 9.0/10
2. [乌克兰称重创连接俄与克里米亚的刻赤大桥](#item-world-news-2) ⭐️ 8.0/10
3. [霍尔木兹海峡油轮据报遭水雷袭击](#item-world-news-3) ⭐️ 8.0/10
4. [乌克兰称俄军“二次打击”致 72 人死亡](#item-world-news-4) ⭐️ 7.0/10
5. [日本因俄机据称侵入领空紧急起飞战机](#item-world-news-5) ⭐️ 7.0/10

**财经新闻**
1. [黄仁勋辞任英伟达 CEO，卢特尼克家族关联再受审视](#item-finance-news-1) ⭐️ 8.0/10
2. [孟加拉国发展势头停滞](#item-finance-news-2) ⭐️ 7.0/10
3. [美国通胀报告凸显食品能源住房成本压力](#item-finance-news-3) ⭐️ 7.0/10
4. [英国失业率小幅回落加剧通胀担忧](#item-finance-news-4) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [中大港理工等提出免训练长视频压缩方法 V-CAST](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&amp;mid=2247944324&amp;idx=3&amp;sn=0ec2b49fbc70dea4c1fc90bbcd164d64) ⭐️ 7.0/10

中山大学、香港理工大学等团队提出免训练、即插即用的视觉 Token 压缩方法 V-CAST，在视觉 Token 送入语言模型前按时空覆盖进行筛选剪枝，并保留原有时空坐标。据团队在 Qwen3-VL、LLaVA 与 Qwen2.5-Omni 共 6 个模型配置、10 个视频及音视频基准上的验证：256 帧长视频评测中平均分领先次优压缩方法 1.5 分；768 帧音视频实验中保留未压缩模型 97.1% 表现，总推理耗时降低 50.0%；在 Qwen3-VL-8B 的 32 帧实验中仅保留 25% 视觉 Token，平均表现仍达原模型的 98.2%。上述效率与保留率数字来自团队投稿报道，属其实验声明而非独立复现结果。

rss · 量子位 · 11月16日 14:07

**「背景」** 视频大模型会把各帧画面编码成视觉 Token 再送入语言模型；帧数增加时，预填充计算与显存开销随之上升，重复背景与动作还会占用大量预算。与此同时，动作排序、计数和事件定位又依赖跨时刻线索，压缩若过度集中在少数画面，就容易漏掉前后变化，因此需要在时间覆盖与帧内细节之间取得平衡。

**「实际影响」** 在已验证的 Qwen3-VL、LLaVA 与 Qwen2.5-Omni 等配置上，长视频或多模态推理的开发者可直接接入免训练的 V-CAST，在将视觉 Token 压至约 25% 的同时，按报告结果把总推理耗时约减半并保留大部分原模型表现，而无需重训或改动模型权重。

**标签**: `#video-llms`, `#token-compression`, `#multimodal-efficiency`, `#long-context`, `#neurips`

---

## 国际时事

<a id="item-world-news-1"></a>
### [塞尔维亚学生名单候选人将宣誓就任议员](https://www.theguardian.com/world/2026/nov/17/serbia-student-list-mps-sworn-in-election-triumph) ⭐️ 9.0/10

塞尔维亚学生名单的 140 名候选人将于周二在新议会首次会议上宣誓就任议员，并开始组阁。该名单在上月选举中击败亚历山大·武契奇领导的塞尔维亚进步党（SNS），结束其 14 年执政；被罢免的武契奇威胁发起大规模抗议。

rss · The Guardian World · 11月17日 05:00

**「此前选举」** 上个月，草根运动“学生名单”在议会选举中击败民粹主义领导人亚历山大·武契奇及其执政 14 年的塞尔维亚进步党（SNS）。

**「影响」** 塞尔维亚结束进步党长达 14 年的执政，由学生名单着手组建新政府。

**标签**: `#Serbia`, `#change of government`, `#elections`, `#Aleksandar Vučić`, `#Student List`

---

<a id="item-world-news-2"></a>
### [乌克兰称重创连接俄与克里米亚的刻赤大桥](https://www.theguardian.com/world/live/2026/nov/17/europe-ukraine-russia-crimea-kerch-bridge-attack-latest-news-updates) ⭐️ 8.0/10

乌克兰称以导弹对连接俄罗斯与克里米亚的刻赤大桥实施打击并造成严重损毁；基辅与莫斯科对损毁程度说法不一。报道称，半岛对外通行目前主要依赖易受无人机攻击的陆上走廊。

rss · The Guardian World · 11月17日 09:15

**「背景」** 刻赤大桥是俄罗斯在 2014 年吞并克里米亚后修建的连接本土与半岛的关键通道，乌克兰视其为非法；此前一天已有一次针对桥拱的袭击。

**「影响」** 克里米亚与俄罗斯之间的通行目前仅能依赖易受乌克兰无人机攻击的陆路走廊，俄方对半岛的补给与人员往来因此受限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theguardian.com/world/2026/nov/16/ukraine-drone-kerch-bridge-russia-occupied-crimea">Ukraine hits Kerch bridge between Russia and occupied Crimea</a></li>
<li><a href="https://edition.cnn.com/2026/11/17/europe/ukraine-russia-kerch-bridge-intl-hnk">Kerch Bridge in Crimea damaged as Russia and Ukraine exchange...</a></li>
<li><a href="https://www.theguardian.com/world/live/2026/nov/17/europe-ukraine-russia-crimea-kerch-bridge-attack-latest-news-updates">Ukraine hails attack on vital Kerch bridge linking... | The Guardian</a></li>

</ul>
</details>

**标签**: `#Ukraine-Russia war`, `#Kerch bridge`, `#Crimea`, `#infrastructure attack`, `#military logistics`

---

<a id="item-world-news-3"></a>
### [霍尔木兹海峡油轮据报遭水雷袭击](https://www.aljazeera.com/news/2026/11/17/tankers-hit-in-strait-of-hormuz-as-drone-raises-alarm-at-iraq-gas-field?traffic_source=rss) ⭐️ 8.0/10

伊朗方面称霍尔木兹海峡有油轮遭水雷袭击；同时伊拉克一处气田出现无人机警报，美国一艘航母抵达，地区紧张局势升温。

rss · Al Jazeera · 11月17日 03:12

**「背景」** 霍尔木兹海峡是波斯湾石油外运的关键水道；伊朗方面称，就在此前一天，该水域已有多艘油轮触碰水雷。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://southfront.press/military-situation-in-iran-on-november-16-2026-map-update/">Military Situation In Iran On November 16, 2026 (Map Update)</a></li>

</ul>
</details>

**标签**: `#Strait of Hormuz`, `#Iran`, `#Iraq`, `#maritime security`, `#US military`

---

<a id="item-world-news-4"></a>
### [乌克兰称俄军“二次打击”致 72 人死亡](https://www.bbc.co.uk/news/articles/c30rk8x5g80qo?at_medium=RSS&amp;at_campaign=rss) ⭐️ 7.0/10

乌克兰官员称，俄罗斯在乌克兰南部发动的“二次打击”（先袭击后再打击救援现场）造成 72 人死亡，且持续空袭仍在阻碍遗体搜救。

rss · BBC World · 11月17日 05:59

**「背景」** 俄乌战争仍在持续；所谓“二次打击”（double-tap）指在首次袭击后，再对赶赴现场的救援人员发动攻击。

**「对平民的影响」** 乌克兰南部平民在此次袭击中据报有 72 人死亡，遗体回收工作因持续打击受阻。

**标签**: `#Ukraine-Russia war`, `#civilian casualties`, `#double-tap strike`, `#southern Ukraine`

---

<a id="item-world-news-5"></a>
### [日本因俄机据称侵入领空紧急起飞战机](https://www.bbc.co.uk/news/articles/c60evw20qe47o?at_medium=RSS&amp;at_campaign=rss) ⭐️ 7.0/10

日本在俄罗斯军机据称侵入其领空后紧急起飞战机应对。台湾和韩国也对在其空域附近被侦测到的俄罗斯军用飞机作出了反应。

rss · BBC World · 11月17日 07:44

**「背景」** 日本在侦测到外国军机接近或进入其领空时，通常会紧急起飞战斗机进行识别与监视。

**标签**: `#Russia`, `#Japan`, `#airspace`, `#military-incident`, `#East-Asia`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [黄仁勋辞任英伟达 CEO，卢特尼克家族关联再受审视](https://www.cnbc.com/2026/11/13/howard-lutnick-nvidia-jensen-huang-china-cantor-fitzgerald.html) ⭐️ 8.0/10

英伟达首席执行官黄仁勋辞职后，美国商务部长霍华德·卢特尼克及其家族与该公司的财务关联再次受到审视。

rss · CNBC Finance · 11月16日 12:14

**「背景」** 英伟达是一家总部位于美国的跨国科技公司，主要开发图形处理器（GPU）及用于人工智能、高性能计算等领域的芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.m.wikipedia.org/wiki/Nvidia">Nvidia - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#Howard Lutnick`, `#CEO resignation`, `#conflict of interest`, `#semiconductors`

---

<a id="item-finance-news-2"></a>
### [孟加拉国发展势头停滞](https://www.economist.com/asia/2026/11/16/bangladesh-is-no-longer-a-development-superstar) ⭐️ 7.0/10

《经济学人》指出，孟加拉国已不再是发展明星，其发展成就陷入停滞，腐败正将其银行推向破产边缘。

rss · The Economist · 11月16日 18:31

**「背景」** 孟加拉国银行业不良贷款已升至约占全部贷款的三分之一以上，并位居全球前列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.daily-sun.com/bank/842604/banking-sector-at-risk-amid-surge-in-non-performing-loans">Banking sector at risk amid surge in non - performing loans</a></li>
<li><a href="https://www.moneycontrol.com/world/bangladesh-tops-global-bad-loan-ranking-as-banking-sector-non-performing-loan-ratio-crosses-32-article-14022139.html">Bangladesh tops global bad loan ranking as banking sector Non ...</a></li>

</ul>
</details>

**标签**: `#Bangladesh`, `#banking-crisis`, `#corruption`, `#emerging-markets`, `#economic-development`

---

<a id="item-finance-news-3"></a>
### [美国通胀报告凸显食品能源住房成本压力](https://news.google.com/rss/articles/CBMi2wFBVV95cUxOVEI0ajRDVk9UaDlyeXZSYVhqSDlXcDlzZGtJcURDM0plUHhkMklBX3E0VXA2bTNpZ0FYaV8wRkRoZW5OQ1VrQUkzSTJZYU1mMUJVV2E0Tjk5NzBzVk9pQlZxMWVqQnkxT002X3c0WXo0SFlUemdOUEVXbXZ2WG1jaUJaY2l2MVFINjBjV2RBQVFTRVVSQ3dCVG5GN1F3V0pjVFlCa3pvZzZTZ3JMdDVYcGZJNTdDVVY4RFpEMGV1U2VMZ1R3VUowSDBWT2hCVGdZR3JYdERwNlRscEk?oc=5) ⭐️ 7.0/10

据 PBS 报道，最新美国通胀报告凸显食品、能源和住房成本持续上升给家庭带来的压力。来源未提供具体通胀读数、统计期或对比基期。

google\_news · PBS · 11月16日 16:40

**「背景」** 美国政府定期发布消费者物价指数（CPI，衡量家庭购买商品与服务价格变动的指标），用以观察食品、能源和住房等生活成本的变化。

**标签**: `#inflation`, `#US economy`, `#consumer prices`, `#cost of living`, `#economic data`

---

<a id="item-finance-news-4"></a>
### [英国失业率小幅回落加剧通胀担忧](https://news.google.com/rss/articles/CBMitAFBVV95cUxOTEl0dEVXWFZSczVQejI3aElaVU40c21IX0wxNVZwNzB0MDdFWG5KY2tOMzBiWWtJVk83UWVONmg2UVg3dVlOMnE4azl3WkhBeTJFSkZBWXpBd2MwYnJUWFBhNllZY1FuTUU4THlTUnR0YzlLV3Z6Z3pXOWs5M3V4U3hGSk5NdFJPSGtQVGVSLWJHaHJacTFqY3p4SFVYZjVoNG5CTnl1RDRrVkthTWc3aTVlN0Q?oc=5) ⭐️ 7.0/10

据《华尔街日报》报道，英国失业率小幅下降，加剧了市场对通胀的担忧。

google\_news · WSJ · 11月17日 07:36

**「背景」** 失业率走低通常意味着劳动力市场更紧，企业更可能提高薪资，从而加大通胀压力并牵动央行利率政策考量。

**标签**: `#UK economy`, `#unemployment`, `#inflation`, `#labor market`, `#monetary policy`

---