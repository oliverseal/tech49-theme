# Tech49 Theme

Custom UI theme for Sublime Text based on the Oblivion FUI from 
[GMUNK](http://work.gmunk.com/OBLIVION-GFX)

The structure for this is very closely based on the 
[Phoenix Theme](https://github.com/netatoo/phoenix-theme) which is based off of 
[Soda Dark](https://github.com/buymeasoda/soda-theme).

## Updates
v1.2.0 Added support for Markdown Extended
- [Markdown Extended](https://sublime.wbond.net/packages/Markdown%20Extended) is 
  a great plugin that helps in the readability and composition of Markdown in 
  Sublime Text.
- *Known Issue*: Markdown Extended doesn't highlight image punctuation correctly
  in its current version. I've submitted a pull request, so this might change soon.

v1.1.1 Chrome stylesheet updates

- Increased the readability of the toolbar (matched Sublime Text tab style).
- Object notation and comments should all be clearly readable in console messages 
  and source code.

v1.1.0 Basic support for Sublime Text 3 + extras

- Added alpha to `selection` to make selected comments easier to read.
- Added alpha to `lineHighlight` to make highlighted lines more
  readable.
- Added support for diff syntax and JSON strings in theme colors.
- Updated Chrome-Custom.css, but still not quite ready for primetime.
  Use at your own risk (Object notation, for example, isn't readable)
- Added a `base.html` file to aid in seeing the Tech49 colors.
- Added a `Tech49.terminal` for OS X terminal that is based on the gnome terminal ANSI.

## Samples

![Markdown Extended](http://oliverseal.github.io/tech49-theme/screenshots/markdown.png)

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
_Alpha_
This styles source code in Chrome's dev-tools to match the Tech 49 theme. Chrome updates the dev-tools
very frequently so this may potentially get out of date.
Replace the 
- Linux users can try this with `ln -sf /path/to/tech49-theme/Chrome-Custom.css /home/$USER/.config/google-chrome/Default/User\ StyleSheets/Custom.css`
- OR `ln -sf /path/to/tech49-theme/Chrome-Custom.css /home/$USER/.config/chromium/Default/User\ StyleSheets/Custom.css`



#### Known Issues
- Not compatible with CodeMirror editor in Chrome yet. If you have
  this option turned on, only the Elements tab and the Console tab
  will have the Tech 49 styles.
- Issues on readability are welcome on this stylesheet.

### Terminals
_Stable_
- `gnome-terminal.xml' Works with Gnome Terminal to change the ANSI colors to match Tech 49.
- `Tech49.terminal` Works with OS X's Terminal to change the ANSI colors to match Tech 49.


### Highlight.js
_Stable_
`markdown-code.css` is built for [Markdown Here](http://markdown-here.com/), but can 
be adapted to work with [highlight.js](http://softwaremaniacs.org/soft/highlight/en/)