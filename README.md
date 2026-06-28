# 🍽️ 菜单助手

私人厨师菜单管理网页应用 — 方便在手机和 iPad 上快速编排每日菜单。

## 功能

- **分类管理**：默认前菜/肉菜/汤品/主食，可自由增删改分类，自定义图标和颜色
- **菜式库**：按分类添加菜式，一键勾选上菜单
- **液态玻璃 UI**：毛玻璃质感卡片，手机/iPad 触控友好
- **菜单预览**：按分类整齐排版，带日期和编号
- **导出图片/PDF**：一键导出，方便微信发送给老板

## 使用方法

1. 用浏览器打开 `index.html`，或部署到 GitHub Pages 后访问网址
2. 点击分类卡片切换分类，在底部输入菜名添加菜式
3. 勾选要上菜单的菜式（默认勾选），点击「预览」
4. 预览满意后点击「导出图片」或「导出PDF」

## GitHub Pages 部署

1. 创建 GitHub 仓库
2. 上传 `index.html` 和 `favicon.svg`
3. Settings → Pages → Source: `main` branch → Save
4. 通过 `https://<用户名>.github.io/<仓库名>/` 访问

## 技术

- 纯 HTML/CSS/JS 单文件，无构建工具
- 数据存 localStorage，无需后端
- html2canvas (CDN) 实现图片导出
- 响应式 + iOS Safe Area 适配
