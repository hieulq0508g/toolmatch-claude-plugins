# Text to Video Generator

Text to Video Generator develops video prompts (subject, action, setting, camera movement, lighting, duration, pacing) and reviews them.

## MCP endpoint

`https://plugin.chat-prompt.com/openart/mcp`

## Tools

- `check_video_prompt`: reviews a video prompt
- `create_video_generation_link`: returns a video generation handoff link

## Optional link

The plugin works fully without any link: it writes and checks video prompts. Only if you say you want to generate the video now, it may show one link to an online video generator. A sentence before the link states that it includes the plugin creator's affiliate code. The plugin contains no affiliate URLs or credentials.

## Install

```
/plugin install text-to-video-generator --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
