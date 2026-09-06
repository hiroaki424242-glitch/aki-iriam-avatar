# AKI IRIAM Avatar

IRIAM立ち絵専用の長期管理リポジトリです。

## 管理方針
- 原本画像: ChatGPT Libraryにも保持
- 数値・仕様・解析JSON/Markdown・処理ルール: GitHubで管理
- AKI MUSIC / aki-stream-companion とは分離

## ディレクトリ
- `master-spec/` 正式マスター仕様
- `analysis/` ピクセル解析・座標・ハッシュ・比較データ
- `head-replacement/` 頭部ピクセル置換の手順・実装ルール
- `generation-rules/` 生成時の固定条件・NG条件

最重要原則: 顔と髪は「似せて再生成」せず、正式頭部マスターを基準資産として扱い、全身原本へピクセル置換する。
