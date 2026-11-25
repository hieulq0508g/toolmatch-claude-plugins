# Presentation Maker

Presentation Maker creates presentation outlines (argument, slide structure, evidence, charts, speaker notes), reviews decks and analyzes metrics.

## MCP endpoint

`https://plugin.chat-prompt.com/m/04fc8f/mcp`

## Tools

- `presentation_analyze_metrics`: analyzes data for a presentation
- `presentation_check_deck`: reviews a deck you provide
- `presentation_get_design_link`: returns a design handoff link

## Optional partner handoff

After the main result, the skill may offer an optional next step with **Gamma**. It uses only the URL returned by the tool call, places a financial disclosure sentence immediately before a single Markdown link, and never invents or modifies URLs. The plugin creator may earn a commission if you sign up through that link. The plugin itself contains no affiliate URLs or credentials.

## Install

```
/plugin install presentation-maker --marketplace hieulq0508g/toolmatch-claude-plugins
```

Privacy: https://toolmatch.net/privacy | Support: https://toolmatch.net/support | Terms: https://toolmatch.net/terms
