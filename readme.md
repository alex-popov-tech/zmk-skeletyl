# Skeletyl ZMK Config

ZMK firmware configuration for the [Bastard Keyboards Skeletyl](https://bastardkb.com/skeletyl/) (3x5 split, 36 keys).

## Layers

### GALLIUM (Layer 0) -- English

[Gallium Colstag](https://github.com/GalileoBlues/Gallium) alpha layout with rearranged punctuation.

```
 ┌─────┬─────┬─────┬─────┬─────┐           ┌─────┬─────┬─────┬─────┬─────┐
 │  B  │  L  │  D  │  C  │  V  │           │  J  │  Y  │  O  │  U  │  /  │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │  N  │  R  │  T  │  S  │  G  │           │  P  │  H  │  A  │  E  │  I  │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │  X  │  Q  │  M  │  W  │  Z  │           │  K  │  F  │ . : │ , ; │  '  │
 └─────┴─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┴─────┘
             │ ESC │ SPC │ SYM │           │ BSP │ SFT │ RET │
             └─────┴─────┴─────┘           └─────┴─────┴─────┘
```

### UA (Layer 1) -- Ukrainian

Standard Ukrainian layout with mod-morphs for missing letters (Х, Ю) and punctuation.

```
 ┌─────┬─────┬─────┬─────┬─────┐           ┌─────┬─────┬─────┬─────┬─────┐
 │  Й  │  Ц  │  У  │  К  │ Е/Є │           │  Н  │ Г/Ґ │  Ш  │  Щ  │ З/ʼ │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │  Ф  │ І/Ї │  В  │  А  │  П  │           │  Р  │  О  │  Л  │  Д  │  Ж  │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │  Я  │  Ч  │  С  │  М  │  И  │           │  Т  │  Ь  │ ./Х │  Б  │ '/Ю │
 └─────┴─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┴─────┘
             │ ESC │ SPC │ SYM │           │ BSP │ SFT │ RET │
             └─────┴─────┴─────┘           └─────┴─────┴─────┘
```

### SYM (Layer 2) -- Symbols & Numbers

```
 ┌─────┬─────┬─────┬─────┬─────┐           ┌─────┬─────┬─────┬─────┬─────┐
 │ | \ │ [ { │ ( # │ { $ │     │           │     │ } & │ ) * │  ]  │  `  │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │  1  │  2  │ 3/← │ 4/→ │  =  │           │  -  │ 7/↓ │ 8/↑ │ 9/< │ 0/> │
 ├─────┼─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┼─────┤
 │     │     │ F11 │  5  │ TAB │           │ TAB │  6  │ F12 │     │     │
 └─────┴─────┼─────┼─────┼─────┤           ├─────┼─────┼─────┼─────┴─────┘
             │     │     │     │           │     │     │     │
             └─────┴─────┴─────┘           └─────┴─────┴─────┘
```

## Features

- **Mod-morphs**: tap for primary, shift for secondary (e.g. `. :`, `, ;`, `Е/Є`, `І/Ї`)
- **Sticky-key combos**: vertical top+home column combos for Ctrl, Cmd, Opt (both hands)
- **Language switch**: inner thumb combo (SYM+BSP) toggles Gallium/UA with Karabiner F14/F15 integration
- **F11/F12**: on SYM layer below 3 and 8 (Neovim terminal, Wezterm leader)

## Building

Push to `main` to trigger GitHub Actions firmware build.
