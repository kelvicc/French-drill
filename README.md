# 🇫🇷 フランス語文 全パターンドリル (Neural AI Audio Edition)

マイクロソフト Azure 高精度ニューラルAI音声（Henri 男性声 / Denise 女性声）による**全50パターン（1,500題＋基本モデル文50題）**、および**【最重要動詞 活用マスター＆瞬発クイズ】（全25動詞・150活用形）**を完全収録したフランス語スピーキング自動化教材です。

---

## 📦 【完全オフライン版】ZIPパッケージのダウンロード

電波の届かない機内、地下鉄、海外渡航先など、完全オフライン環境で音声を100%再生したい場合は、以下の同梱ZIPファイルをダウンロードして端末で解凍してご利用ください。

- **[📥 french_speaking_drill_neural_complete.zip](./french_speaking_drill_neural_complete.zip)**（約 25.2 MB / 全 2,129 音声ファイル同梱）

### オフライン版の使い方
1. 上記の `french_speaking_drill_neural_complete.zip` をダウンロードします。
2. 任意のフォルダに解凍（展開）します。
   - **iPhone**: 標準「ファイル」アプリでタップするだけで自動展開されます（または「Documents by Readdle」アプリ等）。
   - **Android**: 標準「Files」アプリ等で解凍します。
   - **PC / Mac**: ダブルクリック等で解凍します。
3. 展開されたフォルダ内の `index.html` をブラウザ（Safari, Chrome, Edge等）で開きます。
4. インターネット接続が一切ない状態でも、すべてのネイティブ音声（2,129ファイル）が即座に再生されます。

---

## 📱 オンライン（GitHub Pages）での学習

本リポジトリは GitHub Pages にも対応しており、用途に合わせて2種類の最適化プレイヤーを用意しています。

| プレイヤー | 推奨環境 | 特徴 |
| :--- | :--- | :--- |
| **[index.html](./index.html)**<br>（または [french_speaking_drill_neural_mobile.html](./french_speaking_drill_neural_mobile.html)） | **スマートフォン（iPhone / Android）** | ・1パターン集中モード（横スワイプ・次へボタンで1画面ずつ学習）<br>・親指タップに最適化した大きなタッチボタン<br>・ドリルB「対話再生（男女掛け合い）」<br>・ドリルC「フラッシュカード式（ワンタップ展開）」<br>・全パターン一覧ドロワーメニュー |
| **[index2.html](./index2.html)**<br>（または [french_speaking_drill_neural.html](./french_speaking_drill_neural.html)） | **PC / Mac / iPad / タブレット** | ・左側固定サイドバー目次付きワイドレイアウト<br>・10問連続自動再生（シャドーイングモード）<br>・再生速度切り替え（0.75x / 1.0x / 1.25x） |

---

## 📚 収録カリキュラム

### 1. 全50パターン・スピーキング自動化ドリル（全1,500問）
- **ドリルA（スロット置換・骨格無意識化）**: 500問（主語・動詞・目的語を反射置換）
- **ドリルB（構文変形・スイッチ対話）**: 500問（Henri男声 ➔ Denise女声のリアル対話スイッチ）
- **ドリルC（状況対応・瞬発発話フラッシュカード）**: 500問（0.5秒で口から出す瞬発ドリル）
- **各パターン基本モデル文**: 50文（SVG図解カード付き）

### 2. 🔥【新機能】最重要動詞 活用マスター表 ＆ 瞬発クイズドリル（全25動詞・150活用形）
- **第1群 -er規則動詞（8動詞）**: parler, aimer, habiter, travailler, chercher, manger, écouter, donner
- **第2群 -ir規則動詞（5動詞）**: finir, choisir, réussir, réfléchir, grandir
- **第3群 最重要不規則動詞（12動詞）**: être, avoir, aller, faire, vouloir, pouvoir, devoir, savoir, venir, prendre, mettre, dire
- **モード切り替え**:
  - `📖 活用マスター表`: 単数・複数の2列対比、IPA発音記号、音の急所・同音異字・リエゾン解説、1形ずつの通常(🔊)＆ゆっくり(🐢 0.75x)再生。
  - `🎯 瞬発クイズドリル`: 0.5秒反射フラッシュカード、自動音声再生、忘却防止リトライ機能、連続正解ストリークカウンター。

---

## 📂 ファイル構成

```text
French-drill/
├── french_speaking_drill_neural_complete.zip  # 完全オフラインZIPパッケージ（25.2MB）
├── index.html                                  # スマホ最適化プレイヤー（メイン入口）
├── index2.html                                 # PC/タブレット向けワイドプレイヤー
├── french_speaking_drill_neural_mobile.html    # スマホ最適化版スタンドアロンファイル
├── french_speaking_drill_neural.html           # PC/タブレット版スタンドアロンファイル
├── README_OFFLINE.txt                          # オフライン利用説明書
├── README.md                                   # 本リポジトリ説明書
├── manifest.json                               # PWAマニフェストファイル
├── sw.js                                       # Service Worker（PWAオフラインキャッシュ）
└── audio/                                      # ニューラルAI音声 MP3ファイル群 (計2,129ファイル)
    ├── *.mp3                                   # パターンドリル音声 (1,978ファイル)
    └── verbs/                                  # 重要動詞活用音声 (150ファイル)
```
