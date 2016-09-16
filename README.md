# css-utility-classes
A small CSS library of utility classes

Table of Contents
=================

* [Spacing](#spacing)
    * [Margin](#margin)
    * [Padding](#padding)
    * [Vertical centering](#vertical-centering)
    * [Horizontal centering](#horizontal-centering)
* [Borders](#borders)
* [Typograpy](#typograpy)
    * [Text alignment](#text-alignment)
    * [Text transform](#text-transform)
    * [Font weight and italics](#font-weight-and-italics)
* [Widths](#widths)
* [CSS display](#css-display)
* [Floats](#floats)
* [Clearfix](#clearfix)
* [Fixed positioning](#fixed-positioning)
* [Invisible content](#invisible-content)
* [Other](#other)
* [Credits](#credits)

Spacing
============
Assign [`margin`](#) or [`padding`](#) to an element or a subset of its sides with shorthand classes. Includes support for individual properties, all properties, and vertical and horizontal properties. All classes are multiples on the global default value, 1rem.

The classes are named using the format: `{property}-{sides}-{size}`

Where property is one of:

* `m` - for classes that set margin
* `p` - for classes that set padding

Where sides is one of:

* `t` - for classes that set `margin-top` or `padding-top
* `b` - for classes that set `margin-bottom` or `padding-bottom`
* `l` - for classes that set `margin-left` or `padding-left`
* `r` - for classes that set `margin-right` or `padding-right`
* `x` - for classes that set both `*-left` and `*-right`
* `y` - for classes that set both `*-top` and `*-bottom`
* `a` - for classes that set a `margin` or `padding` on all 4 sides of the element

Where size is one of:

* `0` - for classes that eliminate the `margin` or `padding` by setting it to 0
* `1` - (by default) for classes that set the `margin` or `padding` to `1rem`
* `2` - (by default) for classes that set the `margin` or `padding` to `2rem`
* `3` - (by default) for classes that set the `margin` or `padding` to `3rem`

Margin
--------------------
Here are some representative examples of these classes:

```css
.m-t-0 {
  margin-top: 0 !important;
}

.m-r-1 {
  margin-right: 1rem !important;
}
```

Padding
--------------------
Here are some representative examples of these classes:

```css
.p-y-3 {
  padding-top: 3rem !important;
  padding-bottom: 3rem !important;
}

.p-a-3 {
  padding: 3rem 3rem !important;
}
```

Vertical centering
--------------------
<div class="valign-wrapper" style="display: -webkit-flex; display: -ms-flexbox; display: flex; -webkit-align-items: center; -ms-flex-align: center; align-items: center;  height: 200px; background-color: rgb(221, 221, 221);">
<h5 class="valign center" style="width: 100%; text-align: center;">Vertically aligned</h5></div>

Horizontal centering
--------------------
`.m-x-auto` class for horizontally centering fixed-width block level content by setting the horizontal margins to auto.

<div style="width: 200px; background-color: rgba(86,61,124,.15); margin-right: auto!important; margin-left: auto!important;">Centered element</div>

```
<div class="m-x-auto" style="width: 200px;">
Centered element
</div>
```

Borders
============

Typograpy
============

Text alignment
--------------------

Text transform
--------------------

Font weight and italics
--------------------

Widths
============

CSS display
============

Floats
============

Clearfix
============

Fixed positioning
============

Invisible content
============

Other
============

Credits
============
* [Materialize](https://github.com/Dogfalo/materialize) - Materialize, a CSS Framework based on Material Design
* [Bootstrap](https://github.com/twbs/bootstrap) - The most popular HTML, CSS, and JavaScript framework for developing responsive,
mobile first projects on the web.