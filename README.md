# Mache theme for Grav CMS

![Mache Theme screenshot](screenshot.jpg)

Mache theme is a port of [Mache](https://freetemplates.pro/downloads/mache-html-template-for-business/) by [freetemplates.pro](https://freetemplates.pro/), original PSD design by [symu.co](https://symu.co/freebies/templates-4/mache-psd-template/).

Mache HTML template doesn't include designs for blog and contact form. To make this Grav theme more useful, the author of this Grav theme added a blog and a contact form based on the styles provided by Mache HTML template. The blog and the form are pretty basic. Please feel free to extend and submit pull requests if you want to share your works.

## Demo

A demo of this theme can be found here: [grav-theme-mache.flatfiledeveloper.com](https://grav-theme-mache.flatfiledeveloper.com).

## Features

### Grav Features:
 * Blueprint support: Edit all content in Admin plugin
 * [JSComments plugin](https://github.com/sommerregen/grav-plugin-jscomments) support
 * [SimpleSearch plugin](https://github.com/getgrav/grav-plugin-simplesearch) support
 * [Related Page plugin](https://github.com/getgrav/grav-plugin-relatedpages) support

### HTML Features:

 * HTML5 & CSS3
 * Preloaders
 * Bootstrap Grid
 * Google Fonts
 * One Page Template
 * Smooth Scrolling
 * Cross Browser Compatibility
 * Pricing Options
 * Sticky Header
 * Sticky Menu/Navigation

### jQuery Plugins:

 * jQuery Waypoints
 * BxSlider
 * Fastclick
 * Responsive-nav

## Installation

### GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install mache

This will install the Gateway theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/mache`.

### Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `mache`.

You should now have all the theme files under

    /your/site/grav/user/themes/mache

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and  [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

## Setup

If you want to set Mache as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: mache`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **mache** folder.

## Configuration with Admin plugin

If you have [Admin plugin](https://github.com/getgrav/grav-plugin-admin) installed, you can fully manage the pages via Admin plugin.

When you create/edit a page, you can find the theme's custom fields at the bottom of "Content" tab or in a complete new tab.

## Show module in top menu

To show a module in the top navigation of a modular page, you need to provide a value for "menu" variable in your page's header.

```
title: Contact
menu: Contact
```

If you use Admin plugin, you go to "Advanced", check "Menu" in "Overrides" section and provide a label for the module's menu item.

## Updating

### GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update mache

This command will check your Grav install to see if your Gateway theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

### Manual Update

Manually updating Mache is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/mache` directory.
* Download the new version of the Mache theme from this repository.
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `mache`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.
