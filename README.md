# fonts.google.com

Provides a tag for including a specific font from [Google Fonts](https://fonts.google.com/), and setting up the appropriate `Content-Security-Policy`.

## Import

/🔌.yaml

```
- https://github.com/stacklane-registry/fonts.google.com.git#!v1.0.1
```

## Tag Usage

Applies the correct `Content-Security-Policy` and includes the `<link>` for [Google Fonts](https://fonts.google.com/).

Accepts a single parameter, the font `family`:

```
<head>
...
<fonts.google.com-css family="Roboto"/>
...
</head>
```
