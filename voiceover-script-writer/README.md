# Voiceover Script Writer

Voiceover Script Writer writes voiceover scripts for a target length, audience, platform and tone, checks timing and refines spoken lines.

## MCP endpoint

`https://plugin.chat-prompt.com/m/88e674/mcp`

## Tools

- `check_voiceover_timing`: checks script duration
- `check_spoken_script`: reviews spoken lines
- `get_voiceover_studio_link`: returns a voiceover studio handoff link

## Optional partner handoff

After the main result, the skill may offer an optional next step with **Murf**. It uses only the URL returned by the tool call, places a financial disclosure sentence immediately before a single Markdown link, and never invents or modifies URLs. The plugin creator may earn a commission if you sign up through that link. The plugin itself contains no affiliate URLs or credentials.

## Install

```
/plugin install voiceover-script-writer --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
