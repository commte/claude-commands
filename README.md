# Claude Code Commands

Claude Code で使えるカスタムコマンドを集めたリポジトリです。
`.claude/commands/` ディレクトリに配置するだけで、開発補助・ログ記録・勤怠管理など、様々な操作を Claude に指示できるようになります。

## 📦 現在収録されているコマンド

| コマンド  | 説明                                                             |
| --------- | ---------------------------------------------------------------- |
| `/dakoku` | 出勤・退勤・休憩を打刻し、Markdown/JSON で記録。勤怠管理に使える |

※ 今後、`/memo`, `/todo`, `/report`, `/focus` などの追加を予定しています。

## 🛠 使い方（共通）

```bash
# プロジェクト直下で以下を実行
mkdir -p .claude/commands

# コマンドファイルを配置（例：/dakoku）
curl -o .claude/commands/dakoku.md https://raw.githubusercontent.com/commte/claude-commands/main/.claude/commands/dakoku.md
```
