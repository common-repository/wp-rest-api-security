=== WP REST API Security ===
Contributors: invisnet
Donate link: https://paypal.me/invisnet/
Author URI: https://charles.lecklider.org/
Tags: rest, api, security
Requires at least: 4.9
Tested up to: 5.1
Stable tag: 1.1.2
Requires PHP: 7.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides a UI to control which REST API endpoints are enabled and which require authentication.

== Description ==

The REST API is essential for any modern web framework, but with it comes a huge attack surface. *WP REST API Security* reduces the attack surface by disabling all the REST API endpoints by default, allowing you to enable only those actually needed. Those that are enabled require authentication by default, allowing you to choose which to make public.

> **N.B.** If you are using the new Block Editor you must keep nearly all the endpoints enabled for it to work, but none need be public.

== Installation ==

1. Install via the Plugin Directory, or upload to your plugins directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Go to *Settings* -> *WP REST API Security*

> **N.B.** Activating *WP REST API Security* will disable all REST endpoints - you **must** enable the ones you need.

== Changelog ==

= 1.1.2 =
* Fix array error.

= 1.1.1 =
* Fix CSS leakage.
* Fix array warning.

= 1.1.0 =
* Bugfix.
* Use actions.

= 1.0.0 =
* Initial release.

