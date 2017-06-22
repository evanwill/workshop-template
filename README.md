# workshop-template

A Jekyll template for a simple workshop website, based on the [Minima theme](https://github.com/jekyll/minima).
Designed for gh-pages.

Works best for about 5 pages of instructions, plus index, all written in Markdown. 
The navigation to the main pages is exposed at top and bottom of each page for easy stepping through the lessons.

To include pages in the nav, add the yml `nav: true`.

Put images in the `images` directory. 
For centered figures, use the `figure.html` include: `{% include figure.html file="my-cat.jpg" alt="cat" caption="My cat" width="50%" %}`.

Tweak `$border-color` in `main.scss` to give tiny splash of color on header / footer borders.

Repository does not include a Gemfile because it is a very simple project. 
Originally built using Ruby 2.3+ and Jekyll 3.4+.
