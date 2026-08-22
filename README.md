# Welcome to QuickBall Translations

### Here you can contribute by translating to official [QuickBall](https://github.com/ChayanMistry/QuickBall)

### Steps

1. **Choose your language and start translating!**
2. **Read the guide below before translating**, especially if the string contains placeholders.
3. Once your translation is ready, submit a Pull Request to this repository.
4. After review, your translation will be included in the QuickBall app.

## Translation Guidelines

### Plain strings

These are the easy ones. Just translate the text naturally.

```xml
<string name="settings">Settings</string>
```

For example:

```xml
<string name="settings">সেটিংস</string>
```

Do **not** translate the `name`:

```text
settings
```

Only translate the text between the tags.

---

### Placeholders

Some strings contain placeholders that are replaced by the app at runtime.

```xml
<string name="welcome_user">Welcome, %1$s!</string>
```

`%1$s` is a **placeholder**. Never translate, remove, or modify it.

You can move it around to fit your language's natural word order:

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

### Things to keep in mind

1. **Never translate or modify resource names.**
2. **Never translate anything such as `%1$s`, `%1$d`, `%s`, `%d`, etc.**
3. You can move placeholders around when required by your language.
4. Keep XML tags and special characters intact.
5. Translate naturally rather than translating word-for-word.
6. If you're unsure about a translation, leave a comment in Weblate for discussion.

### Specialito

By translating QuickBall, you are officially a **nice, great and specialito person**. ❤️

Your contribution helps make QuickBall accessible to more people around the world. Thank you so much!

## Supported Languages

Translations will be listed here as they become available.

| Language | Contributors | Translation                             |
| -------- | ------------ | --------------------------------------- |
| English  | —            | [`values/`](translations/values/)       |
| Bangla   | —            | [`values-bn/`](translations/values-bn/) |

More languages will be added as the community contributes.

