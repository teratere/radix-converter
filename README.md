# 🔢 Radix Converter - 基数変換コンバーター

2進数 (BIN)・8進数 (OCT)・10進数 (DEC)・16進数 (HEX) をリアルタイムに相互変換するシングルファイルWebツールです。  
直感的なビットタイル表示を備え、タップ操作によるビット反転（0/1切り替え）にも対応しています。

> **🌐 Live Demo:**  
> ブラウザですぐに使える公開版はこちら 👉 **[https://selfup.net/radix/](https://selfup.net/radix/)**

---

## 🌟 主な機能 (Features)

- **4基数リアルタイム相互変換:**
  - 10進数 (DEC) / 16進数 (HEX) / 2進数 (BIN) / 8進数 (OCT) のいずれかに入力すると、残りの基数へ即座に同期変換
  - 2進数の4ビット区切り自動フォーマット
- **インタラクティブ・ビットマップ:**
  - LSB（下位ビット）からMSB（上位ビット）までをタイル状に可視化
  - タイルをクリック／タップすることでビットを反転させ、すべての進数へ即時反映
  - 桁位置（bit番号）をタイルの下に明瞭配置し、4bit/8bitごとのスペーサーで高い視認性を確保
- **64ビット対応 (BigInt):**
  - JavaScript の BigInt を採用し、巨大な整数値や多ビット表現も安全に計算
- **クイックプリセット & コピー機能:**
  - `255 (0xFF)`, `1024 (1 KiB)`, `65535 (16bit MAX)` のワンタップ入力
  - 各基数フィールドのワンクリック・クリップボードコピー

---

## 🛠 開発について (About)

このプロジェクトは、**生成AI（Gemini）を活用したバイブコーディング（対話型プログラミング）**によって制作されたシングルファイルWebアプリケーションです。

- **企画・仕様設計・ディレクション:** teratere
- **コード生成・AIアシスタント:** Gemini
- **構成技術:** HTML5 / Tailwind CSS (CDN) / Vanilla JavaScript (BigInt API)

---

## 🔗 関連リンク (Links)

- 🚀 **Web App (Live):** [https://selfup.net/radix/](https://selfup.net/radix/)
- 🏠 **Apps Hub:** [https://selfup.net/](https://selfup.net/) （個人開発Webツール一覧）

---

## 📄 ライセンス (License)

MIT License
