---
layout: default
title: "Horizon Summary: 2026-11-17 (EN)"
date: 2026-11-17
lang: en
---

> From 141 items, 10 important content pieces were selected

---

**Technology News**
1. [V-CAST Halves Long-Video Inference Without Training](#item-tech-news-1) ⭐️ 7.0/10

**World Affairs**
1. [Serbia’s Student List MPs to be sworn in after election win](#item-world-news-1) ⭐️ 9.0/10
2. [Ukraine claims critical hit on Kerch bridge](#item-world-news-2) ⭐️ 8.0/10
3. [Iran reports tanker mine strikes in Strait of Hormuz](#item-world-news-3) ⭐️ 8.0/10
4. [Ukraine says Russian double-tap strike killed 72](#item-world-news-4) ⭐️ 7.0/10
5. [Japan scrambles jets after alleged Russian airspace incursion](#item-world-news-5) ⭐️ 7.0/10

**Financial News**
1. [Huang exit renews scrutiny of Lutnick’s Nvidia ties](#item-finance-news-1) ⭐️ 8.0/10
2. [Bangladesh development stall and bank stress](#item-finance-news-2) ⭐️ 7.0/10
3. [U.S. inflation report flags food, energy and housing costs](#item-finance-news-3) ⭐️ 7.0/10
4. [UK jobless rate edges lower](#item-finance-news-4) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [V-CAST Halves Long-Video Inference Without Training](https://mp.weixin.qq.com/s?__biz=MzIzNjc1NzUzMw==&amp;mid=2247944324&amp;idx=3&amp;sn=0ec2b49fbc70dea4c1fc90bbcd164d64) ⭐️ 7.0/10

Researchers from Sun Yat-sen University, Hong Kong Polytechnic University, and collaborators propose V-CAST, a training-free, plug-and-play method that prunes visual tokens before they enter a language model for long-video understanding. On team-reported benchmarks across Qwen3-VL, LLaVA, and Qwen2.5-Omni \(six model setups, ten video and audio-video tasks\), keeping 25% of visual tokens on Qwen3-VL-8B at 32 frames retained 98.2% of the uncompressed model’s average score. In 768-frame audio-video tests they report 97.1% performance retention with total inference time cut by 50.0%, and a 1.5-point average lead over the next-best compression method on 256-frame long-video evaluation. The approach first allocates a per-frame token budget, then selects which tokens to keep while preserving original spatiotemporal coordinates.

rss · 量子位 · Nov 16, 14:07

**「Why long-video tokens matter」** Video-language models encode each frame into visual tokens before the language model runs, so longer clips produce large token sequences whose prefilling cost and memory grow quickly, especially when many frames repeat similar backgrounds or motion. Aggressive pruning can cut that cost, but it risks dropping brief cues and cross-frame action changes that tasks such as ordering, counting, and event localization need, which is why compression methods must balance temporal coverage with within-frame detail.

**「Impact」** Teams running long-video multimodal models such as Qwen3-VL, LLaVA, and Qwen2.5-Omni can drop V-CAST in before the language model without retraining, cutting visual tokens to about 25% and total inference time by roughly half while keeping most of the original benchmark scores.

**Tags**: `#video-llms`, `#token-compression`, `#multimodal-efficiency`, `#long-context`, `#neurips`

---

## World Affairs

<a id="item-world-news-1"></a>
### [Serbia’s Student List MPs to be sworn in after election win](https://www.theguardian.com/world/2026/nov/17/serbia-student-list-mps-sworn-in-election-triumph) ⭐️ 9.0/10

Candidates from Serbia’s Student List are to be sworn in as MPs at the new parliament’s inaugural session on Tuesday and begin forming a government after defeating Aleksandar Vučić’s Serbian Progressive Party \(SNS\) in last month’s elections, ending 14 years of SNS rule. Vučić has threatened mass protests of his own.

rss · The Guardian World · Nov 17, 05:00

**「Background」** The Student List, a grassroots slate of political outsiders, defeated Aleksandar Vučić’s Serbian Progressive Party \(SNS\) in parliamentary elections on 26 October, ending 14 years of SNS rule after he conceded defeat.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/world/2026/nov/17/serbia-student-list-mps-sworn-in-election-triumph">Serbia ’s Student List candidates to be sworn in as MPs after election ...</a></li>

</ul>
</details>

**Tags**: `#Serbia`, `#change of government`, `#elections`, `#Aleksandar Vučić`, `#Student List`

---

<a id="item-world-news-2"></a>
### [Ukraine claims critical hit on Kerch bridge](https://www.theguardian.com/world/live/2026/nov/17/europe-ukraine-russia-crimea-kerch-bridge-attack-latest-news-updates) ⭐️ 8.0/10

Ukraine said it critically damaged the Kerch bridge linking Russia and occupied Crimea in an overnight missile strike, with footage showing an explosion at the road and rail crossing. Kyiv and Moscow dispute the scale of the damage; reports say travel from the peninsula is now limited to a land corridor.

rss · The Guardian World · Nov 17, 09:15

**「Background」** Russia built the Kerch bridge after annexing Crimea in 2014—an annexation Ukraine rejects as illegal—and Ukraine had already struck the crossing the previous day.

**「Access and supply」** Travel and supply links between Russia and Crimea are now limited to a land corridor vulnerable to Ukrainian drone attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/world/2026/nov/16/ukraine-drone-kerch-bridge-russia-occupied-crimea">Ukraine hits Kerch bridge between Russia and occupied Crimea</a></li>
<li><a href="https://edition.cnn.com/2026/11/17/europe/ukraine-russia-kerch-bridge-intl-hnk">Kerch Bridge in Crimea damaged as Russia and Ukraine exchange...</a></li>

</ul>
</details>

**Tags**: `#Ukraine-Russia war`, `#Kerch bridge`, `#Crimea`, `#infrastructure attack`, `#military logistics`

---

<a id="item-world-news-3"></a>
### [Iran reports tanker mine strikes in Strait of Hormuz](https://www.aljazeera.com/news/2026/11/17/tankers-hit-in-strait-of-hormuz-as-drone-raises-alarm-at-iraq-gas-field?traffic_source=rss) ⭐️ 8.0/10

Iran reported mine strikes on tankers in the Strait of Hormuz. A drone alert at an Iraqi gas field and the arrival of a US aircraft carrier were also cited as raising regional tensions.

rss · Al Jazeera · Nov 17, 03:12

**「Background」** Iranian forces had already reported several tanker mine strikes in the Strait of Hormuz—a narrow chokepoint for global oil shipments—in the preceding days, amid a wider US–Israel confrontation with Iran.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aljazeera.com/tag/israel-iran-conflict/">US -Israel war on Iran | US -Israel war... | Today&#x27;s latest from Al Jazeera</a></li>
<li><a href="https://english.almayadeen.net/news/politics/irgc-says-us-hormuz-route-is-walled-in-by-fire-as-two-tanker">IRGC says US Hormuz route is ‘walled in by fire’ as two tankers burn</a></li>
<li><a href="https://southfront.press/military-situation-in-iran-on-november-16-2026-map-update/">Military Situation In Iran On November 16, 2026 (Map Update)</a></li>

</ul>
</details>

**Tags**: `#Strait of Hormuz`, `#Iran`, `#Iraq`, `#maritime security`, `#US military`

---

<a id="item-world-news-4"></a>
### [Ukraine says Russian double-tap strike killed 72](https://www.bbc.co.uk/news/articles/c30rk8x5g80qo?at_medium=RSS&amp;at_campaign=rss) ⭐️ 7.0/10

Ukrainian officials say a Russian “double-tap” strike—a follow-up attack on responders—killed 72 people in southern Ukraine, and that continuing Russian strikes are still hampering efforts to recover bodies.

rss · BBC World · Nov 17, 05:59

**「War context」** The fighting is part of Russia’s ongoing invasion of Ukraine.

**「Civilian toll」** Ukrainian officials say 72 people were killed in southern Ukraine and continuing strikes are still blocking recovery of the dead.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/world/ukraine-russia-war/">Latest Ukraine and Russia at War News - reuters.com</a></li>

</ul>
</details>

**Tags**: `#Ukraine-Russia war`, `#civilian casualties`, `#double-tap strike`, `#southern Ukraine`

---

<a id="item-world-news-5"></a>
### [Japan scrambles jets after alleged Russian airspace incursion](https://www.bbc.co.uk/news/articles/c60evw20qe47o?at_medium=RSS&amp;at_campaign=rss) ⭐️ 7.0/10

Japan scrambled fighter jets after an alleged Russian incursion of its airspace. Taiwan and South Korea also responded to Russian military aircraft detected near their airspaces.

rss · BBC World · Nov 17, 07:44

**「Background」** Governments in the region routinely scramble fighter jets—launching them quickly to intercept—when foreign military aircraft approach or enter airspace they claim, and may protest diplomatically afterward.

**Tags**: `#Russia`, `#Japan`, `#airspace`, `#military-incident`, `#East-Asia`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Huang exit renews scrutiny of Lutnick’s Nvidia ties](https://www.cnbc.com/2026/11/13/howard-lutnick-nvidia-jensen-huang-china-cantor-fitzgerald.html) ⭐️ 8.0/10

Jensen Huang’s resignation as Nvidia CEO has brought renewed scrutiny to U.S. Commerce Secretary Howard Lutnick and his family’s financial ties to the chipmaker.

rss · CNBC Finance · Nov 16, 12:14

**「Background」** Howard Lutnick is the U.S. commerce secretary, whose department oversees trade and export rules that affect advanced chipmakers such as Nvidia.

**Tags**: `#Nvidia`, `#Howard Lutnick`, `#CEO resignation`, `#conflict of interest`, `#semiconductors`

---

<a id="item-finance-news-2"></a>
### [Bangladesh development stall and bank stress](https://www.economist.com/asia/2026/11/16/bangladesh-is-no-longer-a-development-superstar) ⭐️ 7.0/10

The Economist reports that Bangladesh is no longer a development superstar, as corruption has pushed its banks to the verge of insolvency and stalled its earlier development success.

rss · The Economist · Nov 16, 18:31

**「Background」** Bangladesh’s banks have seen loans that borrowers have stopped repaying rise above 30% of total lending, among the highest shares worldwide.

<details><summary>References</summary>
<ul>
<li><a href="https://www.thedailystar.net/business/news/default-loans-may-exceed-30-june-3821231">Default loans may exceed 30% by June | The Daily Star</a></li>
<li><a href="https://www.moneycontrol.com/world/bangladesh-tops-global-bad-loan-ranking-as-banking-sector-non-performing-loan-ratio-crosses-32-article-14022139.html">Bangladesh tops global bad loan ranking as banking sector Non ...</a></li>

</ul>
</details>

**Tags**: `#Bangladesh`, `#banking-crisis`, `#corruption`, `#emerging-markets`, `#economic-development`

---

<a id="item-finance-news-3"></a>
### [U.S. inflation report flags food, energy and housing costs](https://news.google.com/rss/articles/CBMi2wFBVV95cUxOVEI0ajRDVk9UaDlyeXZSYVhqSDlXcDlzZGtJcURDM0plUHhkMklBX3E0VXA2bTNpZ0FYaV8wRkRoZW5OQ1VrQUkzSTJZYU1mMUJVV2E0Tjk5NzBzVk9pQlZxMWVqQnkxT002X3c0WXo0SFlUemdOUEVXbXZ2WG1jaUJaY2l2MVFINjBjV2RBQVFTRVVSQ3dCVG5GN1F3V0pjVFlCa3pvZzZTZ3JMdDVYcGZJNTdDVVY4RFpEMGV1U2VMZ1R3VUowSDBWT2hCVGdZR3JYdERwNlRscEk?oc=5) ⭐️ 7.0/10

A U.S. inflation report highlights ongoing strain on households from rising food, energy and housing costs, according to PBS.

google\_news · PBS · Nov 16, 16:40

**「Background」** U.S. consumer inflation is mainly tracked by the Consumer Price Index, which rose to 3.7% in September 2026 from 3.4% in August.

<details><summary>References</summary>
<ul>
<li><a href="https://tradingeconomics.com/united-states/inflation-cpi">United States Inflation Rate</a></li>

</ul>
</details>

**Tags**: `#inflation`, `#US economy`, `#consumer prices`, `#cost of living`, `#economic data`

---

<a id="item-finance-news-4"></a>
### [UK jobless rate edges lower](https://news.google.com/rss/articles/CBMitAFBVV95cUxOTEl0dEVXWFZSczVQejI3aElaVU40c21IX0wxNVZwNzB0MDdFWG5KY2tOMzBiWWtJVk83UWVONmg2UVg3dVlOMnE4azl3WkhBeTJFSkZBWXpBd2MwYnJUWFBhNllZY1FuTUU4THlTUnR0YzlLV3Z6Z3pXOWs5M3V4U3hGSk5NdFJPSGtQVGVSLWJHaHJacTFqY3p4SFVYZjVoNG5CTnl1RDRrVkthTWc3aTVlN0Q?oc=5) ⭐️ 7.0/10

The U.K. jobless rate edged lower, according to a Wall Street Journal report, adding to concerns about inflation.

google\_news · WSJ · Nov 17, 07:36

**「Background」** A lower jobless rate can signal a tighter labor market, where employers may raise pay to hire or keep workers, and that wage pressure can feed into higher consumer prices.

**Tags**: `#UK economy`, `#unemployment`, `#inflation`, `#labor market`, `#monetary policy`

---