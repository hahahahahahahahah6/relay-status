# Relay 实时验证 · 鹈鹕骑车测试

本站（relay.haocoach.com）每 5 小时自动调用一次中转站，测试提示词固定为「鹈鹕骑车」（请模型描写一只鹈鹕骑自行车），并公开每一次的返回内容、耗时与 token 用量。返回是真 Claude 的现场写作，无法靠便宜模型冒充，以此证明本站没有掺水。测试不调用官方 API 做对比，只测本站自身。

- 状态页：https://hahahahahahahahah6.github.io/relay-status/（GitHub Pages）
- 数据：`results.json`（每次测试追加一条，最多保留 100 条）
- 测试提示词：请写一段话，生动描写一只鹈鹕骑着自行车穿过公园的样子。要求：不少于80字，语言生动具体。
- 测试模型：claude-sonnet-4-6（经 relay.haocoach.com 调用）
- 间隔：每 5 小时（cron）
