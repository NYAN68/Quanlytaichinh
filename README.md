# 💰 家計管理アプリ / Personal Finance Manager

[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white)](https://sheets.google.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🇯🇵 日本語

### 概要
収入・支出をWebから直接入力し、Google スプレッドシートへ自動同期できる家計管理Webアプリです。  
インストール不要で、ブラウザだけで動作します。

### 主な機能
- **ダッシュボード** — 今月の残高・収入・支出・借金を一画面で確認
- **収入・支出管理** — カテゴリ別に取引を追加・削除・フィルター
- **予算管理** — カテゴリ別の予算上限を設定し、進捗をビジュアルで確認
- **貯金・目標** — 貯金目標を作成し、積立額を管理
- **借金・ローン** — 借金の返済進捗をトラッキング
- **Google Sheets 同期** — Apps Script経由でスプレッドシートへ自動データ送信

### 使用技術
| 技術 | 用途 |
|---|---|
| `HTML / CSS / JavaScript` | フロントエンド（フレームワーク不使用） |
| `localStorage` | ブラウザ内データ保存 |
| `Google Apps Script` | スプレッドシートへのデータ連携 |

### セットアップ
```bash
git clone https://github.com/NYAN68/Zaimu-kanri
cd Zaimu-kanri
# ブラウザで finance_manager.html を開くだけで動作します
```

### Google Sheets 連携手順
1. [Google スプレッドシート](https://sheets.google.com) で新しいシートを作成
2. **拡張機能 → Apps Script** を開く
3. `apps_script.gs` の内容を貼り付けて保存
4. **デプロイ → ウェブアプリとして導入** → URLをコピー
5. アプリの **設定ページ** にURLを貼り付けて保存

---

## 🇬🇧 English

### Overview
A personal finance web app where you can input income and expenses directly in the browser, with automatic sync to Google Sheets via Apps Script.  
No installation required — runs entirely in the browser.

### Features
- **Dashboard** — overview of monthly balance, income, expenses, and debt at a glance
- **Income & Expense** — add, delete, and filter transactions by category
- **Budget Management** — set category budgets and track progress visually
- **Savings Goals** — create savings targets and track contributions
- **Debt Tracking** — monitor repayment progress for each loan
- **Google Sheets Sync** — automatically push all data to a spreadsheet via Apps Script

### Tech Stack
| Technology | Purpose |
|---|---|
| `HTML / CSS / JavaScript` | Frontend (no framework) |
| `localStorage` | In-browser data persistence |
| `Google Apps Script` | Spreadsheet data integration |

### Setup
```bash
git clone https://github.com/NYAN68/Zaimu-kanri
cd Zaimu-kanri
# Open finance_manager.html in your browser — no server needed
```

### Google Sheets Integration
1. Create a new spreadsheet at [Google Sheets](https://sheets.google.com)
2. Open **Extensions → Apps Script**
3. Paste the contents of `apps_script.gs` and save
4. **Deploy → Deploy as web app** → copy the URL
5. Paste the URL into the app's **Settings page** and save

---

## 📸 スクリーンショット / Screenshots

> *(スクリーンショットをここに追加してください / Add screenshots here)*
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/b44ba8ee-873f-4834-8ca4-f370c714da9e" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/c31f6709-9e15-4cef-8dcf-2d210c79a028" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/4cf771a3-d763-43e6-8f40-898fe5f4a102" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/f332fd4d-cf27-4e0d-acc4-c5c114587c58" />



---

## 👤 Author

**NGUYEN THANH NHAN**  
🔗 [GitHub](https://github.com/NYAN68)
