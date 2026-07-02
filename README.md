# internal-field
社内向けナレッジポータル — 戦略リサーチ・レポート・ノウハウの蓄積基地

## サイト構造（2026-07-02 再編）

```
index.html            トップ（今の数字＝唯一の数値ソース／更新履歴）
company/              経営のOS
  roadmap.html          会社設計ロードマップ（v13）
  financial.html        財務マネジメント設計
  gap-analysis.html     ギャップ分析
  ubm/                  UBM継続ロードマップ＋archives/（過去のUBM報告）
projects/             4プロジェクト体制＋その他
  ldm/  synchro-juku/  oto/  moment/  external/
reports/              リサーチレポート（index.html が一覧。YYYY-MM-DD-テーマ.html で追加）
tools/                Deploy Tool
dashboards/ ldm/ oto/  旧URL（リダイレクトとして温存。新規追加禁止）
```

## 運用ルール
- LDM人数・MRRなどの数字は **index.html の stats-bar だけ** に書く（重複させない）
- レポート追加は `reports/` に日付入りファイル名で置き、`reports/index.html` にカード追加
- ファイル名にランダム文字列を付けない（`YYYY-MM-DD-テーマ.html`）
- 旧URLのリダイレクトスタブは削除しない
