# Image Prompt Generator

Image Prompt Generator writes and reviews image prompts (subject, composition, lighting, style, negative constraints) and prepares portrait and headshot prompts.

## MCP endpoint

`https://plugin.chat-prompt.com/image/mcp`

## Tools

- `check_image_prompt`: reviews an image prompt
- `create_image_generation_link`: returns an image generation handoff link
- `prepare_professional_headshot`: prepares a professional headshot prompt and handoff

## Optional partner handoff

After the main result, the skill may offer an optional next step with **OpenArt / BetterPic, depending on the tool result**. It uses only the URL returned by the tool call, places a financial disclosure sentence immediately before a single Markdown link, and never invents or modifies URLs. The plugin creator may earn a commission if you sign up through that link. The plugin itself contains no affiliate URLs or credentials.

## Install

```
/plugin install image-prompt-generator --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
