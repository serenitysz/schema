# Serenity JSON Schema

Official `serenity.json` configuration file schematics for the Serenity.
Allows automatic validation and autocompletion in editors that support JSON Schema.

## How to Use

You can use it directly with the raw Github URL:

```bash
https://raw.githubusercontent.com/serenitysz/schema/main/versions/<version>.json
```

You can also put the URL in the VSCode settings:

```json
{
    "json.schemas": [
        {
            "fileMatch": ["serenity.json"],
            "url": "https://raw.githubusercontent.com/serenitysz/schema/main/versions/<version>.json"
        }
    ]
}
```
