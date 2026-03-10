# CotEditor Twig Syntax

A [CotEditor](https://coteditor.com) syntax definition for the [Twig](https://twig.symfony.com) templating language.

CotEditor does not include Twig support out of the box — this file adds syntax highlighting and outline navigation for `.twig` and `.html.twig` files.

## Installation

**Option A — Import via menu:**
In CotEditor, go to **Settings → Format → Syntax** and click the import button (↓) at the bottom left. Select `Twig.yml`.

**Option B — Manual:**
Copy `Twig.yml` to:
```
~/Library/Application Support/CotEditor/Syntaxes/
```
Then restart CotEditor.

After installing, open a `.twig` file and select **Twig** from the syntax pop-up in the toolbar or status bar.

## What gets highlighted

| Color role | What it covers |
|---|---|
| **Keywords** | Entire `{% … %}` statement blocks |
| **Variables** | Entire `{{ … }}` output expression blocks |
| **Comments** | `{# … #}` comment blocks |
| **Strings** | Single- and double-quoted string literals |
| **Numbers** | Numeric literals |
| **Types** | `true`, `false`, `null`, `none` |
| **Commands** | Twig-specific functions: `dump`, `cycle`, `range`, `random`, `parent`, `striptags`, `json_encode`, `url_encode`, `nl2br` |
| **Outline** | Jumps to `block` and `macro` definitions via ⌃6 / document outline |

## Autocomplete

The syntax includes completions for all built-in tags, filters, functions, operators, and `loop.*` variables (trigger with F5 / ESC in CotEditor).

## Compatibility

- CotEditor 2.x and later (YAML syntax format)
- File extensions: `.twig`, `.html.twig`
- Works with Symfony, Drupal, Craft CMS, and any Twig-based project

## Contributing

Pull requests welcome — especially for platform-specific extras (Drupal functions, etc.).

## License

MIT
