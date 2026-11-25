# Image Prompt Generator

Image Prompt Generator writes and reviews image prompts (subject, composition, lighting, style, negative constraints) and prepares portrait and headshot prompts.

## MCP endpoint

`https://plugin.chat-prompt.com/image/mcp`

## Tools

- `check_image_prompt`: reviews an image prompt
- `create_image_generation_link`: returns an image generation handoff link
- `prepare_professional_headshot`: prepares a professional headshot prompt and handoff

## Optional link

The plugin works fully without any link: it writes and checks image prompts. Only if you say you want to generate the image now, it may show one link to an online image generator. A sentence before the link states that it includes the plugin creator's affiliate code. The plugin contains no affiliate URLs or credentials.

## Install

```
/plugin install image-prompt-generator --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
