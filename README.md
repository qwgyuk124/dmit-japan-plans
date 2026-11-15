# DMIT日本测评：Pro、Eyeball、Tier 1三条线怎么选？22个套餐价格、循环优惠与退款条款一次讲清（附年成本测算）

DMIT 日本东京机房现在有三条产品线，价格从年付 $36.90 到月付 $799.90，跨度二十多倍。Pro 走三网 CN2 GIA 回程，入门 $21.90/月；Eyeball 走三网 CMI 回程，入门 $25.90/月；Tier 1 是国际线路，年付 $36.90 起，折合每月三美元出头。

选哪条，取决于你的流量主要落在哪个运营商、要不要大陆优化、每月能接受多少预算。下面把 22 个套餐的价格、一个续费不涨价的循环折扣码、流量超了会怎样、买错能不能退，逐项讲清楚。

> **选购速览**
>
> - 主力是电信、要晚高峰稳定回国：TYO Pro，TINY 月付 $21.90
> - 主力是移动、要大带宽和大流量：TYO Eyeball，从 STARTER 起有 2Gbps
> - 只要一个日本 IP、不关心回国速度：TYO Tier 1，WEE 年付 $36.90
>
> 👉 [查看 DMIT 日本当前全部套餐与库存](https://www.dmit.io/aff.php?aff=9081)

## 三条线的路由差在哪，谁该选哪条

三条线的区别不在 CPU 和硬盘，全系都是 KVM 虚拟化、AMD EPYC 处理器加 NVMe SSD，差别在网络。

**TYO Premium（Pro）**：去程电信走 CN2 GIA、联通走 AS9929、移动走 CMI，三网回程统一 CN2 GIA。CN2 GIA 是电信的商用精品线路，走 59.43 网段，绕开公网拥堵节点，这也是 Pro 卖得最贵的直接原因。

**TYO Eyeball（EB，官方型号 TYO.AS3.EB）**：三网回程 CMI，电信和联通去程走 CTG GIA，移动去程走 CMI。CMI 是中国移动国际线路，移动用户直连效果好；电信联通有去程优化，回程不如 Pro。

**TYO Tier 1（T1）**：电信联通走 NTT，移动走 CMI，没有大陆优化。适合只想要日本 IP 的场景，回国速度看当时路由，不保证。

| 你的情况 | 该选 | 依据 |
| --- | --- | --- |
| 电信宽带，晚上 8–11 点要稳 | Pro | 回程 CN2 GIA，第三方测得晚高峰波动小 |
| 移动宽带或移动流量为主 | Eyeball | 回程 CMI，移动链路最短 |
| 建站、反代、服务国内用户 | Pro | 三网回程一致，不会某个运营商特别差 |
| 跑下载、中转、大流量业务 | Eyeball 或 T1 | 同价位流量配额高得多 |
| 只要日本 IP、日区业务落地 | T1 | 无大陆优化，价格最低 |
| 预算卡在每月 10 美元以内 | T1 | WEE 年付 $36.90，全线最低入口 |

## 全部 22 个套餐的价格

以下价格来自公开套餐整理，币种为美元，实际以下单页结算为准。网上流传过一些更低的 Pro 报价（比如入门 $14.90），与当前在售结构对不上，本文不采用。

### TYO Premium（三网 CN2 GIA 回程）

| 套餐 | 配置 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB / 20GB SSD | 500GB / 1Gbps | $21.90/月 | [开通 Pro TINY](https://www.dmit.io/aff.php?aff=9081&pid=138) |
| STARTER | 1核 / 2GB / 40GB SSD | 1000GB / 1Gbps | $39.90/月 | [开通 Pro STARTER](https://www.dmit.io/aff.php?aff=9081&pid=139) |
| MINI | 2核 / 2GB / 60GB SSD | 2000GB / 1Gbps | $79.90/月 | [开通 Pro MINI](https://www.dmit.io/aff.php?aff=9081&pid=140) |
| MICRO | 4核 / 4GB / 80GB SSD | 4000GB / 1Gbps | $159.90/月 | [开通 Pro MICRO](https://www.dmit.io/aff.php?aff=9081&pid=141) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 5000GB / 1Gbps | $259.90/月 | [开通 Pro MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=142) |
| LARGE | 8核 / 16GB / 320GB SSD | 8000GB / 1Gbps | $429.90/月 | [开通 Pro LARGE](https://www.dmit.io/aff.php?aff=9081&pid=143) |
| GIANT | 8核 / 24GB / 640GB SSD | 15000GB / 1Gbps | $799.90/月 | [开通 Pro GIANT](https://www.dmit.io/aff.php?aff=9081&pid=144) |

### TYO Eyeball（三网 CMI 回程）

| 套餐 | 配置 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB / 20GB SSD | 1000GB / 1Gbps | $25.90/月 | [开通 EB TINY](https://www.dmit.io/aff.php?aff=9081&pid=221) |
| STARTER | 1核 / 2GB / 40GB SSD | 2000GB / 2Gbps | $55.90/月 | [开通 EB STARTER](https://www.dmit.io/aff.php?aff=9081&pid=222) |
| MINI | 2核 / 2GB / 60GB SSD | 3000GB / 2Gbps | $85.90/月 | [开通 EB MINI](https://www.dmit.io/aff.php?aff=9081&pid=223) |
| MICRO | 4核 / 4GB / 80GB SSD | 4000GB / 4Gbps | $119.90/月 | [开通 EB MICRO](https://www.dmit.io/aff.php?aff=9081&pid=224) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 6000GB / 4Gbps | $179.90/月 | [开通 EB MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=225) |
| LARGE | 8核 / 16GB / 320GB SSD | 12000GB / 4Gbps | $369.90/月 | [开通 EB LARGE](https://www.dmit.io/aff.php?aff=9081&pid=226) |
| GIANT | 8核 / 24GB / 640GB SSD | 24000GB / 4Gbps | $749.90/月 | [开通 EB GIANT](https://www.dmit.io/aff.php?aff=9081&pid=227) |

### TYO Tier 1（国际线路，无大陆优化）

| 套餐 | 配置 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| WEE | 1核 / 1GB / 20GB SSD | 1000GB | $36.90/年 | [开通 T1 WEE](https://www.dmit.io/aff.php?aff=9081&pid=228) |
| TINY | 1核 / 1GB / 20GB SSD | 2000GB | $6.90/月 | [开通 T1 TINY](https://www.dmit.io/aff.php?aff=9081&pid=131) |
| STARTER | 1核 / 2GB / 40GB SSD | 4000GB | $12.90/月 | [开通 T1 STARTER](https://www.dmit.io/aff.php?aff=9081&pid=132) |
| MINI | 2核 / 2GB / 60GB SSD | 8000GB | $21.90/月 | [开通 T1 MINI](https://www.dmit.io/aff.php?aff=9081&pid=133) |
| MICRO | 4核 / 4GB / 80GB SSD | 16000GB | $32.90/月 | [开通 T1 MICRO](https://www.dmit.io/aff.php?aff=9081&pid=134) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 32000GB | $49.90/月 | [开通 T1 MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=135) |
| LARGE | 8核 / 16GB / 320GB SSD | 64000GB | $99.90/月 | [开通 T1 LARGE](https://www.dmit.io/aff.php?aff=9081&pid=136) |
| GIANT | 8核 / 24GB / 640GB SSD | 128000GB | $199.90/月 | [开通 T1 GIANT](https://www.dmit.io/aff.php?aff=9081&pid=229) |

## 三个容易被价格表误导的地方

**Eyeball 入门比 Pro 贵 4 美元，但流量翻倍。** EB TINY $25.90 给 1000GB，Pro TINY $21.90 只给 500GB。按流量单价算，EB 是 $0.0259/GB，Pro 是 $0.0438/GB，EB 反而便宜。所以不能简单说 EB 更贵，只能说它起步配置给得更多。每月流量不到 500GB 的人，多花这 4 美元是浪费；流量在 500GB 到 1TB 之间、又是移动用户，EB TINY 更合适。

**Eyeball 的性价比从中端才开始明显。**到了 MICRO 这一档，EB 是 $119.90 给 4Gbps 带宽、4000GB 流量，Pro 是 $159.90 给 1Gbps、同样 4000GB。EB 便宜 40 美元，带宽是四倍。代价是回程从 CN2 GIA 换成 CMI，电信用户体验会掉一档。电信用户为了省这 40 美元选 EB，通常会在晚高峰后悔。

**Tier 1 的流量配额高得不正常，因为差价买的是线路。** T1 STARTER $12.90/月给 4000GB，Pro STARTER $39.90/月只有 1000GB，两者差 27 美元。这 27 美元不买配置、不买流量，买的是三网回程 CN2 GIA 这一段路由。反过来说，如果你压根不需要大陆优化，花 39.90 买 Pro STARTER 就是纯浪费。

## 优惠码与真实的年成本

Pro 系列有一个循环折扣码 `202510_HKG_TYO_PRO_20OFF_RECURRING`，季付及以上打 8 折，**续费仍是折后价**，不是只优惠首期。这一点比折扣力度本身更重要——很多商家首年低价、续费翻倍，两年下来并不便宜。

拿 Pro TINY 算一笔：月付 $21.90，一年 $262.80。用这个码季付，折后约 $17.52/月，一年约 $210.24。两者差约 $52.56，相当于白拿两个多月的机器。

码名里的 `202510` 指向 2025 年 10 月的一次活动，现在还能不能用，只能在下单页填进去看。能用就下单，显示无效就按原价买或者等下一次活动，不要为了等码拖过退款窗口。

T1 系列另有季付折扣码，具体码面在结算页可见，这里不写死，因为流传的版本不止一个。

优惠码不能叠加，一个订单只能用一个。循环折扣码的优先级高于一次性折扣码，长期用的话选循环的那个。

👉 [用 8 折循环码开通 Pro TINY](https://www.dmit.io/aff.php?aff=9081&pid=138)

## 流量用超之后，三条线的处理完全不同

这条对拿机器跑下载、做中转的人影响最大，也是很多测评一句"超出限速"带过的地方。

**Pro 和 Eyeball 超出流量后暂停服务**，要么等下一个计费周期重置，要么手动购买额外流量。机器直接停，业务跟着断。

**Tier 1 超出后不停机，降速到 50Mbps 继续跑。** 对轻量业务来说，50Mbps 还能撑住网页和 API 请求，不至于半夜被报警叫醒。

购买前先估一下月流量落在哪个区间。如果预计会经常贴着配额跑，T1 的"限速不停机"比多给 500GB 更实用；反过来，如果你的业务不能接受降速，那就该往上一档买，而不是赌自己用不完。

## 退款和换 IP：买错的成本有多高

新购 3 天内可以无理由全额退款，前提是流量使用不超过 30GB。30 天内可以按剩余价值比例退。

这个条款的实际意义是：你有一到三天时间把机器开起来，跑一遍晚高峰的延迟和下载，不满意直接退，损失接近零。比起那些"一经售出概不退款"的商家，试错成本低得多。

IP 被封的情况，Pro 和 Eyeball 每 15 天可以申请免费更换一次，需要确认 IP 确实被封，不是随意换着玩。

👉 [先开一台 Pro TINY 实测，3 天内可全额退](https://www.dmit.io/aff.php?aff=9081&pid=138)

## 延迟和解锁的第三方数据

以下数字来自第三方测评记录，不是官方标称，你的实际结果会因所在地和运营商而异。

东京到中国大陆的基础延迟大约在 60–80ms。Pro 走 CN2 GIA，晚高峰基本维持在这个区间。有测评者在电信宽带上记录到白天 75–85ms、晚高峰不超过 120ms，同时段普通日本 VPS 可能从 80ms 涨到 200ms 以上。Eyeball 走 CMI，测评记录显示到北京电信约 60ms、联通约 55ms、移动约 55ms，晚高峰稳定。T1 没有大陆优化，延迟随路由变化，不做承诺。

硬件层面，全系 NVMe SSD，第三方测得的存储 IO 在 800MB/s 量级，日常建站和小型数据库够用。

流媒体方面，第三方实测 IPv4 可解锁 Netflix 日本区、Disney+ 日本区、YouTube Premium 日本区、Prime Video 日本区，ChatGPT 可正常访问，Spotify 注册不支持。IPv6 下 Netflix 仅能看原创内容。IP 池整体质量不错，原生 IP 属性对访问日本本地服务有帮助，具体 IP 段建议开通后自测。

## 和香港节点怎么选

同品牌的香港 Pro 到大陆最低 20–30ms，比东京快一截，但入门价 $39.9/月，是东京 Pro 入门价 $21.9/月的近两倍。

延迟敏感、预算充足的选香港；预算有限、能接受 60–80ms 的选东京。这两条线不冲突，是同一个品牌在不同价位上的两档选择。

## 下单前最后确认三件事

**第一，Eyeball 有没有货。** Eyeball 系列在 2026 年部分时段库存紧张甚至临时下架，付款前先在套餐页确认。缺货时的替代方案：往上选 Pro，往下选 T1。

**第二，优惠码是否还有效。** 把 `202510_HKG_TYO_PRO_20OFF_RECURRING` 填进结算页，看折扣有没有真的减掉。T1 的码同理。

**第三，支付方式。** 支付宝、PayPal、信用卡都可以，微信支付以下单页实际显示为准。

选择规则收拢成一句：要大陆优化就买 Pro，移动用户或大流量需求买 Eyeball，只要日本 IP 买 T1。三条线里没有哪条是"全能最优"，只有哪条匹配你的运营商和流量。

👉 [前往 DMIT 挑选适合你的日本套餐](https://www.dmit.io/aff.php?aff=9081)
