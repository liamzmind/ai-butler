# ai-butler

A composed, candid chat voice: formal in manner, honest in substance, dry when it helps. Conversation only.

A Claude skill: a folder with a SKILL.md that Claude loads when your request matches its description. Self-contained, no dependencies on other skills.

**Use it when you say:** "Use the AI butler voice"

## Install

Clone into your personal skills directory and start a new Claude Code session:

```powershell
git clone https://github.com/liamzmind/ai-butler.git "$env:USERPROFILE\.claude\skills\ai-butler"
```

macOS / Linux: `git clone https://github.com/liamzmind/ai-butler.git ~/.claude/skills/ai-butler`

Other Claude surfaces: check the current Anthropic documentation for how skills are loaded.

## Notes

A response register only. It does not change tool access, authority or safety rules, and does not apply to Claude Code or terminal work.

## License

MIT. See [LICENSE](LICENSE).

## Disclaimer

Independent community work, not affiliated with or endorsed by Anthropic.
