# AKI IRIAM Avatar

IRIAM立ち絵専用の長期管理リポジトリです。

## 最初に読む資料

- [AKI IRIAM立ち絵 制作基準書](generation-rules/production-handbook.md) — AKIの希望、絶対条件、毎回の工程、失敗防止、保存ルール
- [毎回のQAチェックリスト](generation-rules/qa-checklist.md) — 400〜800%・1〜数px単位の完成検査
- [現在のプロジェクト状態](analysis/current-project-state.json) — 出力仕様、運用モード、最新候補、ハッシュ
- [正式頭部マスター仕様](master-spec/head-master.md)
- [正式頭部ピクセル置換フロー](head-replacement/pixel-replacement-workflow.md)

## 管理方針

- 原本画像・完成PNG: ChatGPT Libraryにも保持
- 数値・仕様・解析JSON/Markdown・処理ルール: GitHubで管理
- 必要な候補画像: 正式マスターと分離した候補用ディレクトリで管理
- 過去候補は上書き・削除しない
- AKI本人の明示的承認なしに候補を正式マスターへ昇格させない
- AKI MUSIC / aki-stream-companion とは分離

## ディレクトリ

- `master-spec/` 正式マスター仕様
- `analysis/` 現行のピクセル解析・座標・ハッシュ・比較データ
- `head-replacement/` 現行の頭部ピクセル置換工程
- `generation-rules/` 制作基準書・QA・固定条件・NG条件
- `archive/` 旧解像度・旧座標・過去の検証記録
- `candidates/` 必要に応じて保存する未昇格候補
- `thumbnails/` AKI本人が採用したIRIAM用サムネイルと制作記録

## 現役資料と履歴資料

現役の判断には「最初に読む資料」だけを使用します。初期1024×1536検証の座標や過去の探索値は `archive/` に保存し、1980×2970の現行制作へ流用しません。

## 最重要原則

顔と髪は「似せて再生成」しない。正式頭部マスターを固定基準資産として扱い、全身原本へピクセル置換する。

最終出力は **1980 × 2970 px PNG**。1024 × 1536 pxはプレビュー・検証用に限る。
