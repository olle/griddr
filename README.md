# Griddr

A simple 2-4 panel dynamic grid layout demo.

https://olle.github.io/griddr/

## It rubs itself with `TABLE`, or else it gets the hose again.

When I started in web development, around 1997/1998, the only few ways to
create page layouts were either to admit defeat and just `<CENTER>`
everything, or to crack your knuckles and get going with `<TABLE>`. Using
`<TR>`s and `<TD>`s, sprinkled with `rowspan` and `colspan`. It was possible to
create amazing digital masonry, and it actually worked. We didn't know anything
else and used what we had in creative ways.

I can vividly remember that alignment was hard if not impossible and
padding/margin and borders, really made the job difficult. In order to align and
float content, you had to resort to using hacks like `trans.gif`, a 1x1
transparent GIF, together with `width` or `height` attributes in order to
stretch out cells where necessary. I remember doing a left sidebar layout,
with nested inner tables, and almost going nuts, because the designer wanted
right floats - which was probably impossible back then. I don't know how that
all ended, but I remember learning a lot.

Fast forward to today, and we have a web platform with CSS so feature-rich,
that we can create almost any layouts declaratively, without adding any
unnecessary HTML to our pages.

## Simple Panel/Page Layouts with CSS Grid 

This small showcase project provides a dynamic grid layout, applied to a simple
static web page with the semantic elements `aside` and `section`. The small
drop-down selection changes the CSS classes and the layout changes to provide:
**vertical split**, **horizontal split**, **left or right aside** as well as
**aside on both sides** with either horizontal or vertical splits. This can be
used as the base for a page-layout, either server-side rendered (the good old
way), or for an SPA with micro-frontends that mounts, and unmounts, as the grid
changes. It's just an experiment, but perhaps it can serve as inspiration for
someone to take it further.

CSS Grid, is amazing!

Happy coding!
