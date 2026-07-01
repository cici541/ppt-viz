# Timeline Slide Example

## Input

```text
请你用这个技能，帮我做一页中国近20年网络安全发展史的PPT

用户补充：成品图，我想要用政企风格。
```

## Expected Behavior

The skill should:

- Identify the page as `时间线 / 行业发展史页`
- Compress the topic into a single core message about China's cybersecurity evolution from compliance construction to data, critical infrastructure, AI, and digital infrastructure security governance
- Choose a horizontal timeline or staged roadmap rather than a statistical chart
- Confirm output mode first when missing
- Recommend an enterprise/government cybersecurity style, prioritizing Anheng-compatible rules when the user has not selected a style

## Example Final Prompt Excerpt

```text
生成一张 16:9 政企网络安全汇报风格 PPT 成品页，主题为“中国近20年网络安全发展史”。整体视觉专业、稳重、科技感克制，采用深蓝、政务蓝、湖蓝、白色和深灰为主色，少量红色仅用于关键法规或风险治理节点强调。页面顶部设置深蓝色标题栏，左侧放置白色加粗标题“中国近20年网络安全发展史”，右侧可放小号章节信息“2006-2026｜从合规建设到数字安全治理”。

正文区域使用纯白或极浅蓝背景，保持充足留白和严格网格对齐。画面中央设计一条横向发展时间线，从左到右分为五个阶段：2007-2013 制度起步、2014-2016 国家战略、2017-2019 法律体系成型、2021-2023 数据安全与关基保护、2024-2026 AI安全与数字基础设施。每个阶段使用政企风模块卡片呈现年份、关键词和一句说明，关键法规节点用小型红色标签强调。

视觉元素使用网络安全语义图形：盾牌、锁、服务器、数据流、网络节点、关键信息基础设施图标、SOC态势感知小屏幕。所有图形必须服务内容表达，避免无意义装饰。整体画面应像政府部门、央国企、网络安全厂商发布会或方案汇报中的正式页面，信息清晰、文字可读、结构严谨。
```
