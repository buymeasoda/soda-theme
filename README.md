# Soda Theme

Dark and light custom UI themes for Sublime Text 2.

## PLEASE NOTE: In the latest update, the theme folder location has been relocated to "Packages"

The theme has now been updated to work when placed inside the **Packages** folder instead of inside **Packages/User**. If you have cloned the theme into the User folder, you will see a [broken theme (with red backgrounds)](https://github.com/buymeasoda/soda-theme/wiki/I-See-Red) on the next git pull. To correct this issue, move the "Theme - Soda" folder from inside User to inside Packages.

See [GitHub: Theme location issue](https://github.com/buymeasoda/soda-theme/issues/10) and [Sublime Forum: Theme location discussion](http://www.sublimetext.com/forum/viewtopic.php?f=2&t=2471&start=50#p11550) for more details.

## Design

![Soda Light Theme](http://buymeasoda.github.com/soda-theme/images/screenshots/soda-light-theme.png)

![Soda Dark Theme](http://buymeasoda.github.com/soda-theme/images/screenshots/soda-dark-theme.png)

## Installation

If you are a git user, the best way to install the theme and keep up to date is to clone the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

### Using Git

Go to your Sublime Text 2 `Packages` directory and clone the theme repository using the command below:

    git clone https://github.com/buymeasoda/soda-theme/ "Theme - Soda"

### Download Manually

* Download the files using the .zip download option
* Unzip the files and rename the folder to `Theme - Soda`
* Copy the folder to your Sublime Text 2 `Packages` directory
* Open your Sublime Text 2 User Global Preferences file `Sublime Text 2 -> Preferences -> User Global Settings`
* Add (or update) your theme entry to be `"theme": "Soda Light.sublime-theme"` or `"theme": "Soda Dark.sublime-theme"`

### Example User Global Settings

    {
        "theme": "Soda Light.sublime-theme"
    }

## Bonus Options

### Code Highlighting Colour Schemes

The code highlighting colour scheme shown in the Soda Light screenshot is [Espresso tutti colori.tmTheme](https://github.com/mkhl/espresso-tutti-colori.tmtheme), which was originally based on the Espresso Editor default colour scheme and ported to TextMate by [Martin Kühl](https://github.com/mkhl).

The code highlighting colour scheme shown in the Soda Dark screenshot is an ever so slightly tweaked version of Monokai that I created.

#### To use the colour scheme

* Download the `tmtheme` file from Martin's repo to the Sublime Text 2 `Packages/User` folder.
* Enable the colour scheme via `Preferences -> Color Scheme -> User`.

### Code Font

The code font shown in the screenshot is [Meslo](https://github.com/andreberg/Meslo-Font), which is a modified version of Menlo.

## Notes

There are some aspects of the Soda theme design I would like to improve such as the overall quickpanel design. It might be that I haven't figured out the correct rules yet, or that the theme system doesn't expose certain features as being editable.

One area that needs to be addressed with both themes is removing the rendering of the background colour taken from the syntax highlighting scheme in the input fields of the UI.

A summary of these areas can be found at the project wiki page [Theme Challenges and ideas](https://github.com/buymeasoda/soda-theme/wiki/Theme-challenges-and-ideas).

## Legals

The theme contains some icons from the excellent [Pictos](http://pictos.drewwilson.com/) series by Drew Wilson which I have a license for. Any use of these icons, other than for the purpose of the theme itself, would need to comply with Drew's [icon licensing agreement](http://stockart.drewwilson.com/license/).