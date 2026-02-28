# LalaPadGen2で設定可能なコンフィグ一覧
## トラックパッド（IQS9151）

- 左右トラックパッド設定は、`lalapadgen2_left.conf` と `lalapadgen2_right.conf` にあります。
- 以下は両ファイル（左右）で共通の現在設定値です。

| Kconfig名 | 現在設定値（左右共通） | 有効範囲/選択肢 | 概要 |
| --- | --- | --- | --- |
| `CONFIG_INPUT_IQS9151_ROTATE_0` | `y` | `y/n` | 座標系回転（0度） |
| `CONFIG_INPUT_IQS9151_RESOLUTION_X` | `2457` | `0..65535` | X解像度 |
| `CONFIG_INPUT_IQS9151_RESOLUTION_Y` | `3072` | `0..65535` | Y解像度 |
| `CONFIG_INPUT_IQS9151_ATI_TARGETCOUNT` | `400` | `0..1000` | ATIターゲット値 |
| `CONFIG_INPUT_IQS9151_DYNAMIC_FILTER_BOTTOM_SPEED` | `30` | `0..65535` | 動的フィルタ下限速度 |
| `CONFIG_INPUT_IQS9151_DYNAMIC_FILTER_TOP_SPEED` | `511` | `0..65535` | 動的フィルタ上限速度 |
| `CONFIG_INPUT_IQS9151_DYNAMIC_FILTER_BOTTOM_BETA` | `20` | `0..255` | 動的フィルタ下限ベータ |
| `CONFIG_INPUT_IQS9151_1F_TAP_ENABLE` | `y` | `y/n` | 1本指タップ有効化 |
| `CONFIG_INPUT_IQS9151_1F_TAP_MAX_MS` | `150` | `1..1000` | 1本指タップ最大時間(ms) |
| `CONFIG_INPUT_IQS9151_1F_TAP_MOVE` | `20` | `1..1000` | 1本指タップ移動しきい値 |
| `CONFIG_INPUT_IQS9151_1F_PRESSHOLD_ENABLE` | `y` | `y/n` | 1本指プレス&ホールド有効化 |
| `CONFIG_INPUT_IQS9151_1F_HOLD_MIN_MS` | `250` | `1..3000` | 1本指ホールド最短時間(ms) |
| `CONFIG_INPUT_IQS9151_CURSOR_INERTIA_ENABLE` | `y` | `y/n` | カーソル慣性の有効化 |
| `CONFIG_INPUT_IQS9151_CURSOR_INERTIA_DECAY` | `950` | `0..1000` | カーソル慣性減衰係数 |
| `CONFIG_INPUT_IQS9151_2F_TAP_ENABLE` | `y` | `y/n` | 2本指タップ有効化 |
| `CONFIG_INPUT_IQS9151_2F_TAP_MAX_MS` | `150` | `1..1000` | 2本指タップ最大時間(ms) |
| `CONFIG_INPUT_IQS9151_2F_TAP_MOVE` | `30` | `1..1000` | 2本指タップ移動しきい値 |
| `CONFIG_INPUT_IQS9151_2F_PRESSHOLD_ENABLE` | `y` | `y/n` | 2本指プレス&ホールド有効化 |
| `CONFIG_INPUT_IQS9151_2F_HOLD_MIN_MS` | `250` | `1..3000` | 2本指ホールド最短時間(ms) |
| `CONFIG_INPUT_IQS9151_SCROLL_Y_ENABLE` | `y` | `y/n` | 縦スクロール有効化 |
| `CONFIG_INPUT_IQS9151_SCROLL_X_ENABLE` | `y` | `y/n` | 横スクロール有効化 |
| `CONFIG_INPUT_IQS9151_2F_SCROLL_START_MOVE` | `50` | `1..2000` | 2本指スクロール開始しきい値 |
| `CONFIG_INPUT_IQS9151_SCROLL_INERTIA_ENABLE` | `y` | `y/n` | スクロール慣性の有効化 |
| `CONFIG_INPUT_IQS9151_SCROLL_INERTIA_DECAY` | `980` | `0..1000` | スクロール慣性減衰係数 |
| `CONFIG_INPUT_IQS9151_2F_PINCH_ENABLE` | `y` | `y/n` | 2本指ピンチ有効化 |
| `CONFIG_INPUT_IQS9151_2F_PINCH_START_DISTANCE` | `100` | `1..2000` | 2本指ピンチ開始距離しきい値 |
| `CONFIG_INPUT_IQS9151_2F_PINCH_WHEEL_GAIN_X10` | `40` | `1..100` | ピンチのホイールゲイン（x10） |
| `CONFIG_INPUT_IQS9151_3F_TAP_ENABLE` | `y` | `y/n` | 3本指タップ有効化 |
| `CONFIG_INPUT_IQS9151_3F_TAP_MAX_MS` | `180` | `1..1000` | 3本指タップ最大時間(ms) |
| `CONFIG_INPUT_IQS9151_3F_TAP_MOVE` | `30` | `1..1000` | 3本指タップ移動しきい値 |
| `CONFIG_INPUT_IQS9151_3F_PRESSHOLD_ENABLE` | `y` | `y/n` | 3本指プレス&ホールド有効化 |
| `CONFIG_INPUT_IQS9151_3F_HOLD_MIN_MS` | `250` | `1..3000` | 3本指ホールド最短時間(ms) |
| `CONFIG_INPUT_IQS9151_3F_SWIPE_THRESHOLD` | `200` | `0..1000` | 3本指スワイプ判定しきい値 |
