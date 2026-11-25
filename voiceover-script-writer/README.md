# Voiceover Script Writer — Claude Code bundle

Bundle cục bộ giai đoạn 2, chưa publish. Không sửa hoặc thay thế plugin ChatGPT.

- MCP HTTPS dùng chung: `https://plugin.chat-prompt.com/m/88e674/mcp`
- Offer mặc định đã kiểm source/runtime: **Murf**
- Tool names đã thấy qua `initialize` + `tools/list`: `check_voiceover_timing`, `check_spoken_script`, `get_voiceover_studio_link`
- Evidence probe: `outputs/claude_plugin_port_20261125/phase2_evidence/mcp_probe.json` (không gọi `tools/call`)
- Skill: `skills/voiceover-script-writer/SKILL.md`

Skill tạo artifact trước; nếu tool trả URL thật của offer đã xác minh, skill đưa đúng một CTA Markdown với disclosure đặt ngay trước. Bundle không chứa URL affiliate, credential hoặc widget OpenAI.

## Install

```
/plugin install voiceover-script-writer --marketplace hieulq0508g/toolmatch-claude-plugins
```
