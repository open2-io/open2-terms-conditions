# Open2 Terms and Conditions

Each language lives in its own file, named `terms.<locale>.md`:

| Locale | File |
| --- | --- |
| `es` (governing version) | [`terms.es.md`](terms.es.md) |
| `en` | [`terms.en.md`](terms.en.md) |

The frontend loads `terms.${locale}.md` for the user's language and falls back to `es` when the locale isn't available.

When editing the terms, update both files in the same commit so section numbers and the "Last updated" date stay in sync.
