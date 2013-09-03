=== FeedPress ===
Contributors: maximevalette
Donate link: http://maxime.sh/paypal
Tags: feedpress, uri.lv, redirect, rss, feed, feedburner
Requires at least: 3.0
Tested up to: 3.6
Stable tag: 1.4.1

Redirects all feeds to a FeedPress feed and enables realtime feed updates.

== Description ==

FeedPress is the most reliable alternative to FeedBurner.

This WordPress plugin automatically handles feeds redirections to your FeedPress feeds the easiest way.

Additionally, every time you publish a new article, a ping is sent to FeedPress to automatically update the feed in realtime.

== Installation ==

1. Copy the feedpress folder into wp-content/plugins
2. Activate the plugin through the Plugins menu
3. Configure your feed from the new FeedPress Settings submenu

== Changelog ==

= 1.4.1 =
* Fixed a bug preventing the tag and category redirect delete.

= 1.4 =
* You can now specify a distinct redirection for each category and tag.

= 1.3 =
* New name!
* Added transparent mode: The feed is not redirected to FeedPress but requests are still reported.

= 1.2.3 =
* Resolves some caching issues as well, and debug mode.

= 1.2.2 =
* Trying to resolve some caching issues with the template_redirect action.

= 1.2.1 =
* The plugin now deletes all of its settings when the user disconnects from FeedPress.

= 1.2 =
* Now supports custom hostnames.

= 1.1.2 =
* Fixed a bug that prevented the plugin to work on some shared hosting.

= 1.1.1 =
* Cosmetic changes. You can now use a standalone account in addition to Twitter.

= 1.1 =
* You can now create the feed directly within the plugin.

= 1.0 =
* First version. Enjoy!