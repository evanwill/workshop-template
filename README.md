# workshop-template

A Jekyll template for a simple workshop website, based on the [Minima theme](https://github.com/jekyll/minima).
Designed for gh-pages.

Works best for about 5 pages of instructions, plus index, all written in Markdown. 
The navigation to the main pages is exposed at top and bottom of each page for easy stepping through the lessons.

## Why?

Rather than making slides for a workshop, why not make a website? 
It's easier to write, access, share, and reuse. 
GitHub and gh-pages makes this super easy.

It is a better Open Educational Resource since anyone can fork and adapt!

## Details

This repo is the demo skeleton. 
Fork it and add your data to the `_config.yml` to get started.

To include pages in the nav, add the yml `nav: true`.

Put images in the `images` directory. 
For centered figures, use the `figure.html` include: `{% include figure.html file="my-cat.jpg" alt="cat" caption="My cat" width="50%" %}`.

Tweak `$border-color` in `main.scss` to give tiny splash of color on header / footer borders.

Repository does not include a Gemfile because it is a very simple project. 
Originally built using Ruby 2.3+ and Jekyll 3.4+.

## Demos

My workshop sites using this template:

- [get-git](https://uidaholib.github.io/get-git/)
- [hello-arduino](https://evanwill.github.io/hello-arduino/)
- [clean-your-data](https://evanwill.github.io/clean-your-data/)
- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)
- [Make @ the MILL](https://uidaholib.github.io/make-at-the-mill/)
