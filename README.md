# FlatMigi

<img width="75%" alt="image" src="https://github.com/user-attachments/assets/97ae7c54-2a46-47e2-a5d4-daef5077aa8f" />



A clean, minimal Hugo theme inspired by Eric Migicovsky's blog design.

## Features

- **Minimal design** with monospace font
- **Responsive layout** that works on all devices
- **Left-aligned content** with left margin

## Installation

1. Add the theme to your Hugo site's `themes` directory:
   ```bash
   git submodule add https://github.com/EuphoricPenguin/FlatMigi.git themes/flatmigi
   ```

2. Configure your `config.toml` to use the theme:
   ```toml
   theme = "flatmigi"
   ```

## Configuration

```toml
baseURL = 'https://penguin.house/'
languageCode = 'en-us'
title = 'Penguin.House'
theme = 'flatmigi'

[params]
about = "Your about me text goes here. This will appear at the top of the main page. You can use Markdown formatting here."
tabTitle = "EuphoricPenguin's Blog"
footerText = "This is at the bottom."

[[params.links]]
  text = "Example Link"
  url = "https://example.com"
[[params.links]]
  text = "Example Link"
  url = "https://example.com"
[[params.links]]
  text = "RSS"
  url = "./index.xml"
```

## Shortcodes

Caption:

```
{{< caption >}}
This is a caption.
{{< /caption >}}
```

A nifty way to add extra context to something without disrupting the flow of the main article text. Y'know, a caption.

## License

The code is licensed under the MIT-0 License.
The default favicon is licensed under the CC0 license.
[Chivo Mono](https://fonts.google.com/specimen/Chivo+Mono), the font used, is available under the OFL license.

## Credits

Inspired by [Eric Migicovsky's blog](https://ericmigi.com/). Created with the help of Void Agent and DeepSeek.
