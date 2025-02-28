---
parent: Features
---

## Settings Pane

A settings modal is available in the app to allow you customize all the various aspects of the application including the theme, language, and styling options. The settings are specified in form of a JSON object. e.g.

```json
{
  "theme": "light",
  "language": "en-US",
  "addQueryDepthLimit": 6,
  "tabSize": 5
}
```

The available options are listed here:

### `theme` - Specifies the theme
Options include `light`, `dark`, `dracula`.

### `language` - Specifies the language
The options are any of the valid language codes according to: [https://support.crowdin.com/api/language-codes/](https://support.crowdin.com/api/language-codes/).

However not all the languages are translated. The available translations are [English, French, Español, Czech, German, Brazilian, Russian, Chinese Simplified, Japanese, Serbian, Italian, Polish, Korea](https://crowdin.com/project/altair-gql).

### `addQueryDepthLimit` - Specifies how deep the 'Add query' functionality would go
You can specify any valid number here.

### `tabSize` - Specifies the tab size in the editor
You can specify any valid number here.


### `theme.fontsize` - Specifies the base font size
_Default: 24_

### `theme.editorFontFamily` - Specifies the font family for the editors
Any valid CSS font family combinations can be used here.

### `disablePushNotification` - Specifies if native push notifications should be disabled
_Default: false_