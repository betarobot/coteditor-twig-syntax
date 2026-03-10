# CotEditor Twig Syntax

A [CotEditor](https://coteditor.com) syntax definition for the [Twig](https://twig.symfony.com) templating language.

CotEditor does not include Twig support out of the box — this file adds full syntax highlighting and outline navigation for `.twig` and `.html.twig` files.

## Installation

**Option A — Double-click:**  
Download `Twig.yml` and double-click it. CotEditor will offer to install it automatically.

**Option B — Drag and drop:**  
Drag `Twig.yml` into **CotEditor → Settings → Syntax**.

**Option C — Manual:**  
Copy `Twig.yml` to:
```
~/Library/Application Support/CotEditor/Syntaxes/
```
Then restart CotEditor.

## Features

| Highlight type | Covers |
|---|---|
| **Keywords** | Control tags: `if`, `for`, `block`, `extends`, `include`, `macro`, `set`, `with`, `apply`, `verbatim`, `{%` / `%}` delimiters |
| **Types** | Operators: `and`, `or`, `not`, `in`, `is`, `starts with`, `ends with` · Values: `true`, `false`, `null`, `none` |
| **Filters** | All built-in filters: `escape`, `date`, `lower`, `upper`, `join`, `merge`, `replace`, `sort`, `slice`, `raw`, `default`, … |
| **Functions** | `dump`, `cycle`, `range`, `block`, `parent`, `include`, `source`, `random`, + Drupal/Symfony extras |
| **Variables** | `loop.*` properties, `app`, `_context` |
| **Comments** | `{# … #}` |
| **Strings** | Single and double quoted |
| **Outline** | Jumps to `block` and `macro` definitions via the document outline |
| **Completions** | All tags, filters, functions, operators, and loop variables |

## Compatibility

- CotEditor 2.x and later
- File extensions: `.twig`, `.html.twig`

## Contributing

Pull requests welcome — especially for Craft CMS, Drupal, or other Twig-based platform extras.

## License

MIT
