# AKI roomwear precision retouch — 2026-09-07

## Candidate v37

- Status: 修正候補（正式マスター未昇格）
- File: `AKI_roomwear_master2_precision_retouch_v37_1980x2970.png`
- Library file ID: `libfile_1f5c7a12e53c81918c9a8fb317e90c55`
- Canvas: 1980 × 2970 px
- Format: PNG / RGB
- SHA-256: `ef03f008a17d59c538986565ec4fb59b85d4d39128af0011410a86419214516b`

## 修正内容

- 向かって左側の長い襟足を、頭部マスター2の毛先に沿って局所復元
- 顔と胴体の接続部に残った重複首線を局所除去
- 顎下に見えていたグレーの帯状境界を除去
- 目・鼻・口・表情、衣装、小物、ポーズは維持

## 検証

- 400%・800%表示で首元と襟足を確認
- 最終PNGを読み戻し、1980 × 2970 pxであることを確認
- 最終局所調整の差分は594 px（変更範囲: x=908–948, y=404–489）
- 衣装・小物領域の差分は0 px

AKI本人の明示的な決定があるまでは正式マスターとして扱わない。
