# タスク管理表

Codexはこのファイルを読み書きしてタスク進捗を管理する。
ステータスは `未着手` → `実行中` → `完了` の順に更新する。

## タスク一覧

| ID | タスク | 依存 | ステータス | 成果物パス | 備考 |
|---|---|---|---|---|---|
| T-00 | リポジトリ規模調査 | なし | 未着手 | docs/00_survey.md | 完了後T-31〜,T-41〜の分割行を追加 |
| T-10 | 全体構造の把握 | T-00 | 未着手 | docs/01_system_overview/ | |
| T-20 | データベース設計の抽出 | T-10 | 未着手 | docs/02_database/ | |
| T-30 | 画面一覧・画面遷移図 | T-10 | 未着手 | docs/03_screens/ | |
| T-31 | 個別画面仕様書（バッチ1） | T-30 | 未着手 | docs/03_screens/screens/ | 対象画面はT-00完了後に決定 |
| T-40 | 機能一覧・共通処理一覧 | T-20, T-30 | 未着手 | docs/04_business_logic/ | |
| T-41 | 個別機能仕様書（バッチ1） | T-40 | 未着手 | docs/04_business_logic/features/ | 対象機能はT-40完了後に決定 |
| T-50 | 非機能要件の抽出 | T-10 | 未着手 | docs/05_non_functional/ | |
| T-R0 | クロスチェック | T-31〜, T-41〜, T-50 | 未着手 | docs/review/cross_check.md | |
| T-R1 | 推測・要確認の棚卸し | T-R0 | 未着手 | docs/review/open_questions.md | T-R0と同時実行可 |
