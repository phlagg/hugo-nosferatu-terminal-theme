# Hugo Theme Tokyo Terminal

A brutally minimal, developer-focused Hugo theme designed to look exactly like a retro terminal environment, utilizing the **Tokyo Night** color palette and **JetBrains Mono Nerd Font**.

## Features
- Authentic `[user@host]~$` prompts.
- Pure Tokyo Night syntax highlighting.
- Blinking cursor animation on the homepage.
- 100% generic and configurable.

## Installation

1. Inside your Hugo project, run:
```bash
git submodule add https://github.com/rehan-hk/hugo-theme-tokyo-terminal.git themes/hugo-theme-tokyo-terminal
```

2. Update your `hugo.toml` to use the theme:
```toml
theme = "hugo-theme-tokyo-terminal"
```

## Configuration

Add your custom terminal prompt and social links to your `hugo.toml`:

```toml
[params]
  prompt = "rehan@dev:~$"
  
  [[params.social]]
    name = "github"
    url = "https://github.com/rehan-hk"
  [[params.social]]
    name = "linkedin"
    url = "https://linkedin.com/in/rehan-hk"
```

## License
MIT License.
