=== bitcoin order form for MapsMarker.com ===

Contributors: harmr, suicidalfish
Plugin Name: bitcoin order form for MapsMarker.com
Plugin URI: http://www.mapsmarker.com/bitcoin
Tags: bitcoin, currency converter, order form, eur, eur, mtgox
Donate link: http://www.mapsmarker.com/donations
Requires at least: 3.0.1
Tested up to: 3.9
Stable tag: 1.1
Author URI: http://www.harm.co.at
Author: Robert Harm
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Adds a bitcoin order form for "[Maps Marker Pro](http://www.mapsmarker.com/)" and a live currency converter for EUR to bitcoins. See a live demo at [http://www.mapsmarker.com/bitcoin](http://www.mapsmarker.com/bitcoin)

Please note that this plugin is not configurable via the WordPress admin backend! I shared this plugin for other developers in order to be able to easier build an own form by just customizing an existing plugin.

The Plugin uses live data from MT Gox to convert Bitcoin to real currency by using the API from at [http://btcrate.com/](http://btcrate.com/). Conversion from USD to EUR is done by using the API from XE.com.

Originally based on the plugin "[Bitcoin Calculator Widget](http://wordpress.org/plugins/bitcoin-currency-converter/)" by [Richard Macarthy](www.richardmacarthy.com), [http://www.richardmacarthy.com/](http://www.richardmacarthy.com/)

If you like this plugin please donate Bitcoin to: 15UUSJRBCEayMMUZJujdu1HgtUE8HNP8ph

== Installation ==

1. Upload contents of bitcoin-calculator to the `/wp-content/plugins/` directory.
2. Activate the plugin through the \\\\\\\\\\\\\\\'Plugins\\\\\\\\\\\\\\\' menu in WordPress
3. Use the shortcode entry '[bitcoin-order-form]' to display the order form on a page or a post.

Please note that the plugin is pre-configured with products available at MapsMarker.com !

Steps needed for customizing the plugin for your products:

1. /lib/exchange.php: customize configurable parameters on top of the file
2. /lib/order-form.php: adjust form fields for products (line 22+)

== Frequently Asked Questions ==

Q: I can´t change the products! 

A: this plugin has been customized for mapsmarker.com/bitcoin and been shared to make it easier for developers to build a customized order form - if you want to use your own products, please customize the code!
Steps needed for customizing the plugin for your products:
1. /lib/exchange.php: customize configurable parameters on top of the file
2. /lib/order-form.php: adjust form fields for products (line 22+)

== Screenshots ==

1. demo order form from mapsmarker.com/bitcoin

== Changelog ==
= 1.1 =
Use blockchain.info instead of Mt Gox for exchange rates

= 1.0 =
* Initial release.

== Upgrade Notice ==
= 1.1 =
Use blockchain.info instead of Mt Gox for exchange rates