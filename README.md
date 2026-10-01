# 坦克大战 · Battle City

> 🎮 **在线游玩：[caiceafelipeantonio-pixel.github.io/battle-city](https://caiceafelipeantonio-pixel.github.io/battle-city/)**

一个纯 HTML / CSS / JavaScript 实现的经典《坦克大战》（Battle City）网页游戏，无需任何依赖，双击即可游玩，也可一键部署到 GitHub Pages。

## 玩法

- **目标**：消灭当前关卡所有敌方坦克，同时守住位于底部中央的金色基地（鹰）。
- **失败条件**：基地被击中，或生命值耗尽。

## 操作

| 操作 | 按键 |
| --- | --- |
| 移动 | 方向键 `↑ ↓ ← →` 或 `W A S D` |
| 射击 | `空格` 或 `J` |
| 暂停 / 继续 | `P` |
| 静音 | `M` |
| 开始 / 重开 | `Enter` |

## 特性

- 三张设计好的关卡地图（砖墙、钢墙、水域、树林等地形）
- 三种敌人：普通、快速、装甲（4 点血）
- 火力升级（最高可摧毁钢墙）、无敌护盾、额外生命三种道具
- 粒子爆炸特效 + Web Audio 合成音效
- 记分、生命、关卡进度 HUD
- 响应式布局，支持键盘与触屏适配

## 快速开始

直接在浏览器中打开 `index.html` 即可。

### 部署到 GitHub Pages

1. 将本仓库推送到 GitHub；
2. 进入仓库 **Settings → Pages**；
3. 在 **Source** 中选择 `main` 分支，目录选 `/ (root)`；
4. 保存后即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 技术说明

- 纯 Canvas 2D 渲染，13×13 网格地图（每格 32px）
- `requestAnimationFrame` 游戏循环，基于 delta-time 的运动
- 无任何第三方库或外部资源

## 许可证

MIT
