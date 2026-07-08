# faiztaiyeb.github.io

Official portfolio website of **Faiz Ahmad Taiyeb** — telecommunications architect, former Special Assistant to the Chief Adviser of Bangladesh, and author.

Plain HTML/CSS/JS, no build step, served directly by GitHub Pages.

## Structure

```
index.html            Single-page site (all sections)
assets/css/style.css   Design system & layout
assets/js/i18n.js      Translation dictionary (EN / NL / BN)
assets/js/main.js      Language switching, nav, scroll-reveal
assets/img/            Portrait + favicon
```

## Languages

English is the default language; Dutch and Bengali are available via the switcher in the header. Language choice is stored in `localStorage`. The Dutch and Bengali copy was translated from the English source and would benefit from a native-speaker review pass before wide distribution.

## Content sources

Biographical and career content was drawn from Mr. Taiyeb's CVs and the [Wikipedia article](https://en.wikipedia.org/wiki/Faiz_Ahmad_Taiyeb). Portrait photo © Nahid Hossain, used under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), via Wikimedia Commons.

## Local development

No build step — just serve the directory statically, e.g.:

```
python3 -m http.server 8000
```
