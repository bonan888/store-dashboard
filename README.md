# 国际站经营数据大屏

店铺 cn1576649761kois 的实时经营数据看板，每日 09:00（北京时间）自动拉取最新数据并更新。

## 访问地址

GitHub Pages: `https://bonan888.github.io/store-dashboard/`

## 内容

- 核心 KPI：搜索曝光 / 点击 / 访客 / 商机 / 订单 / GMV
- 流量转化漏斗（Chart.js）
- 渠道流量分布
- 买家地域 Top10
- 商品健康度分层
- 服务能力评估
- 行动建议（P0-P3）

## 数据更新

- 数据来源：阿里巴巴国际站数据参谋
- 更新频率：每日 09:00 自动（Asia/Shanghai）
- 数据窗口：近 7 天

## 本地更新

```powershell
powershell -ExecutionPolicy Bypass -File update_dashboard.ps1
```
