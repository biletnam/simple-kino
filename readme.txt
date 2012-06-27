=== Simple Kino ===
Contributors: samikeijonen
Donate link: http://foxnet.fi
Tags: movie, kino, custom post type, theatre
Requires at least: 3.3
Tested up to: 3.3.2
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple Kino register Custom Post Type movie so it's for building theatre websites.

== Description ==

*Simple Kino* register Custom Post Type *movie* so it's for building theatre websites. You need to integrate your theme 
with this plugin. You can start by adding `[movie-information]` and `[movie-showtimes]` shortcodes in your template files. Yo can add them like this.

`echo do_shortcode( '[movie-information]' );`

Or you can use my Sin City theme.

Plugin integrates with some other plugins. 

* <a href="http://wordpress.org/extend/plugins/members/" title="Members">Members</a>
* <a href="http://wordpress.org/extend/plugins/hybrid-tabs/" title="Hybrid Tabs">Hybrid Tabs</a>

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `simple-kino` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. After that there is Movie menu item in the WordPress admin

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the directory of the stable readme.txt, so in this case, `/tags/4.3/screenshot-1.png` (or jpg, jpeg, gif)
2. This is the second screen shot

== Changelog ==

= 0.1 =
* Everything is new

== Upgrade Notice ==

= 1.0 =
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.

== A brief Markdown Example ==

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`