<div align="center">

<img src="https://raw.githubusercontent.com/magalhaesfelipe/toge-theme-vscode/main/images/logo.png"
        alt="Matcha Ceremony Logo"
        style="width:104px;height:104px;border-radius:20px;box-shadow:0 2px 24px #688360b0,0 1px 0 #eae2d67a inset;background:#202313;padding:7px;margin-bottom:-16px;">

<h1 style="
      font-family:'JetBrains Mono','IBM Plex Mono','monospace';
      font-size:2.65em;line-height:1.1;
      font-weight:900;
      margin:18px 0 4px 0;
      letter-spacing:1.4px;
      background:linear-gradient(100deg,#8AA573 25%,#C3CEB2 65%,#E8DCC4 90%);
      -webkit-background-clip:text;background-clip:text;color:transparent;
      text-shadow:0 2px 20px #A4C49B60, 0 1px 6px #A4C49B33;">
TOGE
<br />
<span style="
        font-size:.54em;
        margin-left:11px;
        background:linear-gradient(90deg,#E8DCC499 70%,#C3CEB288 100%);
        -webkit-background-clip:text;
        background-clip:text;
        color:transparent;
        font-weight:700;
        padding:4px 13px 4px 12px;
        vertical-align:middle;
        border-radius:8px;">
2026's 1st Edition
</span>
</h1>

  <div style="
        content:'';
        position: absolute;
        top: -90px; left: 50%; transform:translateX(-50%);
        opacity: 0.32;
        filter: blur(2.9px) saturate(110%) brightness(0.96);
        border-radius: 39px;
        box-shadow: 0 7px 64px #10160E66,0 1px 0 #C3CEB22A;
        pointer-events: none;
        z-index: 0;
        width: 630px;
        max-width: 90vw;
        height: 270px;
        background: url('https://i.postimg.cc/HsCyTyPs/bg-img.png') center/cover no-repeat;
    ">
  </div>

**Dark theme forged in the reflection of Bonsai trees.**

_Focus. Discipline. Code with the calm of a bonsai garden._

[Install](https://marketplace.visualstudio.com/items?itemName=FelipeMagalhaes.toge) · `#CodeLikeABushi`

> “Sharp contrast. Quiet mind. One clean cut.”
> Nothing flashy. Nothing extra. Only the way of the blade.

</div>

<!-- Later I'm going to add screenshots here, of few languanges such as JavaScript, TypeScript, JSON, CSS, Go, HTML, Terminal -->

## 🏯 Description

**Toge** is a dark theme with ink-black backgrounds and warm parchment text, accented by jade green, amber lacquer, and flashes of crimson and wisteria.

It is inspired by ancient Japanese Bonsai trees, martial arts (_bujutsu_, _kendo_, _iaido_) and the feudal shogun era: dojo discipline, samurai armor lacquer, ink-brush scrolls, and the stillness before the strike.

## 🍡 Color Palette

### Syntax Colors

| Color             | Hex       | Usage                                    |
| ----------------- | --------- | ---------------------------------------- |
| 📜 Washi Scroll   | `#E8DCC4` | Default editor text                      |
| 🏮 Amber Lacquer  | `#e2b178` | Strings, regex, symbols                  |
| 🪻 Wisteria Crest | `#BF79C3` | Numbers, characters, constants           |
| 🈯 Matcha Green   | `#7D9B76` | Entity names (functions, classes, types) |
| 🌸 Fallen Sakura  | `#e06c8f` | Comments                                 |
| ⛓️ Iron Gray      | `#737C8C` | Punctuation, escape sequences            |
| 🩸 Aka Red        | `#DF334A` | Invalid code                             |

### UI Colors

| Color            | Hex       | Usage                                        |
| ---------------- | --------- | -------------------------------------------- |
| 🎋 Bamboo Jade   | `#4d9375` | Buttons, links, progress bar, active borders |
| 🌑 Sumi Ink      | `#1a1919` | Editor background                            |
| ⬛ Black Lacquer | `#121212` | Sidebar, panels, tabs, status bar, title bar |
| 🕯️ Charcoal      | `#181818` | Hover, selection, current line               |
| ⚫ Dojo Floor    | `#191919` | Borders                                      |

### Terminal (ANSI)

| Color   | Normal    | Bright    |
| ------- | --------- | --------- |
| Red     | `#cb7676` | `#cb7676` |
| Green   | `#4d9375` | `#4d9375` |
| Yellow  | `#e6cc77` | `#e6cc77` |
| Blue    | `#6394bf` | `#6394bf` |
| Magenta | `#d9739f` | `#d9739f` |
| Cyan    | `#5eaab5` | `#5eaab5` |
| Black   | `#393a34` | `#777777` |
| White   | `#dbd7ca` | `#ffffff` |

## 📋 Features

- ✅ **Bracket colorization**: 6 colors for nested brackets
- ✅ **Git integration**: colors for added, modified, deleted, untracked, and conflicting files
- ✅ **Full terminal support**: 16 ANSI colors
- ✅ **Eye comfort**: dark, low-glare surfaces with warm text for long sessions
- ✅ **Minimal UI**: flat, mostly borderless focus with subtle separators

## ⬇️ Installation

### From VS Code

1. Launch VS Code Quick Open (Ctrl+P)
2. Paste the following command: ext install FelipeMagalhaes.toge
3. Press enter.

### From VS Code Marketplace

1. Open VS Code
2. Go to **Extensions** (`Ctrl+Shift+X`)
3. Search for `Toge`
4. Click **Install**
5. Go to **File** → **Preferences** → **Color Theme**
6. Select **Toge**

### Manual Installation

1. Download or clone the repository
2. Copy the `toge-theme` folder to:
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **macOS/Linux**: `~/.vscode/extensions/`
3. Restart VS Code
4. Select the theme in settings

## 🖥️ Supported Languages

- Ruby
- C / C++
- Go
- Rust
- JS / TS
- Python
- JSON / YAML
- Markdown
- Java
- PHP
- HTML / CSS / SCSS
- There is more...

## 🎚️ Recommended Settings

```json
{
	"editor.fontFamily": "'JetBrains Mono', 'Fira Code', Consolas, monospace",
	"editor.fontLigatures": true,
	"editor.fontSize": 15,
	"editor.lineHeight": 1.6,
	"editor.bracketPairColorization.enabled": true
}
```

## 🤝 Contributing

Found an issue or have an improvement idea?

1. Create an **Issue** with a description
2. Or submit a **Pull Request**

## 👤 Author & Publisher

**Felipe Magalhães**

- GitHub: [@magalhaesfelipe](https://github.com/magalhaesfelipe)

## 📄 License

<!-- I have to add on later :| -->

MIT License. See [LICENSE.txt](LICENSE.txt).

Copyright (c) 2026 Felipe Magalhães

## 🗻 Finally

Inspired by Japanese martial arts and the feudal shogun era.

The color palette draws from:

- 🈯 Bonsai/Matcha Green
- ⚔️ Katana steel and iron fittings
- 🏮 Lacquered samurai armor
- 📜 Washi scrolls and ink-brush calligraphy
- 🌸 Cherry blossoms falling in the dojo courtyard
- 🏯 Castle halls and torch-lit corridors

---

**Forged with 🌲, ⚔️ and discipline**

_“The art of bonsai teaches us patience and the beauty of embracing imperfections.”_
<br />
<br />
_"The sword is the soul of the samurai. Keep it sharp, keep the mind still."_
