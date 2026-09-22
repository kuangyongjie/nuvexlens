<div align="center">

[English](README.md) | [简体中文](README_ZH.md) | [日本語](README_JA.md)

<img src="images/logo.svg" width="120" height="120" alt="NuvexLens Logo">

# NuvexLens

**プロフェッショナル・スマート金融チャート＆クオンツ意思決定プラットフォーム**

*高性能チャートエンジン、ブラインドリプレイトレーニング、マルチファクタークオンツシグナル、クロスマッケートヒートマップ、多次元スクリーナー、詳細な投資リサーチナレッジベースを統合したワンストップ取引エコシステム*

[![Platform](https://img.shields.io/badge/プラットフォーム-Web-blue?style=flat-square)](https://nuvexlens.com)
[![Version](https://img.shields.io/badge/バージョン-v3.3-green?style=flat-square)](https://nuvexlens.com)
[![License](https://img.shields.io/badge/ライセンス-Commercial-orange?style=flat-square)](https://nuvexlens.com)

[公式サイト](https://nuvexlens.com) · [チャート](https://chart.nuvexlens.com/) · [シグナルセンター](https://chart.nuvexlens.com/signals/hub/strategy) · [マーケット](https://nuvexlens.com/quotes/) · [スクリーナー](https://nuvexlens.com/screener/) · [詳細分析](https://chart.nuvexlens.com/signals/analysis) · [ドキュメント](https://docs.nuvexlens.com)

</div>

---

## 免責事項と謝辞

- **商用ライセンスと知的財産**：**本プロジェクトは商用ソフトウェアであり、オープンソースではありません。** 無断での複製、配布、リバースエンジニアリング、商用転売は固く禁止されています。
- **チャートエンジンとコンポーネント**：本プロジェクトのチャートモジュールは、**TradingView** オープンチャートライブラリをベースに高度な二次開発を行っており、金融データ可視化のために TradingView 公式コンポーネントを組み込んでいます。
- **謝辞**：世界のフィンテック開発者コミュニティに卓越したプロフェッショナルなチャート基盤とエコシステムを提供してくださっている **[TradingView](https://www.tradingview.com/)** チームに心より感謝申し上げます。

---

## プラットフォーム概要

NuvexLens はプロのトレーダー、クオンツ投資家、金融学習者のために構築されました。マルチマーケットのリアルタイムストリーミングデータ、アルゴリズムシグナル、セクターヒートマップ、柔軟な条件スクリーニング、銘柄の詳細なテクニカル診断、包括的なナレッジベースを統合し、包括的な取引分析と意思決定をサポートします。

```
                    +---------------------------------------------+
                    |             NuvexLens エコシステム           |
                    +---------------------------------------------+
                                           |
     +-----------------+-------------------+-----------------+-----------------+
     |                 |                   |                 |                 |
[ スマートチャート ] [ シグナルセンター ] [ マーケット相場 ]  [ スクリーナー ]  [ 銘柄詳細分析 ]
 chart.             signals/hub         quotes/           screener/         signals/analysis
 - 最大10画面同期   - クオンツ戦略推奨  - 世界主要指数    - クロス市場条件  - パノラマ診断
 - 低遅延データ配信 - バックテスト追跡  - セクターマップ  - 財務/指標組合せ - 多時間枠コンセンサス
 - ブラインド復盤   - 機関保有追跡      - 市場心理指標    - 厳選プリセット  - サプライチェーン評価
 - Pineスクリプト   - テクニカル監視    - オンチェーン    - チャート連携    - 重要価格帯判定
     |                 |                   |                 |                 |
     +-----------------+-------------------+-----------------+-----------------+
                                           |
                   +-----------------------+-----------------------+
                   |                                               |
         [ ナレッジベースとヘルプ ]                        [ TrendRadar ニュース ]
           docs.nuvexlens.com                              trendradar.nuvexlens.com
           - 4言語体系的チュートリアル                     - 24時間365日金融速報
           - 厳選インジケーターライブラリ                  - マルチソースセンチメント
```

---

## 主要モジュールと直通リンク

| モジュール | コアポジショニング | 直通リンク | 主要機能とサブページ |
| :--- | :--- | :--- | :--- |
| **スマートチャート**<br>Smart Chart | プロ仕様のマルチアセットチャート＆ブラインド復盤トレーニング | [チャートを開く](https://chart.nuvexlens.com/) | 最大10画面同期、ミリ秒単位データ配信、100+標準＆VIPインジケーター、ブラインドリプレイトレーナー、Pine Script エンジン |
| **シグナルセンター**<br>Signals Hub | クオンツ戦略推奨、テクニカルシグナル監視、機関ポジション追跡 | [シグナルセンターを開く](https://chart.nuvexlens.com/signals/hub/strategy) | 戦略推奨と勝率検証、[テクニカルシグナル監視](https://chart.nuvexlens.com/signals/hub/technical)、[機関保有コンセンサス](https://chart.nuvexlens.com/signals/hub/holdings) |
| **マーケット相場**<br>Quotes | 世界主要市場の相場マトリクス、セクターヒートマップ、市場心理 | [マーケットを開く](https://nuvexlens.com/quotes/) | 主要指数リスト、[セクターヒートマップ](https://nuvexlens.com/quotes/heatmap)、[市場心理ダッシュボード](https://nuvexlens.com/quotes/sentiment)、[オンチェーン先物データ](https://nuvexlens.com/quotes/onchain-contracts) |
| **マルチ市場スクリーナー**<br>Screener | A株/香港株/米国株/暗号資産対応の多次元条件スクリーナー | [スクリーナーを開く](https://nuvexlens.com/screener/) | 全市場銘柄カバー、ファンダメンタルズ＆テクニカル複合絞り込み、検証済みプリセット戦略、チャートワンクリック連携 |
| **銘柄詳細分析**<br>Analysis | 銘柄コード直接入力によるパノラマ診断とテクニカルコンセンサス | [詳細分析を開く](https://chart.nuvexlens.com/signals/analysis) | 多時間枠テクニカルレーティング、クオンツスコアリング、サポート/レジスタンス自動判定、Serenity ボトルネック分析 |
| **ドキュメント・ヘルプ**<br>Help Center | 多言語対応の取引チュートリアル、インジケーター解説、利用ガイド | [ドキュメントを開く](https://docs.nuvexlens.com)<br>[ヘルプセンターを開く](https://help.nuvexlens.com) | 日/英/簡/繁の4言語対応、実践取引ワークフロー、指標戦略ライブラリ、クイックスタート＆FAQ |
| **TrendRadar ニュース**<br>TrendRadar | 24時間365日世界の金融速報、AIセンチメント、市場動向レーダー | [ニュースレーダーを開く](https://trendradar.nuvexlens.com/) | リアルタイム金融ニュース速報、AIエンティティ関連付け、マクロ経済イベントカレンダー |

---

## モジュール詳細

### 1. スマートチャート (Smart Chart)
- **直通リンク**: [https://chart.nuvexlens.com/](https://chart.nuvexlens.com/)
- **主な特徴**:
  - **超低遅延ストリーミング**: 分散 WebSocket ブリッジと専用ゲートウェイにより、ミリ秒レベルのリアルタイム板情報と歩み値を配信。
  - **マルチスクリーン＆複数時間枠同期**: 1〜10分割レイアウト対応。クロスヘア、タイムライン、描画ツールが完全同期。
  - **没入型ブラインドリプレイトレーナー (Replay Trainer)**:
    - 過去の任意の時点からティック単位の精度でチャートを再現。
    - 銘柄名と日時を非表示にするブラインドモードにより、後知恵バイアスを排除し、純粋なプライスアクションとテクニカル直感を育成。
    - 0.5倍〜10倍速の可変速再生および1本ごとのステップ再生に対応。
  - **100以上の指標と独自VIPインジケーター**: トレンドリボン、出来高プロファイル、大口資金フロー、フラクタル転換シグナルなど。
  - **Pine Script トランスパイラと実行環境**: Pine スクリプト構文をブラウザの独立サンドボックスで安全に実行。

### 2. シグナルセンター (Signals Hub)
- **直通リンク**: [https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
- **サブページ**:
  - **クオンツ戦略**: [https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
  - **テクニカルシグナル**: [https://chart.nuvexlens.com/signals/hub/technical](https://chart.nuvexlens.com/signals/hub/technical)
  - **機関保有追跡**: [https://chart.nuvexlens.com/signals/hub/holdings](https://chart.nuvexlens.com/signals/hub/holdings)
- **主な特徴**:
  - **高精度シグナル生成**: マルチファクターモデルに基づき、盤中・盤後に期待値の高い売買シグナルを提示。
  - **透明性の高い勝率検証**: 各戦略の過去の勝率、プロフィットファクター、最大ドローダウン、損益曲線を完全公開。
  - **テクニカルシグナル監視**: 移動平均線クロス、ボリンジャーバンド・スクイーズブレイク、RSI ダイバージェンスなどを常時スキャン。
  - **機関保有コンセンサス (Holdings Tracker)**: 米 SEC 13F、ARK ETF の日次売買、米連邦議会議員の取引情報を統合分析。

### 3. マーケット相場＆ヒートマップ (Quotes)
- **直通リンク**: [https://nuvexlens.com/quotes/](https://nuvexlens.com/quotes/)
- **サブページ**:
  - **セクターヒートマップ**: [https://nuvexlens.com/quotes/heatmap](https://nuvexlens.com/quotes/heatmap)
  - **市場センチメント**: [https://nuvexlens.com/quotes/sentiment](https://nuvexlens.com/quotes/sentiment)
  - **オンチェーン契約**: [https://nuvexlens.com/quotes/onchain-contracts](https://nuvexlens.com/quotes/onchain-contracts)
- **主な特徴**:
  - **世界主要指数一覧**: 米国（S&P 500、Nasdaq、Dow）、中国 A 株、香港ハンセン指数、主要暗号資産のリアルタイムボード。
  - **セクター別ツリーマップ (Treemap)**: 時価総額、変動率、売買代金に応じた動的表示。大業種から個別主導株まで多層ドリルダウン可能。
  - **ミクロ市場心理ダッシュボード**: 暗号通貨の Long/Short 比率、資金調達率、ソーシャルセンチメント指数を可視化。

### 4. マルチ市場スクリーナー (Screener)
- **直通リンク**: [https://nuvexlens.com/screener/](https://nuvexlens.com/screener/)
- **主な特徴**:
  - **グローバル市場網羅**: 中国 A 株（上海・深セン・北京）、米国株（NYSE、NASDAQ、AMEX）、香港株、暗号通貨を網羅。
  - **豊富な指標フィルター**: PER、PBR、ROE、配当利回り、売上高成長率、移動平均線の並び、出来高急増率など100以上の指標。
  - **実証済みプリセット戦略**: 「高配当・低バリュエーション」「出来高急増ブレイクアウト」「優良安定成長株」などの条件をワンクリック実行。
  - **エコシステム連携**: 抽出された銘柄をワンクリックでチャートや詳細分析画面に連携。

### 5. 銘柄詳細分析 (Stock Analysis & Research)
- **直通リンク**: [https://chart.nuvexlens.com/signals/analysis](https://chart.nuvexlens.com/signals/analysis)
- **主な特徴**:
  - **コード入力による即時レポート**: 任意の銘柄コードを入力するだけで、テクニカル、ファンダメンタルズ、資金流向を統合診断。
  - **マルチ時間枠テクニカルコンセンサス**: 15分足から週足まで、各種オシレーターと移動平均線による買い/売りシグナル強度を集計。
  - **重要価格帯の自動検出**: 出来高プロファイルとフィボナッチに基づく主要サポート/レジスタンスラインの自動描画。
  - **Serenity サプライチェーン評価**: 産業構造におけるチョークポイントと競争上の優位性（モート）を分析。

### 6. ドキュメント・ヘルプセンター (Help Center & Docs)
- **直通リンク**:
  - ドキュメント: [https://docs.nuvexlens.com](https://docs.nuvexlens.com)
  - ヘルプセンター: [https://help.nuvexlens.com](https://help.nuvexlens.com)
- **主な特徴**:
  - **4言語完全対応**: 日本語、英語、簡体字中国語、繁体字中国語に対応。
  - **体系的なトレーディング学習コース**: 初期設定からデータ構造、高度なPineプログラミング、クオンツ検証手法まで網羅。
  - **厳選インジケーターライブラリ**: トレンド、モメンタム、ボラティリティなどの主要スクリプトのアルゴリズムと実践的な活用法を解説。
  - **よくある質問 (FAQ)**: アカウント設定、クラウド同期、ショートカットキー一覧などを完備。

### 7. TrendRadar ニュース (TrendRadar)
- **直通リンク**: [https://trendradar.nuvexlens.com/](https://trendradar.nuvexlens.com/)
- **主な特徴**:
  - **24時間365日世界の金融ニュース配信**: 主要金融メディアや公的発表をリアルタイムに集約。
  - **AI による関連性抽出**: ニュース本文から関連する業界セクターや個別銘柄を自動タグ付け。
  - **マクロ経済イベントカレンダー**: 各国中銀の政策金利決定、CPI/PPI、主要企業決算日をタイムライン表示。

---

## 対応市場と資産クラス

| 資産クラス | 対象範囲 | 提供データ | 配信インフラ |
| :--- | :--- | :--- | :--- |
| **中国 A 株** | 上海・深セン・北京 全上場銘柄＆ETF | リアルタイム気配、歩み値、日足/分足、権利落ち修正データ | 低遅延 WebSocket ＋ 専用ゲートウェイ |
| **米国株** | NASDAQ、NYSE、AMEX 全銘柄 | プレマーケット、通常取引、アフターマーケットデータ | 国際金融ストリーミング回線 |
| **香港株** | 香港証券取引所 (HKEX) 全銘柄 | リアルタイム約定、板情報、過去データ | 香港専用データゲートウェイ |
| **暗号資産** | 主要現物・無期限先物取引ペア（BTC、ETH、SOL 等） | 秒未満価格配信、オーダーブック、ファンディングレート | 取引所直結 WebSocket インフラ |
| **先物・コモディティ** | 国内外の主要先物・株価指数先物 | リアルタイム価格、連続限月過去データ | 標準化先物アダプター |

---

## 推奨トレーディングワークフロー

1. **全体市況とセクターの確認**:
   - [マーケット相場](https://nuvexlens.com/quotes/) で世界指数の動向を把握。
   - [セクターヒートマップ](https://nuvexlens.com/quotes/heatmap) で資金流入のある注目業種を特定。
2. **スクリーナーによる候補銘柄の選定**:
   - [マルチ市場スクリーナー](https://nuvexlens.com/screener/) でプリセットや独自条件を用いて絞り込み。
   - 候補銘柄をクラウドウォッチリストに追加。
3. **シグナル検証と機関保有動向の確認**:
   - [シグナルセンター](https://chart.nuvexlens.com/signals/hub/strategy) でクオンツ戦略との適合性と過去勝率を確認。
   - [機関保有追跡](https://chart.nuvexlens.com/signals/hub/holdings) で大口ファンドの保有変化をチェック。
4. **チャート分析とエントリータイミングの決定**:
   - [スマートチャート](https://chart.nuvexlens.com/) で複数時間枠のチャートを同時に確認。
   - 出来高プロファイルやVIPインジケーターを用いてエントリー、利確、損切りの水準を明確化。
5. **ファンダメンタルズと企業競争力の検証**:
   - [銘柄詳細分析](https://chart.nuvexlens.com/signals/analysis) でサプライチェーンと堀（Moat）の強さを確認。
6. **リプレイトレーニングによる検証**:
   - チャートの [ブラインドリプレイ機能](https://chart.nuvexlens.com/) を使い、過去データで直感を研鑽。

---

## よくある質問 (FAQ)

<details>
<summary><b>デスクトップアプリのインストールは必要ですか？</b></summary>
<br>
インストールの必要はありません。NuvexLens は最新の Web 標準技術で構築されており、Chrome、Edge、Safari、Firefox などのブラウザで、デスクトップネイティブアプリと同等の快適な動作を実現しています。
</details>

<details>
<summary><b>データ配信の遅延時間はどのくらいですか？</b></summary>
<br>
価格データおよびシグナルは分散 WebSocket 経由でミリ秒単位の低遅延で配信されます。引け後のヒストリカルデータや財務データは毎日市場終了後に自動更新されます。
</details>

<details>
<summary><b>ウォッチリストやチャート設定は複数端末で同期されますか？</b></summary>
<br>
はい、完全に対応しています。ログイン状態であれば、ウォッチリスト、描画ツール、インジケーター設定、スクリーナーの保存条件がリアルタイムにクラウドアカウントへ暗号化同期されます。
</details>

<details>
<summary><b>ブラインドリプレイは通常のチャート確認と何が違いますか？</b></summary>
<br>
過去のチャートを普通にスクロールすると、未来の展開を知っていることによる後知恵バイアスが生じます。NuvexLens のブラインドモードは銘柄名と日付を完全に隠すため、実際の相場と同じ緊張感の中でテクニカル分析の検証が行えます。
</details>

---

## お問い合わせ・サポート

- 公式サイト: [nuvexlens.com](https://nuvexlens.com)
- ナレッジベース: [docs.nuvexlens.com](https://docs.nuvexlens.com)
- サポート・お問い合わせ: support@nuvexlens.com

---

<div align="center">

**NuvexLens** — トレーダーと学習者のためのスマート金融分析プラットフォーム

Empowering Professional Trading Decisions

Copyright © 2024-2026 NuvexLens. All Rights Reserved.

</div>
