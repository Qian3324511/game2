# 交接笔记

## 三个仓库 / 三个文件夹

| 玩什么 | 仓库 | 在线 | 本地 |
|---|---|---|---|
| 小气象员·接雨滴 | `touhenying` | https://qian3324511.github.io/touhenying/ | `G:\Gitbub游戏\touhenying` |
| 遛弯勇者（挂机） | `game1` | https://qian3324511.github.io/game1/ | `G:\Gitbub游戏\game1` |
| 布站记·县域气象观测网 | `game2` | https://qian3324511.github.io/game2/ | `G:\Gitbub游戏\game2` |

三个都是 GitHub Pages，main 分支根目录，单文件 `index.html`，无依赖无联网。

## 布站记（本仓库）

致敬 HullQin《勃艮第城堡》，机制搬进县域气象观测网：37 格六角图板、6 类地类、骰子布点、区域计分、双人同屏 + 单人练习。

- 图板：7 行 4/5/6/7/6/5/4 共 37 格，起手站 `['0,-3','1,-3','-1,2','-1,3']`
- 参数：5 阶段 × 5 轮，暂存区 4 格，资源为经费 / 技术员
- 图标全部内联 SVG（Linux Chromium 下 emoji 会变方框）

## 备注

- github.com:443 经常被断，`git push` 失败就用 GitHub Contents API 推（本地仓库和远端因此会分叉，网络好时 `git fetch && git reset --hard origin/main`）
- 浏览器端存档在 localStorage，遛弯勇者键名 `walker_hero_v1`
