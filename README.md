# Money Manager

A SiYuan bookkeeping plugin. Track daily income and expenses with custom tree categories, statistics, moods, star ratings, images, and Daily Note integration.

## Features

- Record daily income / expense with custom hierarchical categories (accounts).
- Statistics: summary, category breakdown, monthly income/expense chart.
- Daily Note integration: set a notebook, then create/append records into `Year/Month/Day` documents.
- Attach mood and multiple images to each record (local upload or remote URL via forwardProxy).
- Self-contained JSON export/import (images inlined as dataUrl) for portable backup.

## Install

Search for "Money Manager" in the SiYuan marketplace, or download `package.zip` from GitHub Releases and extract it into `workspace/data/plugins/moneymanager/`, then reload the plugin.

## Development

```bash
npm install
npm run dev     # watch build
npm run check   # type check
npm run build   # production build + package.zip
```
