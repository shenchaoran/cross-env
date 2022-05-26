- [Usage](#usage)

Set env only for specific platform, available choices are
`Linux,Windows_NT,Darwin`. Support set min node version by `minVersion`

```json
{
  "scripts": {
    "build": "cross-env-os os=\"Linux,Windows_NT\" minVersion=17 NODE_ENV=production webpack --config build/webpack.config.js"
  }
}
```
