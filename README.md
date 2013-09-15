# Master CSS framework

A non-grid CSS framework. Used for creating complex layout prototypes quickly and without coding CSS.

It is not limited to creating layouts and can be used as a supporting framework with most of other HTML/CSS libraries out there (even with [Bootstrap](http://getbootstrap.com)).

It does not feature responsive styles but is still suitable for any kind of web application - from desktop to mobile.

### Basic usage

Just include `master.css` in your HTML:

    <link type="text/css" rel="stylesheet" href="master.css" />

And start coding! All you have to do is to think in correspoding CSS properties: most of them are already included in `master.css` ranging from widths, paddings and margins to font sizes (full list is included below).

For example: to create a 960px wide centered layout, you would apply the following CSS rules:

    #main {
      width: 960px;
      margin: 0 auto;
    }

Instead of that, you can apply two classes: one for width and the other one for margins:

    <div class="w960 ma"></div>

- `w960` refers to `width:960px`
- `ma` refers to `margin: 0 auto` (sets right and left margin to auto so the layout is displayed centered)

Have a look at some [examples](https://github.com/topsitemakers/mastercss/tree/master/examples) to see how complete layouts are created. You will understand the framework in no time and it will allow you to use it without even thinking about it too much.

*Note:* if you are already using some reset stylesheet, you can use the `-lean` file as it does not include [normalize.css](http://necolas.github.io/normalize.css/).

### Range

All increments for width and height are 5 (5% and 5px).

**Width**

- Pixels - from 5px to 1280px
- Percentage - from 5% to 100%

**Height**

- Pixels - from 5px to 400px

**Padding**

- Pixels - from 5px to 100px
- Percentage - from 5% to 95%

**Margin**

- Pixels - from 5px to 100px
- Percentage - from 5% to 95%

### Credits

[normalize.css](http://necolas.github.com/normalize.css/) (v2.1.3)

<hr>

By: [topsitemakers.com](http://www.topsitemakers.com).
