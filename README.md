# API・JSON・CSV・翻訳比較ツール

api-json-csv-translation-compare は API、CSV、翻訳文言を横断確認する開発者/運用者 向けの closed alpha プロダクトです。APIレスポンス、JSON、CSV、翻訳キーを同じ比較モデルへ正規化して差分確認する。

## Source

- PICKUP Rank: 48
- Domain / Idea No: WindowsApp / 11
- Repository: api-json-csv-translation-compare
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/WindowsApp/created_idea_011_api-json-csv-translation-compare`
- 同梱ZIP: `D:/AI/WindowsApp/created_idea_011_api-json-csv-translation-compare/idea_011_api-json-csv-translation-compare.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- ui/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/api-json-csv-translation-compare-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

