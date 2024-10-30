=== CPT Descriptions ===
Contributors: vanpop
Donate link: http://vanpop.com/
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html
Tags: cpt, custom post types, description, custom post type description, vanpop
Requires at least: 3.1
Tested up to: 3.5
Stable tag: 0.1

== Description ==

This plugin adds a place to enter a description for your custom post types which you can display anywhere in your theme.

== Installation ==

1. Upload the ''cpt-descriptions` folder to the `/wp-content/plugins/` directory
1. Activate the CPT Descriptions plugin through the 'Plugins' menu in WordPress
1. Use the_cpt_description() or get_cpt_description() to display/use the custom post type description in your theme

== Frequently Asked Questions ==

= How do I display a/the custom post type description? =

You can use the function the_cpt_description() to echo the current custom post type description or you can use get_cpt_description() to return the description for use in code.

If you are not on an archive/single custom post type template you can pass the post type variable to either function (eg. the_cpt_description('books')) to get the description for that post type.

== Screenshots ==

1. Show added admin menu item and custom post type description entry page/field

== Changelog ==

= 0.1 =

* Initial beta release.
