# AI_Agent_Skill_Standards

AIエージェント向けSkillの設計・実装・品質確認の基準をまとめるリポジトリです。現在の文書は初版草案です。

## 共通Skill設計標準

[共通Skill設計標準](standards/skill-design.md)では、`SKILL.md` の責務、詳細手順の段階的な読み込み、必須の安全条件、参照失敗時の挙動、配布前の受け入れ基準を定めます。

## 製品別の実装規約

製品ごとの読み込み制限、権限、検証・配布手順は各文書で管理します。

- [Antigravity CLI](platforms/antigravity.md) — 検証で観測した読み込み上限と暫定の設計目標
- [Claude Code](platforms/claude-code.md) — 対象環境で確認する項目
- [Codex](platforms/codex.md) — 対象環境で確認する項目
