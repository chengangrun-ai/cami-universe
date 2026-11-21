# CAMI's Universe · 个人数字宇宙

一个《小王子》主题的 3D 个人作品集：封面捏脸 → 私人图书馆书墙 → 三本特殊书翻书穿页 → 三颗可探索星球（走路 / 互动 / 摘玫瑰 / 作品索引闪现）→ 轨道总览。

## 在线预览

- 豆包托管版：https://4mj4cu48v90fx.doubao.link/app/app_17jfsp5mj45
- GitHub Pages：见仓库右侧 **Deployments** 或下方说明（开启后更新）。

## 本地运行

纯静态站点，无需构建。任意静态服务器即可：

```bash
# 任选其一
python -m http.server 8766
npx serve .
```

浏览器打开 `http://127.0.0.1:8766/`。

## 技术栈

- 原生 JavaScript（无框架、无构建工具）
- Three.js 0.134（本地 vendor）+ GSAP 3.12.5（本地 vendor）
- 单文件 `index.html`，CSS / JS 全内联，素材在 `assets/`

## 目录结构

```
index.html        站点入口（单文件）
assets/
  faces/          封面表情贴图
  books_v2/       书架书封
  works/          作品建筑封面
  gallery/        作品画廊缩略图
  planets/        星球背景贴图
  vendor/         three / gsap / 字体 woff2
```

## 作品分布

机械星 4 · 创意星 8 · 知识星 7，共 19 个项目。
