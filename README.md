# Ephinea Tools

PSOBB Ephineaサーバー用の非公式ツール集（静的サイト）。
取り込んだデータはブラウザ内（localStorage）にのみ保存され、サーバーには送信されません。

- `/` — ランディング + キャラクターデータ取込み（`.psochar` / `.psobank` をそのまま読み込み）
- `/characters/` — 職業・Section ID・レベル・ステータス・マテリアル使用数・装備の一覧
- `/mag/` — マグ育成プランナー（仕上がりの目標から給餌手順を逆算）
- `/simulator/` — ステータスシミュレーター（装備効果・セット効果の内訳表示）
- `/inventory/` — インベントリ査定（Price guide準拠のPD評価）
- `/wishlist/` — 欲しいものリスト（ドロップ逆引き + 相場 + 所持突合）

各ページに英語版 `/en/...` があります。

生成物のみのリポジトリです（ビルドパイプラインはローカル管理）。
データ出典: [Ephinea PSO Wiki](https://wiki.pioneer2.net)
