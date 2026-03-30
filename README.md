# YGO 初動計算機

遊戯王OCGのデッキ初動確率を計算するブラウザアプリです。サーバー不要、全てブラウザ内で完結します。

**https://d4rulyn.github.io/ygo-syodou-calc/**

## 機能

- デッキ登録（PDF / XLSX 読み込み or 手入力）
- 初動組み合わせパターン定義（群ごとの管理、複製対応）
- 初動確率計算（群単体、群間AND/OR）
- XLSX 出力 / 読み込み（データの保存・復元）
- ブラウザ内にデッキを保存（localStorage）
- Undo / Redo
- ライト / ダーク / ハッカー テーマ

## 使い方

1. [アプリを開く](https://d4rulyn.github.io/ygo-syodou-calc/)
2. 「デッキ」タブで [遊戯王ニューロン](https://www.db.yugioh-card.com/yugiohdb/member_deck.action) からダウンロードしたPDFをドロップ、または手入力でカードを登録
3. 「組み合わせ」タブで初動パターンを定義
4. 「初動計算」タブで確率を計算

## プライバシー

入力したカード情報やアップロードしたファイルは外部サーバーに一切送信されません。
