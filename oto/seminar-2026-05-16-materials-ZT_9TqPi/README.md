# OTO 人の進化と豊かさの錬金術セミナー 2026/05/16
## ChatGPT Images 2.0 (GPT-5.5) 向け 資料化ハンドオフ

このフォルダは、5/16セミナー本番で話した内容を **スライド資料化** するためのハンドオフ資料です。
**ChatGPT Images 2.0**（https://chatgpt.com/ja-JP/images/）で画像を生成し、スライドに組み立てます。

---

## 役割分担

- **Claude側のこあ**（このフォルダを準備）
  - セミナー本番の書き起こしから、世界観・構成・各スライドのテキストを抽出
  - 画像生成プロンプトを ChatGPT Images 2.0 向けに最適化
  - デザイン仕様（配色・フォント・トーン）

- **堀内さん（または実行者）**
  - `image-prompts.md` の各プロンプトを **ChatGPT Images 2.0** にコピペして画像生成
  - 生成された画像をダウンロード
  - `slides-outline.md` のテキスト＋生成画像でスライド組み立て
  - 最終形式は PowerPoint(.pptx) or Keynote or HTML どれでも

---

## ファイル構成

- `README.md` ← このファイル（指示書）
- `slides-outline.md` ← 各スライドのテキスト・構成（30スライド）
- `image-prompts.md` ← 各スライドに対応する画像生成プロンプト（ChatGPT Images 2.0 向け）
- `design-guide.md` ← デザイン仕様（配色・フォント・トーン）

---

## 進め方の推奨

1. `design-guide.md` で全体のトーンを把握
2. `slides-outline.md` でスライドの順番・テキストを確認
3. `image-prompts.md` の各プロンプトを **ChatGPT Images 2.0** にコピペ
   - URL: https://chatgpt.com/ja-JP/images/
   - 1枚ずつ生成 → ダウンロード
   - 全32枚（30本番 + オプション2枚）
4. テキスト＋画像でスライドを組み立て（PowerPoint推奨）
5. internal-field の oto/ 配下に成果物を置く（または別途）

---

## ChatGPT Images 2.0 を使う時のコツ

- プロンプトは **英語で書いてある通りそのままコピペ** がベスト（細かい指示がそのまま反映される）
- 同じスタイル指定が全プロンプトに入ってるので、画像全体の統一感が出る
- 生成後、気に入らなければ「もう少し〜」と日本語で追加指示OK
- 1枚あたり数十秒で生成される

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
