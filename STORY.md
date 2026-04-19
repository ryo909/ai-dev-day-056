# Day056 Story — Runout Forecast Log

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day056専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: runout_forecast_log
- Mechanic: block_fill
- Input/Output: shelf_tokens -> urgency_shelf
- Audience Promise: 補充のタイミングを先に決められる。
- Publish Hook: 残量や使う頻度を自分で追加・編集すると、切れそうな順と買い足し日がログで揃う。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day056｜飲み切り見通しログ
補充タイミングを見通しやすくするためのツールです。
