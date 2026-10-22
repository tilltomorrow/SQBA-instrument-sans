# SQBA Instrument Sans

A custom version of [Instrument Sans](https://github.com/Instrument/instrument-sans), made by [Van Lennep Amsterdam](https://www.vanlennep.eu) for SQBA.

Where Instrument Sans is a variable family with width, weight and italic, SQBA Instrument Sans is a fixed four-style family with a set of alternate letterforms built in as the default. It is meant to be simple to install and use: one family in the font menu, with bold and italic working through the usual buttons and shortcuts.

## Styles

| Style | Width (wdth) | Weight (wght) |
| --- | --- | --- |
| Regular | 94 | 500 |
| Italic | 94 | 500 |
| Bold | 94 | 700 |
| Bold Italic | 94 | 700 |

All four are static fonts, style-linked as one family.

## Built-in letterforms

The following stylistic sets from Instrument Sans are the default forms in this version. No OpenType settings are needed.

| Set | Change |
| --- | --- |
| `ss01` | Round punctuation, tittles and diacritics |
| `ss03` | "y" with a rounded descender |
| `ss06` | "M" with angled strokes |
| `ss07` | "G" without the spur |
| `ss08` | "J" with extended terminal |
| `ss09` | "Q" with alternate tail |
| `ss10` | "2" with alternate spine |
| `ss12` | "$" and "¢" with solid vertical stroke |

## OpenType features

Still available as optional features:

- `ss02` Single-story "a"
- `ss04` "K" with crossed arm and leg
- `ss05` "R" with straight leg
- `ss11` Alternate "&" (Et-style ampersand)
- `case` Case-sensitive punctuation
- `liga` Standard ligatures
- `pnum` / `tnum` Proportional and tabular figures

## Files

- `delivery/` The release package: OTF fonts, WOFF2 webfonts, specimen, README (install and usage guide), FONTLOG and OFL.
- `sources/SQBAInstrumentSans.glyphs` and `sources/SQBAInstrumentSans-Italic.glyphs` The modified Glyphs sources.
- `sources/InstrumentSans.glyphs` and `sources/InstrumentSans-Italic.glyphs` The original Instrument Sans sources, kept for reference.

## Building

The release fonts were built with [fontmake](https://github.com/googlefonts/fontmake):

```
fontmake -g sources/SQBAInstrumentSans.glyphs -i -o otf --overlaps-backend pathops
fontmake -g sources/SQBAInstrumentSans-Italic.glyphs -i -o otf --overlaps-backend pathops
```

## Credits

Original design: Instrument Sans by [Rodrigo Fuenzalida](https://rfuenzalida.com), with direction from [Jordan Egstad](https://egstad.com), for [Instrument](https://instrument.com).

Modifications: Van Lennep Amsterdam, 2026. See `FONTLOG.txt` in the delivery package for the full list of changes.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL

Copyright 2022 The Instrument Sans Project Authors (https://github.com/Instrument/instrument-sans)
