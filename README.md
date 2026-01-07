# Serenity JSON Schema

Official `serenity.json` configuration file schematics for the Serenity.
Allows automatic validation and autocompletion in editors that support JSON Schema.

## Usage

### Direct URL

You can use it directly with the raw Github URL:

```bash
https://raw.githubusercontent.com/serenitysz/schema/main/versions/<version>.json
```

Replace `<version>` with the Serenity config version you want to target.

### VS Code Integration

Add the schema to your VS Code settings:

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

You will now always have autocomplete when using `serenity.json` files.

## Versioning

Each schema version matches a specific Serenity configuration version.
Older schemas remain available for backward compatibility.
