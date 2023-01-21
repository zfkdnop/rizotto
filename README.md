# rizotto

rizotto is a minimalist, responsive [hugo](https://gohugo.io) theme inspired by terminal ricing aesthetics and slightly modified.

![Screenshot of the original risotto theme](https://raw.githubusercontent.com/joeroe/rizotto/master/images/screenshot.png)

## Install

The easiest way to install the theme is to clone this repository into your site's `themes` directory:

```shell
git clone https://github.com/joeroe/rizotto themes/rizotto
```

If your site is already a git repository, you can add the theme as a submodule instead:

```shell
git submodule add https://github.com/joeroe/rizotto.git themes/rizotto
```

## Update

If you installed the theme using `git clone`, pull the repository to get the latest version:

```shell
cd themes/rizotto
git pull
```

Or, if you added it as a git submodule:

```shell
git submodule update --remote
```

## Configure

To use the theme, add `theme = rizotto` to your site's `config.toml` or `config.yaml`.

See `exampleSite/config.toml` for the theme-specific parameters you need to add to your site's `config.toml` or `config.yaml` to configure the theme.

### Colour palettes

Colour palettes for the theme are defined using the [base16 system](https://github.com/chriskempson/base16):

| Base | Default colour | Used for | Examples |
| ---- | -------------- | -------- | -------- |
| 00   | Dark           | Background | Page background          |
| 01   | │              | Alt. background | Content background          |
| 02   | │              | In-text backgrounds | `<pre>`, `<code>`, `<kbd>`, `<samp>` |
| 03   | │              | Muted text | `:before` & `:marker` symbols |
| 04   | │              | Alt. foreground | Aside text          |
| 05   | │              | Foreground         | Content text         |
| 06   | │              |          |          |
| 07   | Light          |          |          |
| 08   | Red            |          |          |
| 09   | Orange         |          |          |
| 0A   | Yellow         | Highlights | Selected text, `<mark>` |
| 0B   | Green          | Primary accent | Logo          |
| 0C   | Cyan           | Active links | `a:active`, `a:hover`         |
| 0D   | Blue           | Links    | `a:link`, `a:visited`         |
| 0E   | Magenta        |          |          |
| 0F   | Brown          |          |          |

For light mode palettes, the sequence of 00–07 should be reversed (light to dark, not dark to light).
