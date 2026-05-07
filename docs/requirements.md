# 要件定義

## 目的

API・JSON・CSV・翻訳比較ツール は、API、CSV、翻訳文言を横断確認する開発者/運用者 が APIレスポンス、JSON、CSV、翻訳キーを同じ比較モデルへ正規化して差分確認する。

## Source

- PICKUP Rank: 48
- Domain / Idea No: WindowsApp / 11
- Repository: api-json-csv-translation-compare
- created_idea: `D:/AI/WindowsApp/created_idea_011_api-json-csv-translation-compare`
- ZIP: `D:/AI/WindowsApp/created_idea_011_api-json-csv-translation-compare/idea_011_api-json-csv-translation-compare.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: sourceName、targetName、key、expectedValue を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `semanticMismatch` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

