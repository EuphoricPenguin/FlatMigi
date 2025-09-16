# FlatMigi Hugo Theme

A clean, minimal Hugo theme inspired by Eric Migicovsky's blog design.

## Features

- **Clean, minimal design** with monospace font (Inconsolata)
- **Responsive layout** that works on all devices
- **Left-aligned content** with subtle left margin
- **Tight text spacing** for cohesive typography
- **Blue social links** matching Eric's style
- **Non-linked site title** (plain text)
- **Dash-only bullets** for list items
- **"Back to Home" link** on post pages
- **Visible border line** between title and social links

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

Add social links to your `config.toml`:

```toml
[params.social]
  twitter = "https://twitter.com/yourusername"
  bluesky = "https://bsky.app/profile/yourhandle"
  podcast = "https://www.youtube.com/channel/yourchannel"
  speaking = "https://www.chartwellspeakers.com/speaker/yourname"
  contact = "your@email.com"

[params]
  about = "Your about text here with *markdown* support"
```

## Customization

The theme uses Tailwind CSS for styling. You can customize colors, spacing, and other styles by modifying the `static/css/main.css` file.

## License

MIT License - feel free to use and modify as needed.

## Credits

Inspired by the clean design of [Eric Migicovsky's blog](https://ericmigi.com/).