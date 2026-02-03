# FX_CALC 💹

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)

[English follows Japanese](#fx_calc-english)

## 🇯🇵 日本語

**FX_CALC** は、サイバーパンク・ターミナル風のデザインを採用した、ブラウザベースのFX（外国為替証拠金取引）損益計算ツールです。
スマートフォンでの操作に最適化されており、複数のポジションを同時に管理・計算できます。

### 🔗 デモ
**[ここをクリックしてアプリを開く](https://m1u13.github.io/)**
*(※公開後、ご自身のリポジトリURLに書き換えてください)*

### ✨ 主な機能

* **サイバーパンクUI:** 黒背景にネオングリーンやシアンを基調とした、没入感のあるターミナルデザイン。
* **複数ポジション管理:** 「ADD POS」ボタンで複数の建玉を追加し、個別に計算可能。
* **SYNC EXIT機能:** 1つのポジションの決済価格（EXIT）を変更すると、他のすべてのポジションの決済価格も同期して一括変更できます（スキャルピングやピラミッディングの決済計算に便利です）。
* **リアルタイムレート取得:** アプリ起動時およびポジション追加時に、API経由で現在のUSD/JPYレートを自動取得し、入力の手間を省きます。
* **損益自動計算:** Pips数と日本円での損益を即座に算出します。
* **スマホ対応:** タッチ操作しやすいステッパー入力とレスポンシブデザイン。

### 🛠 使い方

1.  **ポジション追加:** 画面下部の `+ ADD POS` を押してポジションを作成します。
2.  **売買区分:** `BUY` / `SELL` をタップして切り替えます。
3.  **Lot数入力:** 1 Lot = 1,000通貨 として計算されます（例: 1.0 = 1,000通貨, 10.0 = 10,000通貨）。
4.  **価格入力:** `ENTRY`（エントリー価格）と `EXIT`（決済価格）を入力します。`+` `-` ボタンで微調整が可能です。
5.  **SYNC機能:** 画面上部の `SYNC EXIT` にチェックを入れると、一番上のポジション（#1）のEXIT価格が全てのポジションに適用されます。

### 💻 技術スタック

* HTML5 / CSS3 (CSS Variables, Flexbox, Grid)
* Vanilla JavaScript (No Frameworks)
* ExchangeRate-API (レート取得用)

---

<a name="fx_calc-english"></a>

## 🇺🇸 English

**FX_CALC** is a browser-based Forex Profit/Loss calculator with a Cyberpunk/Terminal aesthetic.
Optimized for mobile use, it allows you to manage and calculate multiple positions simultaneously.

### 🔗 Demo
**[Launch App](https://m1u13.github.io/)**
*(Please replace with your actual GitHub Pages URL)*

### ✨ Features

* **Cyberpunk UI:** Immersive terminal design with neon colors and scanline effects.
* **Multi-Position Management:** Add and track multiple trading positions individually.
* **SYNC EXIT Mode:** When enabled, changing the Exit price of the first position automatically syncs the Exit price for all other positions (useful for closing basket trades).
* **Real-time Rates:** Automatically fetches the current USD/JPY rate via API to pre-fill inputs.
* **Instant Calculation:** Instantly calculates Pips gained/lost and P/L in JPY.
* **Mobile Friendly:** Responsive design with touch-friendly stepper inputs.

### 🛠 Usage

1.  **Add Position:** Tap `+ ADD POS` at the footer.
2.  **Toggle Type:** Switch between `BUY` and `SELL`.
3.  **Input Lots:** 1 Lot = 1,000 Currency Units (e.g., 1.0 = 1,000 units).
4.  **Set Prices:** Input your `ENTRY` and `EXIT` prices. Use the `+` / `-` buttons for fine-tuning.
5.  **Sync Mode:** Check `SYNC EXIT` at the top to lock all Exit prices to Position #1.

### 💻 Tech Stack

* HTML5 / CSS3 (CSS Variables, Flexbox, Grid)
* Vanilla JavaScript (No Frameworks)
* ExchangeRate-API (For fetching default rates)

---

### 📄 License

MIT License
