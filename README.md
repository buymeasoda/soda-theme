# Phoenix Theme

Dark custom UI themes for Sublime Text 2, based on Soda Theme by Ian Hill (http://buymeasoda.com/)

## Design

![Phoenix Dark Default Theme](http://img268.imageshack.us/img268/3320/phoenixdark.png?v=1)

## Todo's

- Color icons for dark themes
- Light theme

## Installation

Phoenix theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

You can locate your Sublime Text 2 `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/netatoo/phoenix-theme/ "Theme - Phoenix"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Phoenix`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activating the theme

To configure Sublime Text 2 to use the theme:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Phoenix Dark.sublime-theme"`

### Example User Settings

    {
        "theme": "Phoenix Dark.sublime-theme"
    }

## Additional Features

### Alternate Colors

Phoenix Theme ships with 5 alternate color styles.

    "phoenix_color_green": true

![Phoenix Dark Green Theme](http://img228.imageshack.us/img228/2007/phoenixdarkgreen.png?v=1)

    "phoenix_color_blue": true

![Phoenix Dark Blue Theme](http://img152.imageshack.us/img152/5929/phoenixdarkblue.png?v=1)

    "phoenix_color_orange": true

![Phoenix Dark Orange Theme](http://img803.imageshack.us/img803/2741/phoenixdarkorange.png?v=1)

    "phoenix_color_yellow": true

![Phoenix Dark Green Theme](http://img839.imageshack.us/img839/8550/phoenixdarkyellow.png?v=1)

    "phoenix_color_red": true

![Phoenix Dark Red Theme](http://img28.imageshack.us/img28/5171/phoenixdarkred.png?v=1)

### Color the text label on current tab

You can colorize or not the text label (filename) of the current tab, for that, we propose to define a custom settings in `Sublime Text 2 -> Preferences -> Settings - User`

    "phoenix_highlight_current_tab": true

![Phoenix Dark Color Tab Style True](http://img696.imageshack.us/img696/1982/phoenixhighlighttabtrue.png?v=1)

    "phoenix_highlight_current_tab": false

![Phoenix Dark Color Tab Style False](http://img811.imageshack.us/img811/8628/phoenixhighlighttabfals.png?v=1)

### Simply choose the height of your tabs!

    {
        "phoenix_tabs_small": false,
        "phoenix_tabs_medium": false,
        "phoenix_tabs_normal": true,
        "phoenix_tabs_large": false,
        "phoenix_tabs_xlarge": false,
        "phoenix_tabs_auto_width": false
    }

### Retina Resolution UI

Phoenix Theme has been designed to take advantage of retina resolution (high-dpi) displays. Phoenix Dark<div></div> support retina displays.

### Theme Customisation

Sublime Text 2 provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

While developing the theme, I have documented some [theme challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas) encountered along the way.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so. 

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on a fork of Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Phoenix Theme" (or a close variant) in the main project title, repo name or Package Control name.