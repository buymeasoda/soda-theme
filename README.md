# Phoenix Theme

Dark and light custom UI themes for Sublime Text 2.
Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

## Design

Dark `Kiwi` Theme (use modified version of Clouds Midnight) :
![Soda Dark Lemon Theme](http://img515.imageshack.us/img515/893/sodadarklemon.png?v=1)
![Soda Dark Lemon Theme](http://img23.imageshack.us/img23/695/sodadarklemon2.png?v=1)

## Todo's

- Dark Classic theme (same as Kiwi with no color)
- Dark Yellow/Pink/Blue/Red/Orange themes
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
* Add (or update) your theme entry to be `"theme": "Phoenix Dark Kiwi.sublime-theme"` or `"theme": "Phoenix Dark.sublime-theme"`

### Example User Settings

    {
        "theme": "Phoenix Dark Kiwi.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Soda Theme ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "soda_classic_tabs": true

![Soda Tab Styles](http://buymeasoda.github.com/soda-theme/images/features/multiple-tab-styles.png)

### Retina Resolution UI

Soda Theme has been designed to take advantage of retina resolution (high-dpi) displays. Both Soda Light and Soda Dark support retina displays.

![Soda Retina](http://buymeasoda.github.com/soda-theme/images/features/soda-retina.png)

### Theme Customisation

Sublime Text 2 provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

### Code Font

The code font shown in the screenshot is Menlo.

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

While developing the theme, I have documented some [theme challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas) encountered along the way.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so. 

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.