# Comic Mono
A legible monospace font... the very typeface you’ve been trained to recognize since childhood. This font is a fork of [Shannon Miwa](https://github.com/shannpersand)’s [Comic Shanns](https://github.com/shannpersand/comic-shanns) (version 1).

<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/">
    <img src="https://repository-images.githubusercontent.com/164606802/cd83d680-894c-11e9-83f7-c353c70df1cb" alt="Screenshot">
  </a>
</p>

## Download
- [ComicMono.ttf](https://dtinth.github.io/comic-mono-font/ComicMono.ttf)
- [ComicMono-Bold.ttf](https://dtinth.github.io/comic-mono-font/ComicMono-Bold.ttf)

## Differences from Comic Shanns
1. All glyphs have been [adjusted](https://www.reddit.com/r/programming/comments/kj0prs/comic_mono_font/ghc7krt/?utm_source=reddit&utm_medium=web2x&context=3) to have exactly the same width (using code based on [monospacifier](https://github.com/cpitclaudel/monospacifier)).
2. The glyph metrics have been adjusted to make it display better alongside system font, based on [Cousine](https://fonts.google.com/specimen/Cousine)’s metrics.
3. The name is changed to `Comic Mono`.
4. A bold version of the font is generated using [FontForge’s Embolden](https://fontforge.github.io/Styles.html#Embolden) operation.

I have no font creation skills; I’m just a software developer. This font family is created by patching the original font, [Comic Shanns (v1)](https://github.com/shannpersand/comic-shanns), using a Python script, [`generate.py`](generate.py).

### Update 2024/06/12

- Adds Italic styles
- Adds lambda 'λ' glyph
- Fixes some glyph errors

## What does it look like?
<p class="website-hidden">
  <a href="https://dtinth.github.io/comic-mono-font/#what-does-it-look-like">
    Check it out!
  </a>
</p>

```python
{% include_relative generate.py %}
```

## Check out these fonts as well
- The original [Comic Shanns](https://github.com/shannpersand/comic-shanns) by [Shannon Miwa](https://github.com/shannpersand) has V2 released with support for accented characters and other symbols, such as math symbols.
- Check out [Serious Shanns](https://github.com/kaBeech/serious-shanns) by [Kyle Beechly](https://github.com/kaBeech), which has more modifications to further enhance the legibility, lighter weight, and Nerd Font version.
- Check out [Comic Shanns Mono](https://github.com/jesusmgg/comic-shanns-mono) by [Jesus Gonzalez](https://github.com/jesusmgg), which is based on Comic Shanns v2 but with metrics adjusted and with more additional characters.

## CDN
You can use this font in your web pages by including the stylesheet. CDN is provided by [jsDelivr](https://www.jsdelivr.com/package/npm/comic-mono).
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/comic-mono@0.0.1/index.css">
```

## npm Package
The contents of this package is also [published to npm](https://www.npmjs.com/package/comic-mono), although the font files are not optimized. See fontsource package (below) for a better option.

## Packages published by third parties
- Fontsource: [@fontsource/comic-mono](https://www.npmjs.com/package/@fontsource/comic-mono) ([thanks @DecliningLotus](https://github.com/fontsource/fontsource/pull/117))
- Arch Linux AUR: [ttf-comic-mono-git](https://aur.archlinux.org/packages/ttf-comic-mono-git/) (maintained by DBourgeoisat)
- Gentoo LInux Overlay: [comic-mono-font](https://gpo.zugaina.org/Overlays/arrans-overlay/media-fonts/comic-mono-font)

## License
It is licensed under the [MIT License](LICENSE).
