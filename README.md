# Interactive AI Demo

AI 互动游戏 × 叙事影像选题本：三个方向 15 个选题，每个都有一个可以直接在浏览器里玩的 demo，以及设计立意、未来展望和加权打分。

**在线预览：** https://yuyuyuzero.github.io/Interactive-AI-Demo/

| 方向 | Demo | 风格 | 在线试玩 |
|---|---|---|---|
| 休闲解压 | 锔 · 碎瓷重圆 | 大漆暗金 · 博物馆展柜 | [kintsugi](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/kintsugi.html) |
| 休闲解压 | 月下红线 | 剪纸 · 靛蓝夜空 | [red-thread](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/red-thread.html) |
| 休闲解压 | 中国色 · 调色铺 | 宣纸水彩 · 明亮通透 | [color-shop](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/color-shop.html) |
| 休闲解压 | 雨落青瓦 | 江南水墨 · 青灰雨雾 | [rain-tiles](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/rain-tiles.html) |
| 休闲解压 | 灯会 · 光路 | 国潮夜市 · 酒红暖金 | [lantern-light](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/lantern-light.html) |
| 互动叙事 × 叙事影像 | 第二十五帧 | 黑白默片 · Art Deco | [25th-frame](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/25th-frame.html) |
| 互动叙事 × 叙事影像 | 夜航电台 | 雨夜窗景 · 冷蓝暖橙 | [night-radio](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/night-radio.html) |
| 互动叙事 × 叙事影像 | 末班车失物招领 | 扁平插画 · 90 年代地铁 | [lost-and-found](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/lost-and-found.html) |
| 互动叙事 × 叙事影像 | 外婆的菜谱 | 暖黄手绘 · 彩铅老厨房 | [grandma-recipes](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/grandma-recipes.html) |
| 互动叙事 × 叙事影像 | 梦境当铺 | 超现实梦境 · 民国当铺 | [dream-pawnshop](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/dream-pawnshop.html) |
| 自由发挥 | 无限说书人 | 木刻版画 · 黑朱米黄 | [storyteller](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/storyteller.html) |
| 自由发挥 | 城市回信 | 邮政凸版 · 牛皮纸邮戳 | [city-letters](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/city-letters.html) |
| 自由发挥 | 方言守夜人 | 岭南骑楼 · 满洲窗夜色 | [dialect-night](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/dialect-night.html) |
| 自由发挥 | 掌中皮影 | 背光幕布 · 彩色牛皮 | [shadow-play](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/shadow-play.html) |
| 自由发挥 | 昨日之我 | 几何极简 · 石墨冷暖 | [echo](https://yuyuyuzero.github.io/Interactive-AI-Demo/demos/echo.html) |

每个 demo 都是单个 HTML 文件，没有构建步骤，美术全部由 Canvas/CSS/SVG 程序化绘制，只从 Google Fonts 加载字体。本地直接双击 HTML 即可打开。例外：掌中皮影的摄像头模式会在用户点击后从 jsDelivr 加载 MediaPipe 手势模型；不开摄像头时用指尖模式即可完整体验。

需要大模型、语音识别或摄像头的几个 demo（梦境当铺、夜航电台、无限说书人、城市回信、方言守夜人、掌中皮影）在代码里都留了注释清楚的接口桩，默认用本地剧本或规则运行。

## 目录

```
index.html      选题本（提案页）
demos/          15 个 demo，每个一个 HTML 文件
```
