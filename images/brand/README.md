# TRADER WATCH 品牌标识

2026-11-21 更新。图形以“观察之眼＋双 K 线”为主体，眼形下沿带一个轻微 W，呼应 WATCH。

- 主色：暖金 `#DDB477`。背景：深蓝 `#0B1018`。
- 网页页头使用透明 SVG，浏览器、收藏夹和手机图标使用同一图形的深色底版。
- 字标保持 `TRADER WATCH / 币安交易员观察台`，不改变产品名称。
- 保持比例和清晰留白；不添加阴影、纹理或渐变。

## 文件

| 文件 | 用途 |
| --- | --- |
| `trader-watch-mark.svg` | 透明矢量图形 |
| `trader-watch-mark-512.png` | 512px 透明 PNG |
| `trader-watch-lockup.svg` / `.png` | 英文与中文组合标识 |
| `trader-watch-icon.svg` | 深色底图标源文件 |
| `trader-watch-icon-96.png` / `-192.png` / `-512.png` | 应用和通知页脚图标 |

本目录提供可查看与下载的品牌文件。代码仓库的源码位置为 `aoying-web/public/brand/`；生成命令：

```sh
npm run brand:build
```

导出脚本使用当前项目已经安装、锁定的 Sharp，生成 favicon SVG / ICO / PNG、Apple 图标、应用图标和分享卡片。运行网站不需要在线生成图像。

## 概念与生产文件

先使用内置图像生成完成概念探索，再以 SVG 几何路径整理为清晰的单色生产标识；生产资产以 SVG 源文件和导出脚本为准。

概念提示词：

> Create a single original minimalist logo SYMBOL for TRADER WATCH, a public-trader observation and candlestick replay web app with a refined dark-navy and muted warm-gold visual style. Use case: logo-brand. Asset type: production brand mark. Design an elegant compact geometric eye / observation aperture, containing two very simple solid candlestick-like vertical elements. The negative space can subtly suggest a W, but prioritize an instantly readable observation-eye silhouette. One flat muted warm-gold color close to #DDB477, transparent background. Clean vector-like paths, balanced geometry, bold enough to remain recognizable at 16px, rounded precision corners where appropriate. Single centered icon only, approximately 75% of a square canvas. No text, no letters, no wordmark, no slogan, no surrounding square, no chart background, no gradients, no glow, no shadows, no 3D, no textures, no presentation mockup, no watermarks. Restrained premium financial software aesthetic, not an exchange logo.
