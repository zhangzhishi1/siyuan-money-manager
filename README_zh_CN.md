# 记账

一款思源笔记记账插件。记录每日收支，支持自定义树形分类（账户）、统计、心情、星级评分、图片，以及 Daily Note 关联。

## 功能

- 记录每日收入 / 支出，支持自定义多级分类（账户）。
- 统计：汇总、分类占比、按月收支柱状图。
- Daily Note 关联：设置笔记本后，按「年/月/日」层级创建或追加当日收支到日记文档。
- 每笔记录可关联心情与多张图片（本地上传，或通过 forwardProxy 抓取外链图）。
- 自包含 JSON 导入导出（图片内联 dataUrl），可跨设备迁移备份。

## 安装

在思源集市中搜索“记账”并安装；也可以下载 GitHub Release 中的 `package.zip`，解压到 `工作空间/data/plugins/moneymanager/` 后重载插件。

## 开发

```bash
npm install
npm run dev     # 监听构建
npm run check   # 类型检查
npm run build   # 生产构建 + package.zip
```
