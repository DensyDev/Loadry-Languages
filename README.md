# Loadry Languages

Community-maintained translations for [Loadry](https://github.com/DensyDev/Loadry).

## Structure

- `languages.json` contains the language catalog and locale metadata.
- `en_US.json` is the source locale and defines the required translation keys.
- Other `*.json` files contain translations for their respective locales.

## Contributing

To update a translation, edit its JSON file without changing the existing key structure. To add a
language, copy `en_US.json`, translate its values, and add its metadata to `languages.json`.

Every locale must contain exactly the same keys as `en_US.json`. Translation files are validated by
the Loadry build before they are included in the application.
