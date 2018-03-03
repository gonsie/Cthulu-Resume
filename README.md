# C'thulu Resume

This one-webpage, printable resume was originally found at [css-tricks.com](https://css-tricks.com/one-page-resume-site/).
It created by [@chriscoyier](http://github.com/chriscoyier) with illustrations by [Michael Dashow](http://www.michaeldashow.com/zoom/zoom_wageslave.html).

It has been reworked and documented on GitHub by [Elsa Gonsiorowski](https://github.com/gonsie).

## Adding Content

This is a self-contained, single page resume.
Almost all the CSS needed is located in `index.html`.
The only extra piece is the GitHub Octicat icon, which is included via `octicons/`.

A category can be added with:

``` html
<dd class="clear"></dd>
<dt>Category Name</dt>
<dd>content</dd>
```

The first heading within a category should be formatted as:

``` html
<h2><strong>Title</strong>Subtitle <span>Dates</span></h2>
<ul>
  <li>Did things</li>
</ul>
```

The second heading in a category should use the class "smartmargin" to ensure that there is some space between each item.
By default, the `h2` tags do not have any margins so that there is no extra vertical space above the first item.

## Adjusting the Design

You can adjust the column sizing by messing with the `width` of the `dd` and `dt` elements.
The overall width can be adjusted via `#page-wrap`.

## Printing

Since this is a self-contained webpage, it is easy to adjust on a local machine.
Simply open the local file [index.html](index.html) using your web browser.
You can then make any edits locally and reload the file.

With the "noprint" class, items can easily be included or removed to ensure your resume is one page when printed.
In this way, you can keep everything within this file (creating a CV) and remove portions when you need to print out a resume.

## Examples

These examples demonstrate how different fonts can be used.

| Username | Webpage | Source |
|----------|---------|--------|
| [@gonsie](http://github.com/gonsie) | [Resume](http://gonsie.com/cv.html) | [On GitHub](https://github.com/gonsie/gonsie.github.io) |
| [@annagons](http://github.com/annagons) | [Resume](http://anna.gonsie.com) | [On GitHub](https://github.com/annagons/annagons.github.io) |
| [@mozhgan-kch](http://github.com/mozhgan-kch) | [Resume](http://mkchimeh.staff.shef.ac.uk) | [On GitHub](https://github.com/mozhgan-kch/mkch-webpage) |
