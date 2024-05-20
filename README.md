# mkdocs-autolinktitle

This MkDocs plugin automatically fetches document titles for Markdown links, streamlining your documentation workflow.

## Setup

Install the plugin using pip:

```bash
pip install mkdocs-autolinktitle
```

Activate the plugin in `mkdocs.yml`:

```yaml
plugins:
  - search
  - autolinktitle
```

> **Note:** If you haven't added a plugins entry to your configuration file yet, you will likely want to include the search plugin as well. MkDocs enables it by default if there are no plugins entries set. When adding plugins, you need to enable it explicitly.


## Usage

Before:
```markdown
<path/to/target.md>
```

After:
```markdown
[Target Title](path/to/target.md)
```

## Thanks

- [MkDocs Plugins Documentation](https://www.mkdocs.org/dev-guide/plugins/)
- [MkDocs Plugin Template by Byrne Reese](https://github.com/byrnereese/mkdocs-plugin-template/)
