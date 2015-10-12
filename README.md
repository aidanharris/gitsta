gitsta
======
Responsive, minimalistic, clean and content-oriented theme, inspired by GitHub. Mainly designed for programmers, but suitable for any bloggers.

![screenshot](screenshot.png)

### Download
- [GitHub Releases](https://github.com/nehalist/gitsta/releases)
- [WordPress.org](https://wordpress.org/themes/gitsta)

### Pre-requisites

The bower package manager is used to manage dependencies. This requires [Node.js](https://nodejs.org/en/). Once Node.js is installed bower can be installed globally using the node package manager (npm) as follows:

`npm install -g bower`

For more detailed information on the bower package manager refer to the [bower website](http://bower.io)

### Installation

Installation can be performed as follows:

```
#Clone the repo
git clone https://github.com/aidanharris/gitsta.git

#Change directory to the cloned directory
cd gitsta

#Initialise & update submodules
git submodule init
git submodule update

#Download dependencies using bower
bower install
```

After performing the above you can then transfer the folder to your server in the themes folder:

```
wordpress
└── wp-content
    └── themes
        └── COPY_THEME_HERE
```

The theme can then be enabled in the WordPress admin panel (Appearence -> Themes).

### Hacking

If you are working on the theme [browser-sync](http://browsersync.io) has been included for your convenience. To install it use npm as follows:

```
#Change directory to the git repo
cd gitsta
#Install any dependencies
npm install
```

### Features
* Responsive
* Support for font awesome, octicons, glyphicons
* Dynamic sidebar (statically positioned if the window height allows it, otherwise non-static)
* Theme options
  * Favicon
  * Comment markdown support
  * Enable/disable blog description on front page
  * Customizable error page
* Neat comments style
* Neat source code displaying within posts and pages
* Full-width template
* Advanced menues (with icons, dividers, ...)
* Well written and documented source code

### Menu
The theme menu supports:
* Icons (Octicons, Glyphicons, Font Awesome)
* Submenus
* All features of [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker): Dividers, Dropdown Headers and disabled links

To use the icons just set the "Title Attribute" of the menu item to the desired item (e.g. `fa-code`, `octicon-flame`, etc.).

### Requirements & Recommendation
* This theme requires at least PHP 5.3, due the usage of closures within the `functions.php`
* Since this theme was created with markdown in mind, you should use some kind of markdown plugin (I'm pretty satisfied with [WP-Markdown](https://wordpress.org/plugins/wp-markdown/)). If you don't like to use markdown, you can disable the markdown support within the theme settings.

### Like the theme?
Rate it on [WordPress.org](https://wordpress.org/themes/gitsta) or star it on [GitHub](https://github.com/nehalist/gitsta)! Thanks!

### Credits
* [Bootstrap](http://www.getbootstrap.com)
* [GitHub](http://www.github.com)
* [Marked](https://github.com/chjj/marked)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
* [TGM Plugin Activation](http://tgmpluginactivation.com/)
* [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker)
