# Meridian_sample_fornote

## Forkして使う場合

このNotebookを自分用に変更したい場合は、GitHub上で Fork してください。

Fork後は、以下のような変更ができます。

チャネル名を実データに合わせて変更する
KPIを売上、CV、来店数などに変更する
コントロール変数を追加する
事前分布を調整する
予算制約を変更する
反実仮想シナリオを変更する

ただし、実データを使う場合は、個人情報・社内情報・クライアント情報をGitHubにアップロードしないよう注意してください。

## ダウンロードして使う場合

GitHub画面右上の Code ボタンから、ZIP形式でダウンロードできます。

Code → Download ZIP

ダウンロード後、NotebookをGoogle Colabにアップロードすれば実行できます。

Colabでは以下からアップロードできます。

ファイル → ノートブックをアップロード
注意点

このNotebookは、MMMの基本的な流れを体験するためのサンプルです。

実務で使う場合は、以下の点を必ず確認してください。

データの集計粒度
KPIの定義
広告費と広告接触量の対応関係
コントロール変数の妥当性
交絡要因の扱い
事前分布の設定
MCMCの収束
ホールドアウトでの予測精度
媒体ごとの現実的な予算制約

MMMの結果は、広告施策の意思決定を支援するためのものです。
結果をそのまま機械的に採用するのではなく、事業理解や媒体運用上の制約と合わせて解釈してください。

## 免責

このリポジトリは学習・検証目的のサンプルです。
分析結果やコードの利用によって生じた損害について、作成者は責任を負いません。

参考
Google Meridian 公式ドキュメント
Google Meridian GitHub Repository
Jin et al. (2017), Bayesian Methods for Media Mix Modeling with Carryover and Shape Effects
Ng, Wang, & Dai (2021), Bayesian Time Varying Coefficient Model with Applications to Marketing Mix Modeling
"""