# gorgeous

my obsidian theme. serif headings, purple accent, dark as possible.
still learning css and obsidian's theming system — used [@kepano's Minimal](https://github.com/kepano/obsidian-minimal) heavily as a reference for how to do things properly.

---

## what it looks like

- georgia serif headings, clean sans body text
- really dark dark mode (the sidebar and editor are different shades so there's actual depth)
- purple accent throughout — links, checkboxes, active items
- blockquotes are just a quiet bar on the left, no box
- h6 is uppercase and small, kind of like a label

## install

**community themes:** Settings → Appearance → Themes → Browse → search "Gorgeous"

**manual:** clone this repo into `.obsidian/themes/` in your vault, then pick it in Settings → Appearance

## changing the accent color

the whole color system is built around three variables at the top of `theme.css`:

```css
--accent-h: 270;   /* hue — 270 is purple, 0 is red, 120 is green */
--accent-s: 30%;   /* saturation */
--accent-l: 58%;   /* lightness */
```

change the hue and everything updates automatically.

## works on

Obsidian 1.9.4+ · Mac · Windows · Linux · iOS · Android

---

made by [Damien Blackwood](https://github.com/DamienBlackwood)
