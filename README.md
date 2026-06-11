# Contributing

Thanks for helping improve CS2 Bot Improver! The most useful contributions are **translation fixes**, and UI/markup fixes are welcome too.

## Where the translations live

All UI text is in `src/i18n/`:

- **`keys.ts`** : the English source of truth. It defines every translation key and its English text. English is also the fallback for any key a locale is missing.
- **`dictionary.ts`** : one block per locale (e.g. `french`, `schinese`, `brazilian`). Each block maps the same keys to that language.

### Fixing or improving a translation

1. Find your language's block in `src/i18n/dictionary.ts`.
2. Edit the value of the key you want to improve while keeping the key exactly as-is.

### Keep placeholders intact

Some strings contain a placeholder like `{n}` (e.g. `"{n} missing"`). Keep the `{n}` in your translation; only move/translate the words around it.
