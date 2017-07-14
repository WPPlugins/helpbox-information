=== HelpBox Information ===
Tags: help, help box, information box, info box
Donate link: http://paypal.me/mrjoshfisher
Contributors: mrjoshfisher
Requires at least: 4.7.0
Tested up to: 4.7.2
Stable tag: 1.2
License: GNU General Public License v2.0 or later

Displays a floating helpbox on your site populated with questions from the questions page

== Description ==
Displays a floating helpbox on your site populated with questions from the questions page.

Has the ability to have a header image or video as well as other features

You must add  <?php do_action(\'helpBox_head_content_tag\'); ?> minus the \\ below your <body> tag for the helpbox to show, you will usually find the body tag in your header.php file.

Please note that the info box doesn't not display when screen size is smaller than 768px, currently developing a better mobile version.


== Installation ==
Simple upload the contents helpbox.zip to your plugin directory. 

Add  <?php do_action(\'helpBox_head_content_tag\'); ?> minus the \\ below your <body> tag for the helpbox to show, you will usually find the body tag in your header.php file.

Then configure the settings and away you go.

Please note that the info box doesn't not display when screen size is smaller than 768px, currently developing a better mobile version.

== Frequently Asked Questions ==

= My contact link isn't showing / pointing to the correct page. =

Please make sure that the Contact Us text is filled and the Contact us page is selecting your contact page.

= My help box isn't showing =

Make sure the tag <?php do_action(\'helpBox_head_content_tag\'); ?> minus the \\ is below your <body> tag for the helpbox to show, you will usually find the body tag in your header.php file.

== Upgrade Notice ==
Please update to the latest version of the plugin to get all the new features and bug fixes

== Changelog ==

= 1.2 =
* Added description on what code to add to your header.php file
* Added banners and icons for plugin
* Restricted max posts to show in helpbox to 8, will add a function to change that soon.
* Code tidy up.

= 1.1 =
* Added colour options for the helpbox.

= 1.0 =
* Initial Files.

== Screenshots ==
1. Frontend View
2. Question Button
3. Settings Screen
4. Questions Screen
5. Add New Question Screen