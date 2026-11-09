# DataStern plugins

Plugins that connect AI assistants to [DataStern](https://www.datastern.eu): official law texts with the wording in force on a given day, its history and a link to the original.

| Plugin | For | Folder |
| --- | --- | --- |
| DataStern | Claude (claude.ai, Claude Desktop, Claude Code) | [plugins/datastern](plugins/datastern) |

## Install in Claude Code

```
/plugin marketplace add datastern/plugins
/plugin install datastern@datastern
```

On claude.ai and Claude Desktop, install DataStern from the plugin directory once it is listed there.

Each plugin holds only instructions and the address of the DataStern server. It runs no code on your computer. See the plugin's README for what it sends and how to revoke access.

## Licence

MIT. DataStern provides source texts to help you, and you make the decision. Check the original text and date before relying on an answer. This isn't legal advice.
