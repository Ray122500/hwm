# 💣 扫雷 Minesweeper

一个纯 HTML/CSS/JavaScript 实现的扫雷小游戏，单个 `index.html` 文件，无需任何构建工具。

## 在线试玩

部署在 Vercel：https://hwm-tawny.vercel.app

## 功能

- 三种难度：简单 9×9（10 雷）/ 中等 16×16（40 雷）/ 困难 16×30（99 雷）
- 第一次点击保证不踩雷（含周围 8 格安全区）
- 左键翻开、右键插旗；手机端点按翻开、长按插旗
- 空白区域自动展开（洪水填充）
- 计时器 + 剩余雷数计数器 + 笑脸重开按钮
- 胜利后自动给所有雷插旗

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 部署（GitHub + Vercel）

```bash
git init
git add .
git commit -m "我的扫雷游戏"
git remote add origin https://github.com/<你的用户名>/saolei.git
git branch -M main
git push -u origin main
```

然后到 [vercel.com](https://vercel.com) → Add New Project → Import 该仓库 → Framework Preset 选 **Other** → Deploy。
