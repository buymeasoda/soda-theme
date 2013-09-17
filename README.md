# Sodarized

Dark and light custom UI themes for Sublime Text 2 and Sublime Text 3 (modified to match [Solarized](http://ethanschoonover.com/solarized) color scheme).

Project site: [https://github.com/jrolfs/sodarized](https://github.com/jrolfs/sodarized)

## Design

![Sodarized Light Theme](http://i.imgur.com/63YdQbp.png)

![Sodarized Dark Theme](http://i.imgur.com/fGDj7TL.png)

## Installation

Sodarized theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Sodarized via the `Package Control: Install Package` menu item. The Sodarized package is listed as `Theme - Sodarized` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/jrolfs/Sodarized.git "Theme - Sodarized"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Sodarized`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Sodarized Light.sublime-theme"` or `"theme": "Sodarized Dark.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Sodarized Light.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Sodarized Light 3.sublime-theme"` or `"theme": "Sodarized Dark 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Sodarized Light 3.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Sodarized ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "soda_classic_tabs": true

![Sodarized Tab Styles](http://i.imgur.com/k4kCl51.png)

![Sodarized Tab Styles](http://i.imgur.com/it5DyH1.png)

### Sidebar Folder Icons

Sodarized has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "soda_folder_icons": true

![Sodarized Folder Icons](http://i.imgur.com/3yg2l8I.png)

### Retina Resolution UI

Sodarized has been designed to take advantage of retina resolution (high-dpi) displays. Both Sodarized Light and Sodarized Dark support retina displays.<sup>1</sup>

![Sodarized Retina](http://buymeasoda.github.com/soda-theme/images/features/soda-retina.png)

### Theme Customisation

Sublime Text provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Soda Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## Bonus Options

### Syntax Highlighting Color Schemes

Both screenshots use a modified version of [Solarized](https://github.com/jrolfs/Solarized).

If you'd like to use the syntax highlighting schemes shown in the screenshots:

* Download [color-schemes.zip](http://d.pr/f/7o1H)
* Unzip and place the extracted `tmtheme` files in the Sublime Text `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

### Code Font

The code font shown in the screenshot is [Inconsolata](http://levien.com/type/myfonts/inconsolata.html).

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

While developing the theme, I have documented some [theme challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas) encountered along the way.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.


## Todo

<sup>1</sup> Retina Display support is untested as I don't have a Retina display to test with :'(
