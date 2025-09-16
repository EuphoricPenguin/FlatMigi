# FlatMigi

<img width="500" height="696" alt="image" src="https://github.com/user-attachments/assets/8a02c4f7-c2b5-4a1c-a945-7bc4e802ce12" />


A clean, minimal Hugo theme inspired by Eric Migicovsky's blog design.

## Features

- **Clean, minimal design** with monospace font (Inconsolata)
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

MIT License

## Credits

Inspired by the clean design of [Eric Migicovsky's blog](https://ericmigi.com/).
