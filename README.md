# Welcome to QuickBall Translations

Here you can contribute by translating the official [QuickBall](https://github.com/ChayanMistry/QuickBall) Android app!

### How to Contribute

1. **Choose your language** from the list below, or create a new translation directory if your language isn't listed yet.
2. **Read the guidelines below** before translating, especially regarding placeholders and XML formatting.
3. **Submit a Pull Request** with your updated or new translation file.
4. After review, your translation will be included in the QuickBall app.

---

## Supported Languages

| Language | Translation | Contributors |
| -------- | ------ | ------------ |
| English | [`values/strings.xml`](translations/values/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| Chinese (中文) | [`values-zh/strings.xml`](translations/values-zh/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| German (Deutsch) | [`values-de/strings.xml`](translations/values-de/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| Hindi (हिन्दी) | [`values-hi/strings.xml`](translations/values-hi/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| Italian (Italiano) | [`values-it/strings.xml`](translations/values-it/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| Portuguese (Português) | [`values-pt/strings.xml`](translations/values-pt/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |
| Spanish (Español) | [`values-es/strings.xml`](translations/values-es/strings.xml) | [@chayanforyou](https://github.com/chayanforyou) |

*More languages will be added as the community contributes.*

---

## Translation Guidelines

### Plain Strings

These are standard text strings. Translate only the text between the XML tags naturally.

```xml
<string name="settings">Settings</string>
```

For example (in Bangla):

```xml
<string name="settings">সেটিংস</string>
```

Do **not** translate the `name` attribute (e.g. `settings`). Only translate the inner text.

---

### Placeholders

Some strings contain placeholders that are replaced dynamically by the app at runtime.

```xml
<string name="welcome_user">Welcome, %1$s!</string>
```

`%1$s` is a **placeholder**. Never translate, remove, or alter placeholder formats.

You can reposition placeholders to fit your language's natural word order:

```xml
<string name="welcome_user">%1$s-কে স্বাগতম!</string>
```

Another example:

```xml
<string name="file_count">%1$d files</string>
```

Can become:

```xml
<string name="file_count">%1$dটি ফাইল</string>
```

---

### Guidelines to Remember

1. **Never translate or modify resource names (`name="..."`).**
2. **Never translate placeholders** such as `%1$s`, `%1$d`, `%s`, `%d`, etc.
3. You can adjust placeholder positions to match your language's syntax.
4. Keep XML tags, formatting, and special characters intact (e.g., `\n`, `&amp;`).
5. Translate naturally rather than doing literal word-for-word translations.
6. If you're unsure about a translation, leave a comment on your Pull Request or open an Issue for discussion.

---

### Specialito

By translating QuickBall, you are officially a **nice, great and specialito person**. ❤️

Your contribution helps make QuickBall accessible to more people around the world. Thank you so much!
