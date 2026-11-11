# Money Manager

A SiYuan bookkeeping plugin. Track daily income and expenses with custom tree categories, statistics, moods, star ratings, images, and Daily Note integration.

## Features

- Record daily income / expense with custom hierarchical categories (accounts).
- Statistics: summary, category breakdown, monthly income/expense chart.
- Daily Note integration: reuse the notebook's system daily-note template and maintain a dedicated transaction child document.
- Attach mood and multiple images to each record (local upload or remote URL via forwardProxy).
- ZIP export/import with metadata and images; legacy JSON backups remain supported.

## Editions and activation

- **Free:** bookkeeping, statistics, categories, and basic data backups.
- **Pro:** image attachments, Daily Note settings and synchronization, legacy daily-note migration, and the tree-hole bubble view.
- Open Settings → Version & License, copy the machine code, send it to the seller, and paste the issued license to activate.
- [Purchase Pro on Taobao](https://e.tb.cn/h.jQSAgko2SkQvsYg?tk=MRyu6dKwpDi). The purchased plan and signed license determine the validity period.
- Initial activation requires a connection. Each plugin load performs one remote check; subsequent feature guards use cached state. Existing locally valid signed licenses remain usable during network failures; explicit expiration, revocation, or machine mismatch locks Pro features.
- Deactivation does not revoke the license or delete transactions or existing images. Free users can still view existing images, edit ordinary transaction fields, and export backups. Restoring backups containing images or Daily Note settings requires Pro.
- License data is stored separately and excluded from transaction backups. Moving to another device requires a license for that device.

## Install

Search for "Money Manager" in the SiYuan marketplace, or download `package.zip` from GitHub Releases and extract it into `workspace/data/plugins/moneymanager/`, then reload the plugin.

## Development

```bash
npm install
npm run dev     # watch build
npm run check   # type check
npm run build   # production build + package.zip
```
