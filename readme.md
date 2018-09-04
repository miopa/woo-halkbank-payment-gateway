=== Halk Bank Payment Gateway For Woocommerce ===

- Contributors: m1tk00
- Tags: woocommerce, payment gateway, gateway, manual payment
- Requires at least: 3.8
- Tested up to: 4.9.8
- Requires WooCommerce at least: 3.2
- Tested WooCommerce up to: 3.4
- Stable Tag: 1.1
- License: GPLv3
- Requires PHP: 5.2.4
- License URI: http://www.gnu.org/licenses/gpl-3.0.html

== Description ==

> **Requires: WooCommerce 2.1+**

This plugin allows your store to make payments via Halk Bank payment service.

== Installation ==

1. Be sure you're running WooCommerce 2.1+ in your shop.
2. You can: (1) upload the entire `halk-bank-payment-woocommerce` folder to the `/wp-content/plugins/` directory, (2) upload the .zip file with the plugin under **Plugins &gt; Add New &gt; Upload**
3. Activate the plugin through the **Plugins** menu in WordPress
4. Go to **WooCommerce &gt; Settings &gt; Checkout** and select "Halk Bank Payment" to configure.
5. Make sure you fill in all Halk Bank fields.

== Frequently Asked Questions ==

**What is the text domain for translations?**
The text domain is `halk-payment-gateway-for-woocommerce`.

== Changelog ==
1.1 Add filter support for currency switcher. Filter name halk_amount_fix
1.0.1 Fix bug with older versions
1.0 Initial version.