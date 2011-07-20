# Soda Theme

A light coloured theme for Sublime Text 2.

## Installation

If you are a git user, the best way to install the theme and keep up to date is to clone the repo directly into your `/Packages/User` directory in the Sublime Text 2 application settings area.

### Using Git

Go to your Sublime Text 2 `Packages/User` directory and clone the theme repository using the command below:

    git clone https://github.com/buymeasoda/soda-theme/ "Theme - Soda"

### Download Manually

* Download the files using the .zip download option
* Unzip the files and rename the folder to `Theme - Soda`
* Copy the folder to your Sublime Text 2 `Packages/User` directory
* Open your Sublime Text 2 User Global Preferences file `Sublime Text 2 -> Preferences -> User Global Settings`
* Add (or update) your theme entry to be `"theme": "Soda Light.sublime-theme"`

### Example User Global Settings

    {
        "theme": "Soda Light.sublime-theme"
    }

### Code Highlight Colour Scheme

The code highlighting colour scheme shown in the screenshot is [Espresso tutti colori.tmTheme](https://github.com/mkhl/espresso-tutti-colori.tmtheme), which was originally based on the Espresso Editor default colour scheme and ported to TextMate by [Martin Kühl](https://github.com/mkhl). 

To use the colour scheme:

* Download (or git clone) the `tmtheme` file from Martin's repo to a folder inside the Sublime Text 2 `Packages` folder (for example: `Packages/User/Color Scheme`).
* Open your Sublime Text 2 User File Settings configuration file `Sublime Text 2 -> Preferences -> User File Settings`
* Add (or update) your colour scheme entry to reference the colour scheme file

### Example User File Settings

    {
        "color_scheme": "Packages/User/Color Scheme/Espresso tutti colori.tmTheme"
    }

## Design

![Soda Light Theme](http://buymeasoda.github.com/soda-theme/images/screenshots/soda-light-theme.png)

## Notes

There are some aspects of the theme design that aren't yet complete such as the Find / Replace button text colour. There are also other areas I would like to improve such as the overall quickpanel design.

At this stage, access to styling those features is either unvailable, limited, or I haven't figured out the correct rules.

A summary of these areas can be found at the project wiki page [Theme Challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas).

## Legals

The theme contains some icons from the excellent [Pictos](http://pictos.drewwilson.com/) series by Drew Wilson which I have a license for. Any use of these icons, other than for the purpose of the theme itself, would need to comply with Drew's [icon licensing agreement](http://stockart.drewwilson.com/license/).