Vim colorscheme for Elive
=========================

Most of VIM colorschemes are designed for be beautiful or with a specific style in mind, this colorscheme instead is designed with a simple focus in mind: **USABILITY**, leaving the beautifulness in a second plane but always good for the eyes, so its goal is to be useful more than beautiful, with important things to consider like the psychology of the color used or the visual hilighting for call the attention to the user.

There's some features that includes

* friendly for the eyes
* Easy to identify what kind of element is each piece of code
* psychology of colors (green = good, red = bad, yellow or magenta = alert, etc)
* Low Contrast for less-important things like comments, visual selections, extra whitespaces in the end of the lines
* High contrast for important things like:
  * important notes like TODO/FIXME/XXX
  * folded blocks
  * hilighted search
  * marks
  * functions
* configurable background darkness level

It works in both gvim and 256-color terminals


Note: This colorscheme is made from the original BadWolf's colorscheme, is not really a hack of it but a redesign of all the resulting look, I decided to use badwolf code because was very nice coded and well structured

It's MIT/X11 licensed, so feel free to hack it apart if you like.

Screenshots
-----------

These screenshots may be out of date, but they'll at least give you a taste of
what you're in for.

### Diff

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/diff.png)

### Features Misc

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/features1.png)
![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/background-level.png)

### Bash

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/bash.png)

### C

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/c.png)

### CSS

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/css.png)

### HTML

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/html.png)

### JS

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/js.png)

### MarkDown

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/markdown.png)

### PHP

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/php.png)

### VimL

![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/viml.png)
![Screenshot](http://github.com/Elive/vim-colorscheme-elive/raw/master/screenshots/viml2.png)




Configuration
-------------

There are a few settings you can use to tweak how the colorscheme looks.

### g:badwolf\_background = 2

user-defined background tone, from 1 to 6, higher = lighter,
0 is for have a transparent background

More Configurations from the original colorscheme code
------------------------------------------------------

### g:badwolf\_darkgutter

Determines whether the line number, sign column, and fold column are rendered
darker than the normal background, or the same.

    " Make the gutters darker than the background.
    let g:badwolf_darkgutter = 1

Default: `0` (off, gutters are the same as the background)

### g:badwolf\_tabline

Determines how light to render the background of the tab line (the line at the
top of the screen containing the various tabs (only in console mode)).

Can be set to `0`, `1`, `2`, or `3`.

    " Make the tab line darker than the background.
    let g:badwolf_tabline = 0

    " Make the tab line the same color as the background.
    let g:badwolf_tabline = 1

    " Make the tab line lighter than the background.
    let g:badwolf_tabline = 2

    " Make the tab line much lighter than the background.
    let g:badwolf_tabline = 3

Default: `1` (same color as the background)

### g:badwolf\_html\_link\_underline

Determines whether text inside `a` tags in HTML files will be underlined.

    " Turn off HTML link underlining
    let g:badwolf_html_link_underline = 0

Default: `1` (on)

### g:badwolf\_css\_props\_highlight

Determines whether CSS properties should be highlighted.

    " Turn on CSS properties highlighting
    let g:badwolf_css_props_highlight = 1

Default: `0` (off)

Contributing
------------

I'd love pull requests, but won't necessarily merge all of them.  Color schemes
are a very subjective topic -- we don't all have the same taste.

**If you're going to send a pull request that you want me to merge, please post
a comment in it with before/after screenshots!**
