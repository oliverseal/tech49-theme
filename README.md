# Tech49 Theme

Custom UI theme for Sublime Text based on the Oblivion FUI from [GMUNK](http://work.gmunk.com/OBLIVION-GFX)

The structure for this is very closely based on the [Phoenix Theme](https://github.com/netatoo/phoenix-theme) which is based off of [Soda Dark](https://github.com/buymeasoda/soda-theme).

## Updates
v1.1 Basic support for Sublime Text 3 + extras

- Added alpha to `selection` to make selected comments easier to read.
- Added alpha to `lineHighlight` to make highlighted lines more
  readable.
- Updated Chrome-Custom.css, but still not quite ready for primetime.
  Use at your own risk (Object notation, for example, isn't readable)
- Added a `base.html` file to aid in seeing the Tech49 colors.
- Added a `Tech49.terminal` for OS X terminal that is based on the gnome terminal.

## Samples

![Markdown](http://oliverseal.github.io/tech49-theme/screenshots/markdown.png)

![CoffeeScript](http://oliverseal.github.io/tech49-theme/screenshots/coffeescript.png)

![Less CSS](http://oliverseal.github.io/tech49-theme/screenshots/less.png)

![HTML](http://oliverseal.github.io/tech49-theme/screenshots/html.png)


## Installation

Just drop it in your Packages folder. 
- Windows: `C:\Program Files\Sublime Text 3\Data\Packages\`
- Mac: `~/Library/Application Support/Sublime Text 3/Data/Packages/`
- Linux: `~/.config/sublime-text-3/Data/Packages/` -- (Might differ by distro.)

_OR_ if you use Sublime Package Manager, just Install Package "Theme - Tech 49"

### Change your Settings - User 

    {
        "theme": "Tech49.sublime-theme"
    }

### Change your Color Scheme

    {
        "color_scheme": "Packages/Theme - Tech49/Tech49.tmTheme"
    }

## Recommendation

These fonts complement Tech 49 well. NOTE: Mac renders Anonymous Pro much more smoothly
than Linux or Windows, so I've discovered (since I mostly use Crunchbang Linux) that
Ubuntu Mono is your best bet cross-platform. -- My only complaint is the "\" isn't 
slash-y enough.

On Mac:
[Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro)
On Linux or Windows:
[Ubuntu Mono](http://font.ubuntu.com/)



## Extras

### Chrome-Custom.css
_Experimental_
This styles Chrome's dev-tools to match the Tech 49 theme. Chrome updates the dev-tools
very frequently so this may potentially get out of date.
Replace the 
- `/Default/User Stylesheets/Custom.css` with this file to try it out.

#### Known Issues
- Object notation is "black-on-black" right now. Fixes will come soon.

### Terminals
_Stable_
- `gnome-terminal.xml' Works with Gnome Terminal to change the ANSI colors to match Tech 49.
- `Tech49.terminal` Works with OS X's Terminal to change the ANSI colors to match Tech 49.


### Highlight.js
_Stable_
`markdown-code.css` is built for [Markdown Here](http://markdown-here.com/), but can 
be adapted to work with [highlight.js](http://softwaremaniacs.org/soft/highlight/en/)