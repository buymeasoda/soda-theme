# Soda Theme

Dark and light custom UI themes for Sublime Text 2.

## Design

![Soda Light Theme](http://buymeasoda.github.com/soda-theme/images/screenshots/soda-light-theme.png?v=7)

![Soda Dark Theme](http://buymeasoda.github.com/soda-theme/images/screenshots/soda-dark-theme.png?v=7)

## Installation

If you are a git user, the best way to install the theme and keep up to date is to clone the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

### Using Git

Go to your Sublime Text 2 `Packages` directory and clone the theme repository using the command below:

    git clone https://github.com/buymeasoda/soda-theme/ "Theme - Soda"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Soda`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Activating the theme

To configure Sublime Text 2 to use the theme:

* For Sublime Text 2 (Build 2174) and later - Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`. For earlier builds - Open your User Global Settings Preferences file `Sublime Text 2 -> Preferences -> Global Settings - User`
* Add (or update) your theme entry to be `"theme": "Soda Light.sublime-theme"` or `"theme": "Soda Dark.sublime-theme"`

### Example User Settings

    {
        "theme": "Soda Light.sublime-theme"
    }

## Bonus Options

### Syntax Highlighting Colour Schemes

The Soda Light screenshot uses a modified version of Espresso Tutti Colori and the Soda Dark screenshot uses a modified version of Monokai.

If you'd like to use the syntax highlighting schemes shown in the screenshots: 

* Download [colour-schemes.zip](http://buymeasoda.github.com/soda-theme/extras/colour-schemes.zip)
* Unzip and place the extracted `tmtheme` files in the Sublime Text 2 `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

### Code Font

The code font shown in the screenshot is [Meslo](https://github.com/andreberg/Meslo-Font), which is a modified version of Menlo.

## Release Notes

Soda theme is designed to work with the latest [development build](http://www.sublimetext.com/dev) of Sublime Text 2. ST2 dev builds move quickly and changes can occur with the theme API between releases, so there may be occassions where the theme doesn't quite work with a brand new dev release.

## Development

While developing the theme, I have documented some [theme challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas) encountered along the way.

## Legals

The theme contains some icons from the excellent [Pictos](http://pictos.drewwilson.com/) series by Drew Wilson which I have a license for. Any use of these icons, other than for the purpose of the theme itself, would need to comply with Drew's [icon licensing agreement](http://stockart.drewwilson.com/license/).