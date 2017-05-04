=== Easy Digital Downloads - Invoices ===
Contributors: easydigitaldownloads
Donate link: http://www.wpbeginner.com/
Tags: edd,easy digital downloads,invoices,invoicing
Requires at least: 3.9
Tested up to: 4.7
Stable tag: 1.1.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display HTML Invoices for EDD

== Description ==

Display HTML Invoices for EDD

== Installation ==

1. Upload the `edd-invoices` folder to the `/wp-content/plugins/` directory
2. Active the plugin through the 'Plugins' menu in WordPress
3. Configure the plugin by going to the EDD > Settings menu

== Frequently Asked Questions ==



== Screenshots ==



== Changelog ==

= 1.1.3, May 4, 2017 =
* Fix: Don't show Generate Invoice links for invalid payments.
* Fix: Move to using EDD_Payment for increased accuracy.
* Fix: Check if edd_get_setting exists before using it on activation.
* Fix: Prevent PHP errors when a payment does not contain billing address information.
* Fix: Fix asset URL to paid image.
* Tweak: Add classes to generate invoice submit button.


= 1.1.2, July 5, 2016 =
* Fix: Settings not retrieved on Invoice page

= 1.1.1 =
* Fix: Invoices page recreated on each admin page load if settings are not saved

= 1.1 =
* Fix: Fees not displayed on invoices

= 1.0.8 =
* Fixed: Incorrect invoice data when generating invoices for subscription payments
* Fixed: Undefined index notices


= 1.0.7 =
* Fixed: Missing text strings in language files

= 1.0.6 =
* Added: Translation support

= 1.0.5 =
* Fixed: incorrect URL to generate invoice

= 1.0.4 =
* FIX: XSS vulnerability in query args

= 1.0.3 =
* Fixed improper URL to the standard.css  file

= 1.0.2 =
* Fixed a bug that would cause css to be loaded over http on an https site

= 1.0.1 =
* Fixed a bug that would cause duplicate pages to be created

= 1.0 =
* First release.
