=== PMC Lockdown ===
Contributors: pmcdotcom, mintindeed, IAmWilliamWallace
Tags: maintenance
Requires at least: 3.2
Tested up to: 3.2.1
Stable tag: 0.9.3

Ability to enter maintenance lockdown mode: force-logout all non-administrators, prevent logins from non-administrators, and disable commenting.

== Description ==

Sometimes you don't need (or want) to shut down the entire frontend of the site during maintenance.  Unlike the default WordPress maintenance mode, this plugin allows your site to stay running.

* Any non-Administrator will be logged out
* Comments will be closed (disabled) on all posts

This plugin does not interact with, prevent, or override WordPress's maintenance mode.  It's complementary.

== Installation ==

Nothing goes in the plugins directory.

1. Deploy `pmc_lockdown.php` to the `/wp-content/mu-plugins/` directory. Simply placing this file activates it. To deactivate it, move it from that location.

== Frequently Asked Questions ==

None yet!

== Changelog ==

= 0.9.3 =
* Initial release