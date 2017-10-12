## Style
```bash
$ bin/style [component-directory | style-file.{sss,css}]
```

This routine will take **component-directory** as a parameter

### Styling a Component
```bash
$ bin/style foo-bar
```

  - Searches for `foo-bar/index.sss` or `foo-bar/index.css` file as entry point.
  - _(optional)_  [Snuggsi Style Sheets](#snuggsi-style-sheets)
  - Leaves `index.min.css` as artifact. _(Great for appending to classic CSS bundles)_


### Cascading Style Sheets
```bash
$ bin/style index.css
```

  - Cross-platform CSS Properties support!


### Snuggsi Style Sheets
```bash
$ bin/style index.sss
```

  - No need for semicolons
  - `@import` inline styles
  - Removes comments from styles
  - Indentation based stylesheets