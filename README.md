# Phoenix Theme

Dark & Light custom UI themes for Sublime Text 2, based on Soda Theme by Ian Hill (http://buymeasoda.com/)

## Design & Colors

### Light Theme
Phoenix Dark Theme ships with 3 alternate color styles.
![Phoenix Light Theme](http://img339.imageshack.us/img339/3994/phoenixlight.png?v=1)
![Phoenix Light Blue Theme](http://img62.imageshack.us/img62/7478/phoenixlightblue.png?v=1)
![Phoenix Light Red Theme](http://img854.imageshack.us/img854/7506/phoenixlightred.png?v=1)

### Dark Theme
Phoenix Dark Theme ships with 6 alternate color styles.
![Phoenix Dark Theme](http://img38.imageshack.us/img38/3320/phoenixdark.png?v=1)
![Phoenix Dark Red Theme](http://img204.imageshack.us/img204/5171/phoenixdarkred.png?v=1)
![Phoenix Dark Green Theme](http://img88.imageshack.us/img88/2007/phoenixdarkgreen.png?v=1)
![Phoenix Dark Blue Theme](http://img341.imageshack.us/img341/5929/phoenixdarkblue.png?v=1)
![Phoenix Dark Orange Theme](http://img692.imageshack.us/img692/2741/phoenixdarkorange.png?v=1)
![Phoenix Dark Yellow Theme](http://img40.imageshack.us/img40/8550/phoenixdarkyellow.png?v=1)
![Phoenix Dark Pink Theme](http://img40.imageshack.us/img40/8550/phoenixdarkyellow.png?v=1)

## Todo's

- Add alternates colors for Light Theme (green, red, orange)

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
* Add (or update) your theme entry to be `"theme": "Phoenix Light.sublime-theme"` or `"theme": "Phoenix Dark.sublime-theme"`

### Example User Settings

    {
        "theme": "Phoenix Dark.sublime-theme"
    }

## Additional Features

### Alternate Colors

Phoenix Theme ships with 5 alternate color styles. To configure you favorite color:

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) the `phoenix_color_*` entry
  
For now, five colors are available on Dark Theme : `red`, `green`, `blue`, `orange` and `yellow`
    
    "phoenix_color_blue": true

### Color the text label on current tab

You can colorize or not the text label (filename) of the current tab, for that, we propose to define a custom settings in `Sublime Text 2 -> Preferences -> Settings - User`

    "phoenix_highlight_current_tab": true    

![Phoenix Dark Highlight Current Tab](http://img341.imageshack.us/img341/6887/phoenixhighlightcurrent.png?v=1)

### Blur current tab color

Enable this setting to bring out the color on the current tab :

    "phoenix_blur_current_tab": true

### Simply choose the height of your tabs!

Prefer small tabs? No problem, there is a custom setting for this!

    "phoenix_tabs_small": true

![Phoenix Dark Tab Sizing](http://img853.imageshack.us/img853/9093/phoenixtabssizing.png?v=1)

For now, five height are available : `small`, `medium`, `normal` (by default), `large`, and `xlarge`

### Automatic width tabs

You want your tabs with automatic width? there is a custom setting for this!

    "phoenix_tabs_auto_width": true

### Custom Color Scheme

Phoenix Theme provide two slightly modified color scheme to magnify the interface.

#### Clouds Midnight
![Phoenix Dark Clouds Midnight](http://img809.imageshack.us/img809/4797/phoenixcloudsmidnightsc.png?v=1)

#### Tomorrow Night
![Phoenix Dark Tomorrow Night](http://img269.imageshack.us/img269/8480/phoenixtomorrowscheme.png?v=1)

### Retina Resolution UI

Phoenix Theme has been designed to take advantage of retina resolution (high-dpi) displays. Phoenix Theme support retina displays.

### Theme Customisation

Sublime Text 2 provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so. 

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on a fork of Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Phoenix Theme" (or a close variant) in the main project title, repo name or Package Control name.