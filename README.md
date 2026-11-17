# 这也能算工作？！

THIS IS A JOB?!

不正常人类研究所 · 第三号实验

一款荒诞职场互动网页游戏。玩家将在一家“不生产问题，只重新定义需求”的公司完成各种越来越离谱的工作任务。玩法包括视觉操作、资源管理、荒诞需求和个性化职场鉴定。

## Live Demo

[在线游玩](https://liurunjia629-bit.github.io/This-is-a-job-/)

## V1.1

- 《Logo再大一点》：拖动、缩放、布局与五轮客户需求。
- 《这个需求很简单》：75秒资源管理、需求膨胀、认真完成、快速应付、拒绝、延期与缩减范围。
- 异常劳动事故报告、六种鉴定彩蛋、图鉴、localStorage存档、PNG结果卡、Web Audio音效。
- 品牌Logo返回本游戏首页；所有游戏资源使用相对路径，兼容Pages子路径。

## 本地运行

需要Node.js 22或更新版本，无第三方依赖。

```sh
node serve.mjs
```

打开 http://127.0.0.1:4173/ 。测试：`node --test tests/*.test.mjs`。

## 部署

纯HTML/CSS/JavaScript，无需构建。GitHub Pages可从main分支根目录发布，另附GitHub Actions工作流。

## 品牌与资源

统一品牌SVG直接沿用前作Dont-Make-Me-Work的lab-logo.svg，保持图形与中英文组合。角色和游戏内客户Logo使用原创SVG/CSS，音效由Web Audio生成。字体优先Noto Sans SC，回退Microsoft YaHei及sans-serif。

存档保存在本地浏览器，不需要注册。测试及已知验证限制参见TEST-REPORT.md和V1.1-CHANGES.md。
