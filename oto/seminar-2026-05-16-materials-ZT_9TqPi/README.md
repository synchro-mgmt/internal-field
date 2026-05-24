# OTO 人の進化と豊かさの錬金術セミナー 2026/05/16
## Codex 向け資料化ハンドオフ

このフォルダは、5/16セミナー本番で話した内容を **スライド資料化** するためのハンドオフ資料です。
Codex側のこあが、このフォルダを読んで、画像生成＋スライド組み立てを実行してください。

---

## 役割分担

- **Claude側のこあ**（このフォルダを準備）
  - セミナー本番の書き起こしから、世界観・構成・各スライドのテキストを抽出
  - 画像生成プロンプトを GPT-4o 向けに最適化
  - デザイン仕様（配色・フォント・トーン）

- **Codex側のこあ**（あなた）
  - `image-prompts.md` の各プロンプトで GPT-4o ネイティブ画像生成
  - `slides-outline.md` のテキスト＋画像でスライド組み立て
  - 最終形式は HTML スライド or PowerPoint(.pptx) どちらでも

---

## ファイル構成

- `README.md` ← このファイル（指示書）
- `slides-outline.md` ← 各スライドのテキスト・構成（30スライド）
- `image-prompts.md` ← 各スライドに対応する画像生成プロンプト
- `design-guide.md` ← デザイン仕様（配色・フォント・トーン）

---

## 進め方の推奨

1. `design-guide.md` で全体のトーンを把握
2. `slides-outline.md` でスライドの順番・テキストを確認
3. `image-prompts.md` の各プロンプトで GPT-4o 画像生成
4. テキスト＋画像でスライドを組み立て
5. 最終的に PowerPoint(.pptx) or HTMLスライドとして出力
6. internal-field の oto/ 配下に成果物を置く（または別途）

---

## 元データ（参考）

- 5/16セミナー本番の書き起こし（100名超参加）
- 既存資料：`Sonic Wealth Evolution.pdf`（15ページ）
- 全体ロードマップ：`oto/launch-roadmap-ePvwbbfko4I.html`
- 進行台本・実施記録：`oto/seminar-script-VU4Zl6Wcrjg.html`

---

## 連絡

何か不明点あれば、Claude側のこあに聞いてください。
基本的に、上記4ファイルだけで動ける状態にしてあります。

— Claude側のこあ (COA)
Internal use only — OTO members
