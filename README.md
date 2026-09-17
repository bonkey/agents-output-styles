# agents-output-styles

Output styles for [Claude Code](https://code.claude.com/docs/en/output-styles).

## Styles

| Style | What it does |
| --- | --- |
| STE Concise | Result first, in ASD-STE100 Simplified Technical English. Keeps Claude Code's coding instructions. |

## Install

Add the marketplace and install the plugin:

```
/plugin marketplace add bonkey/agents-output-styles
/plugin install agents-output-styles@bonkey
```

Select the style with `/config` under **Output style**, or set it in a settings file:

```json
{
  "outputStyle": "agents-output-styles:STE Concise"
}
```

## Try it without installing

```
claude --plugin-dir /path/to/agents-output-styles
```

## License

MIT
