# DataStern for Claude

Understand a legal question with Claude, using the official text. DataStern gives Claude the wording of a law as it stood on the day that matters, its history and a link to the original, so you can check each answer yourself.

## Use it

Connect DataStern from the plugin's **Connectors** tab and sign in. Connect a knowledge base in [DataStern](https://www.datastern.eu/explore). Then ask in your own words, for example:

- "How much notice does an employer have to give under Austrian law? Quote the provision and link to the original."
- "What changed in § 4 EStG since 2020?"

The plugin has two skills:

- **legal-question** finds the provision in force on the right day and answers with quotes, dates and links.
- **law-changes** shows the versions of a provision and what changed between two dates.

You need a DataStern account. The plugin only reads: it can't change anything in your account or anywhere else.

## Data

The plugin contains instructions for Claude and the address of the DataStern server, `https://www.datastern.eu/mcp`. It runs no code on your computer.

When Claude uses DataStern, it sends your search words, or the act, provision and date, to that server. DataStern records each call for limits and usage, as described in its [privacy policy](https://www.datastern.eu/privacy). Sign-in is through your DataStern account, and you can revoke access there at any time.

## Limits

DataStern provides source texts to help you, and you make the decision. Check the original text and date before relying on an answer. This isn't legal advice.

## Licence

The files in this plugin are licensed under the [Apache License 2.0](LICENSE), copyright 2026 Mykola Yevstihnieiev (DataStern). The licence covers these files only. It grants no right to use the DataStern name or logo, and no access to the DataStern service, which needs a DataStern account and is provided under its [terms](https://www.datastern.eu/terms). The law texts DataStern serves come from the Austrian Legal Information System (RIS) under CC BY 4.0.

## Support

See [datastern.eu](https://www.datastern.eu), [terms](https://www.datastern.eu/terms) and [privacy](https://www.datastern.eu/privacy).
