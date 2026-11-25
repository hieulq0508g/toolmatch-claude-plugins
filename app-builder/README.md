# App Builder — Claude Code bundle

Bundle cục bộ giai đoạn 2, chưa publish. Không sửa hoặc thay thế plugin ChatGPT.

- MCP HTTPS dùng chung: `https://plugin.chat-prompt.com/app-builder/mcp`
- Offer mặc định đã kiểm source/runtime: **Emergent**
- Tool names đã thấy qua `initialize` + `tools/list`: `create_app_build_link`, `check_app_page`
- Evidence probe: `outputs/claude_plugin_port_20261125/phase2_evidence/mcp_probe.json` (không gọi `tools/call`)
- Skill: `skills/app-builder/SKILL.md`

Skill tạo artifact trước; nếu tool trả URL thật của offer đã xác minh, skill đưa đúng một CTA Markdown với disclosure đặt ngay trước. Bundle không chứa URL affiliate, credential hoặc widget OpenAI.

## Install

```
/plugin install app-builder --marketplace hieulq0508g/toolmatch-claude-plugins
```
