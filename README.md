# 【2026.09 自用】AI API 中转站推荐：GPT-6 / Claude 5 / Gemini 3 / 国产模型，低倍率渠道合集

> 纯个人充值实测，非软文（部分含 AFF 返利链接，介意请去掉 `?aff=` 参数）
>
> ⚠️ 先说清楚：中转站本质是二级渠道，存在降智、跑路、隐私风险，请自行判断。**公司代码、密钥、隐私数据别过中转。**

## 0. 一句话科普

中转站 = AI API 的分销商：转卖 OpenAI / Anthropic / Google / DeepSeek 等接口，给你一个 OpenAI 兼容的 `base_url + sk-key`，按 **官价 × 分组倍率** 计费，通常只要官价的 1~3 折。便宜是真能便宜，但渠道质量鱼龙混杂，所以这篇帖子按场景帮你筛一筛。

## 1. 按需选站（TL;DR）

| 需求 | 站点 | 一句话点评 |
|---|---|---|
| 自带智商检测 | [yoshub](https://api.yoshub.com/?aff=ZZrl) | 有便宜的claude aws |
| 全且稳，懒得折腾 | [poke2api](https://www.poke2api.com/register?aff=9ZYKTQL98HAE) | 贵一点，但模型全且稳定 |
| 性价比之选 | [starapi](https://www.starapi.cc/register?aff=P8XWVHXYHNHN) | 便宜的国模渠道量大管饱 |
| 便宜大碗 luna | [usa0](https://usa0.top/register?aff=CX64TD5KYYPK) | 有 gpt-6-luna，要低价的可以试试 |
| 写代码拒绝降智 | [dieqiyun](https://dieqiyun.top/register?aff=2AQQNGXAYMMU) | 不降智渠道很多 |
| 怕跑路，要活人售后 | [wanzhao](https://sub.wanzhao.top/register?aff=YDSMZ3PB4278) | 群主是活人，天天在群里 |

## 2. 各站详解

### 1️⃣ yoshub —— 自备智商检测，模型多

**入口**：https://api.yoshub.com/?aff=ZZrl

- 有便宜的claude aws渠道，其他的也比较便宜
- 渠道多也意味着同一模型不同分组体验差异大，**建议小额充值多测几个分组**，找到适合自己的那条线
- 适合：喜欢折腾、想一站集齐所有模型的玩家

### 2️⃣ poke2api —— 贵一点，但模型全且稳定

**入口**：https://www.poke2api.com/register?aff=9ZYKTQL98HAE

- GPT / Claude / Gemini / Grok / DeepSeek / GLM / Kimi / 千问 / 豆包 / MIMO / Muse Spark 全都有，连生图、视频专用分组都齐，价格不算便宜，胜在渠道稳、模型全，透传线路多
- 适合：拿它当主力、不想天天换站的生产力用户

### 3️⃣ starapi —— GPT 炸了，国模兜底

**入口**：https://www.starapi.cc/register?aff=P8XWVHXYHNHN

- DeepSeek / GLM / Kimi / 千问等国产渠道便宜、并发足
- GPT 上游抽风的时候，切国模续命完全不慌
- 适合：国模重度用户 + 需要 Plan B 的人

### 4️⃣ usa0 —— 有 gpt-6-luna

**入口**：https://usa0.top/register?aff=CX64TD5KYYPK

- 主打 GPT 系低价线路，倍率低到 ×0.1
- 适合：GPT 重度、预算敏感，能接受号池渠道波动的

### 5️⃣ dieqiyun —— 不降智渠道很多

**入口**：https://dieqiyun.top/register?aff=2AQQNGXAYMMU

- 明确标"不降智"的分组很多：官key-不降智、24h可用-不降智-az官转、不降智分组 ×0.35 等
- 监控页实拍：主力分组 7 天可用性普遍 91%+，claude(特殊kiro) 99.66%、腾讯云 deepseek 100%、官key-不降智 95.13%
- 适合：Claude Code / Codex 编码党，对模型智商有要求的

### 6️⃣ wanzhao —— 群主是活人，天天在线

**入口**：https://sub.wanzhao.top/register?aff=YDSMZ3PB4278

- 群主天天在群里，炸了找得到人、修得也快——在中转圈，这比便宜难能可贵
- 适合：新手、怕跑路、要售后的

## 3. 价格参考（后台实拍）

> 以下来自上面几个站的后台截图，**价格随时变动，以各站实时页面为准**。
部分模型分组不好截图，改用密钥界面展示

![渠道倍率实拍](images/01-ratio.png)

![模型价格页实拍](images/02-model-price.png)

![可用性监控实拍](images/05-uptime.png)

![后台密钥实拍一](images/03-keys-a.png)

![后台密钥实拍二](images/03-keys-b.png)

![分组列表实拍（100+ 分组）](images/04-groups.png)

## 4. 怎么接入

1. 注册任意一站，**先充 1~5 刀试水**
2. 后台新建 API Key，按需选择分组（分组倍率不同）
3. 客户端里填 `base_url` + `sk-` 令牌即可：


## 5. 避坑 FAQ

**Q：倍率是什么？**
花费 = 模型官价 × 分组倍率。倍率越低越便宜，但超低倍率通常是号池/混合渠道，质量和"智商"可能打折。

**Q：什么是"降智"？**
部分号池渠道会因为上下文截断、系统提示丢失等原因，让模型表现"变笨"。写代码建议选官 key / 企业线路 / 透传 / 明确标注"不降智"的分组。

**Q：怎么防跑路？**
小额多次充值；先看监控页可用性；优先选群主活跃、有用户群、有历史记录的站。

**Q：隐私呢？**
中转站技术上能看到你的全部请求内容。敏感代码、密钥、个人数据别过中转，或选透传渠道。

**Q：AFF 是什么？**
通过本文链接注册，作者会有少量返利，不影响你的价格；介意可以去掉链接里的 `?aff=` 参数直接访问。

---

觉得有用点个 Star ⭐，有其他亲测好站欢迎 Issue 补充。
