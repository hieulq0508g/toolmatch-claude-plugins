# Website Builder

Website Builder creates website briefs, sitemaps and landing page plans, and reviews page content you provide.

## MCP endpoint

`https://plugin.chat-prompt.com/website-builder/mcp`

## Tools

- `create_site_build_link`: returns a build handoff link for the brief
- `check_site_page`: reviews HTML or page content you supply

## Optional partner handoff

After the main result, the skill may offer an optional next step with **Emergent**. It uses only the URL returned by the tool call, places a financial disclosure sentence immediately before a single Markdown link, and never invents or modifies URLs. The plugin creator may earn a commission if you sign up through that link. The plugin itself contains no affiliate URLs or credentials.

## Install

```
/plugin install website-builder --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
