# DataStern plugins

Plugins that connect AI assistants to [DataStern](https://www.datastern.eu): official law texts with the wording in force on the day that matters and a link to the original.

| Plugin | For | Folder |
| --- | --- | --- |
| DataStern | Claude (claude.ai, Claude Desktop, Claude Code) | [plugins/claude/datastern](plugins/claude/datastern) |
| DataStern | Antigravity | [plugins/antigravity/datastern](plugins/antigravity/datastern) |

## Install in Claude Code

```
/plugin marketplace add datastern/plugins
/plugin install datastern@datastern
```

On claude.ai and Claude Desktop, install DataStern from the plugin directory once it is listed there.

## Install in Antigravity

Add the folder [plugins/antigravity/datastern](plugins/antigravity/datastern) as a plugin in Antigravity. It connects to `https://www.datastern.eu/mcp` and asks you to sign in with your DataStern account.

Each plugin holds only instructions and the address of the DataStern server. It runs no code on your computer. See the plugin's README for what it sends and how to revoke access.

## Licence

The files in this repository are licensed under the [Apache License 2.0](LICENSE), copyright 2026 Mykola Yevstihnieiev (DataStern). The licence covers these files only. It grants no right to use the DataStern name or logo, and no access to the DataStern service, which needs a DataStern account and is provided under its [terms](https://www.datastern.eu/terms). The law texts DataStern serves come from the Austrian Legal Information System (RIS) under CC BY 4.0.

DataStern provides source texts to help you, and you make the decision. Check the original text and date before relying on an answer. This isn't legal advice.
