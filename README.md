# SVBHACK

pelican-svbhack is a theme for [Pelican](http://getpelican.com) and it is my hack of a svbtle-like theme, started as a fork of [pelican-svbtle](https://github.com/wting/pelican-svbtle).

## DEMO

You can see the [theme in action](http://www.giuliofidente.im/).

## FEATURES

- syntax highlighting for code blocks
- supports google analytics
- custom list of links

## KNOWN ISSUES

- no IE testing
- no custom menu

## INSTALL

Clone the [repository](https://github.com/giulivo/pelican-svbhack), edit your `pelicanconf.py` and modify the `THEME` variable to make it point to the downloaded theme location.

## PELICANCONF.PY

Supports the most common global variables, patches are welcomed if you need better support. In addition to the standard ones, you can also set:

- `GOOGLE_ANALYTICS`
- `TAGLINE`

When developing locally, you may want to set the following variable: `SITEURL = http://localhost:8000`

## MODIFICATIONS

- Accent color can be changed by editing `@accent` in `./static/css/style.less`.
- A different Pygmentize theme can be used by editing `./Makefile` and running `make pygments`.

## AUTHOR

pelican-svbtle is authored by William Ting.

pelican-svbhack is authored by Giulio Fidente.

## LICENSE

Released under MIT License, full details in `LICENSE` file.