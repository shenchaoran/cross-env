<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Usage](#usage)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Usage

Set env only for specific platform, available choices are
`Linux,Windows_NT,Darwin`

```json
{
  "scripts": {
    "build": "cross-env-os os=\"Linux,Windows_NT\" NODE_ENV=production webpack --config build/webpack.config.js"
  }
}
```
