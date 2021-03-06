=== Wordpress Flash Clock ===
Contributors: Gljivec, Zdrifko
Donate link: http://premiumcoding.com/wordpress-flash-clock-plugin
Tags: flash, clock, wp clock, wordpress clock, slick clock, flash clock, watch, wordpress watch, wordpress flash clock
Requires at least: 2.3
Tested up to: 3.2
Stable tag: 1.11

Wordpress Flash Clock allows you to display a clock on your page. If you wish to have a slick designed Wordpress Clock then this is the plugin for you. With or without reflection it will enhance the look of your website.

== Description ==

We present you a premium wordpress plugin which will enhance your webpage. Wordpress Flash clock allows you to display a clock on your page. With or without reflection wp clock will enhance the look of your website. A live example of the widget: http://premiumcoding.com/wordpress-flash-clock-plugin. If you want a countdown / counter of the same design please check http://premiumcoding.com/wordpress-count-down/

== Installation ==

= Installation =
1. Make sure you're running WordPress version 2.3 or better. It won't work with older versions.
1. Download the zip file.
1. Go to your WordPress admin panel and select �Plugins�. 
1. Click on button �Add new� and on next page click upload. Now browse for the zip file "wp-clockCountDown.zip" mentioned above and click Install now. 
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to Appearance/Widgets and add your plugin to your sidebar
1. See 'Settings->Count Down' to adjust things like display size, etc...

== Frequently Asked Questions ==

= How to change width of clock? =
Simply set parameter width to desired value. (It is best viewed when set to 300-400 pixels).

= How to set reflection? = 
Set parameter Reflection to true via settings in Wordpress.

= My theme/site appears not to like this plugin. It's not displaying correctly. =
There are a number of things that may prevent WP-flash-clock from displaying or cause it to display a short message about how it needs the Flash plugin.

* In 99% of all cases where this happens the issue is caused by markup errors in the page where the plugin is used. Please validate your blog using [validator.w3.org](http://validator.w3.org) and fix any errors you may encounter.
* Older versions had issues with PHP 5.2 (or better). This has been fixed, so please upgrade to the latest version.
* The plugin requires Flash Player 9 or better and javascript. Please make sure you have both.

= I'd like to change something in the Flash movie, will you release the .fla? =
Flash version of the file is currently available here: http://activeden.net/item/xml-flash-clock/58460 .If plugins gets a lot of downloads I will make it available for free on Wordpress.

= Some characters are not showing up =
Because of the way Flash handles text, only Latin characters are supported in the current version. This is due to a limitation where in order to be able to animate text fields smoothly the glyphs need to be embedded in the movie. The Flash movie's source code is available for download through Subversion. Doing so will allow you to create a version for your language. There's a text field in the root of the movie that you can use to embed more characters. If you change to another font, you'll need to edit the Tag class as well.

== Screenshots ==

1. Preview of Countdown without text
2. Preview of Countdown with text
3. Preview of Countdown without reflection and with transparent background

== Options ==

The options page allows you to change the Flash movie's dimensions as well set the background or make it transparent.

== Changelog ==

= 1.00 =
* Initial release version.

= 1.01 =
* Fixed a path problem.

= 1.1 =
* Added text under countdown, see screenshots and our live preview for more info.

= 1.11 =
* Fixed a minor bug.

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`