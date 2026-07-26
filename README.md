# 珂溪 · 创作与健康工作台

> 单文件 H5 应用，手机 UI 风格，桌面浏览器居中显示。
> 数据存在浏览器 localStorage，刷新不丢。

## 运行方式

打开 `index.html` 即可使用，无需任何依赖（已内置 Tailwind CDN）。
建议在 Chrome / Edge / Safari 打开。

## 模块清单

| 模块 | 用途 |
|---|---|
| 每日计划 | 今日所有任务总览（日常 + 健康 + 创作） |
| 选题灵感 | 内容选题池管理 |
| 短视频文案 | 文案草稿管理（核心创作） |
| 爆款二创 | 热点视频二次创作 |
| 内容复盘 | 已发内容数据复盘 |
| 健康打卡 | 吃药/运动/情绪打卡 |

## 数据存储

所有数据存在 localStorage 的 `kexi_workbench_v1` 键下。
如需重置，在浏览器控制台执行：
```js
localStorage.removeItem('kexi_workbench_v1'); location.reload();
```