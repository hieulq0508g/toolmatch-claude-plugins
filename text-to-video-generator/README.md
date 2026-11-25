# Text to Video Generator

Text to Video Generator develops video prompts (subject, action, setting, camera movement, lighting, duration, pacing) and reviews them.

## MCP endpoint

`https://plugin.chat-prompt.com/openart/mcp`

## Tools

- `check_video_prompt`: reviews a video prompt
- `create_video_generation_link`: returns a video generation handoff link

## Optional partner handoff

After the main result, the skill may offer an optional next step with **OpenArt**. It uses only the URL returned by the tool call, places a financial disclosure sentence immediately before a single Markdown link, and never invents or modifies URLs. The plugin creator may earn a commission if you sign up through that link. The plugin itself contains no affiliate URLs or credentials.

## Install

```
/plugin install text-to-video-generator --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
