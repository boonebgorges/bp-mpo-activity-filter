=== Plugin Name ===
Contributors: boonebgorges
Tags: buddypress, activity, privacy, more privacy options, filter
Requires at least: WPMU 2.8, BuddyPress 1.1
Tested up to: WPMU 2.9.1.1, BuddyPress 1.2-rc
Donate link: http://teleogistic.net/donate/
Stable tag: trunk

When using More Privacy Options, this plugin removes items from BP activity streams according to user roles.

== Description ==

More Privacy Options is a plugin for WPMu that allows blog owners to fine-tune their blog's privacy settings, expanding on the default privacy settings offered in the WP core. Putting this plugin together with BuddyPress has been problematic, however, because BuddyPress is not built to recognize the new privacy settings defined by MPO. As a result, even private blog posts get put into the public activity feed.

This plugin, BP MPO Activity Filter, does just what the name suggests: it filters BuddyPress activity feeds (wherever bp_has_activities appears) and filters the output based on the privacy settings of the source blogs. For example, if a blog is set to be visible only to logged in members of the community, BP MPO Activity Filter will only display activity items corresponding to that blog (both posts and comments) to users who are logged in. Sitewide administrators will have an unfiltered activity stream.

It's been developed and tested on the BP 1.2 Release Candidate, but will probably work on older versions of BP as well.

I borrowed the idea, and a little bit of the code, from this plugin: http://blogs.zmml.uni-bremen.de/olio. 

== Installation ==

*Upload the directory '/bp-mpo-activity-filter/' to your WP plugins directory and activate from the Dashboard of the main blog.

== Changelog ==

= 1.0 =
* Initial release