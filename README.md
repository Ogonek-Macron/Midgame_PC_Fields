# Midgame_PC_Fields
テトリスの途中パフェの地形に関する研究

## テト譜内の確率について
* 途中ライン消去 1 回以内
* 最後の 1 手のみソフトドロップ許可
* bag 内のどの位置からの場合も同様に確からしいと仮定
* 事前の bag 間ミノ持ち越し無し
* パフェ中の bag 間ミノ持ち越し有り

## 探索範囲
* 3 ミノ以内にあっては、幅 6 × 高さ 6 の範囲内、4 ミノ以上にあっては、幅 6 × 高さ 4 の範囲内
* 途中に高さ MAX の列無し
* 浮いたブロック無し
