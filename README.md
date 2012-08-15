# Phoenix Theme

Dark & Light custom UI themes with color for Sublime Text 2, based on Soda Theme by Ian Hill (http://buymeasoda.com/)

## Design & Colors

### Light Theme
![Phoenix Light Theme](http://ballejaune.net/phoenix-theme/Phoenix-Light.png?v=1)
Phoenix Light Theme currently provides a single color alternative :
![Phoenix Light Blue Theme](http://ballejaune.net/phoenix-theme/Phoenix-Light-Blue.png?v=1)

### Dark Theme
![Phoenix Dark Theme](http://ballejaune.net/phoenix-theme/Phoenix-Dark.png?v=1)
Phoenix Dark Theme currently provides five alternate colors :
![Phoenix Dark Red Theme](http://img204.imageshack.us/img204/5171/phoenixdarkred.png?v=1)
![Phoenix Dark Green Theme](http://img88.imageshack.us/img88/2007/phoenixdarkgreen.png?v=1)
![Phoenix Dark Blue Theme](http://img341.imageshack.us/img341/5929/phoenixdarkblue.png?v=1)
![Phoenix Dark Orange Theme](http://img692.imageshack.us/img692/2741/phoenixdarkorange.png?v=1)
![Phoenix Dark Yellow Theme](http://img40.imageshack.us/img40/8550/phoenixdarkyellow.png?v=1)

## Todo's

- Add alternates colors for Light Theme (green, red, orange)

## Installation

Phoenix theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2.

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Phoenix Theme via the `Package Control: Install Package` menu item. The Phoenix Theme package is listed as `Theme - Phoenix` in the packages list.

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
  
**Light theme :** `blue`

**Dark Theme :** `red`, `green`, `blue`, `orange` and `yellow`
  
### Example User Settings

 	"phoenix_color_blue": true

### Blur current tab color

Enable this setting to bring out the background color on the current tab, for that, we propose to define a custom settings in `Sublime Text 2 -> Preferences -> Settings - User` :

    "phoenix_blur_current_tab": true

![Phoenix Dark Blur Current Tab]( http://img854.imageshack.us/img854/7839/phoenixblurcurrenttab.png?v=1)

### Color the text label on current tab

You can colorize or not the text label (filename) of the current tab :

    "phoenix_highlight_current_tab": true    

![Phoenix Dark Highlight Current Tab](http://img341.imageshack.us/img341/6887/phoenixhighlightcurrent.png?v=1)

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

Based on Soda Theme by Ian Hill (http://buymeasoda.com/)