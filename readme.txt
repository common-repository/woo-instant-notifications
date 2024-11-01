=== Woo Instant Notifications ===
Contributors: Irdroid, iustin16, maddob
Tags: woocommerce auto print, receipt printer woocommerce, thermal printer woocommerce, till receipts woocommerce, till receipt woocommerce, web to print, woocommerce auto print order, woocommerce order print, woo instant notifications
Requires at least: 4.9
Tested up to: 6.0.1
Stable tag: 2.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Woo Instant Notifications is a plugin that helps you automatically print order receipts on a thermal printer for your WooCommerce Shop. 

== Description ==

Print automatically receipts via a thermal printer for your WooCommerce orders.The Plugin allows you to customize the data on the printed receipts via shortcodes, automatic triggers based on order status change, built in customizable templates for order notification, invoices and packing slips. Possibility to manually re-print orders from the WordPress Dashboard. Works with any thermal printer with paper size 57mm, 80mm and 100mm.

**How it works?** 

The plugin sends automatically pre-formatted plain text emails, based on order status change (For example, when a new order is received an automatic email with the order details is sent to a pre-defined email address, configured in the plugin). The content of the builtin receipt templates can be customized with text and shortcodes in order to include the needed information that you want to appear on the printed receipt.

You have several options for automatic printing hardware setup:

1. A Printer, connected to a PC that runs Mozilla Thunderbird (with the auto printing add-ons installed) and configured with email address (of your choise) for receiving print jobs.

2. Our [Cloud based WooPrinters](https://hwgroup-bg.com/shop/), that connect directly to the Internet via WiFi or Wired (LAN) connection and monitor their Cloud mailboxes for incoming messages with order details.

3. [Cloudy](https://hwgroup-bg.com/product/cloudy) - Android based Thermal Printing System with built-in thermal receipt printer, WiFi and 3G/4G Internet Connectivity, Cloud email address for message delivery and printing (Watch Demo Video below).

4. [MadPrint](https://play.google.com/store/apps/details?id=com.maddob.madprint) for automatic printing, using an Android smartphone or tablet, connected to a Bluetooth thermal receipt printer. Please refer to MadPrint description for tested devices.

The first option (1) requires you to use a computer with the Mozilla Thunderbird email client installed and configured with a email address (preferably dedicated for printing only ) in order to print incoming messages automatically. Mozilla Thunderbird is configured to check the above mailbox on a regular basis for any new emails that contain the order details.Once a new email with the order details is received it gets automatically printed via the printer connected to the computer that runs Mozilla Thunderbird (See animation below).

[youtube https://www.youtube.com/watch?v=-e-JRVqIRY8]

The above setup is useful if you already have a printer, connected to a computer on site and you dont want to invest in additional printing hardware.

The second option (2) for printing hardware are our Cloud based network printers - The WooPrinter Series.The WooPrinter connects directly to the Internet via your WiFi / Wired router and checks its unique Cloud email address for new print jobs. Once a customer places and order via WooCommerce, the woo instant notifications plugin sends an email with the order details to the WooPrinter’s unique Cloud emails address. Then the WooPrinter prints the order details automatically (See animation below).

[youtube https://www.youtube.com/watch?v=fFeJIQqz66g]

The above setup with our [Cloud Based Printers](https://hwgroup-bg.com/shop/) is useful in case you need to setup a WooCommerce automatic printing system quickly and easily on site;You dont have the possibility to install additional computers and printers on site and you dont want to bother configuring Thunderbird.If that is the case, then our Cloud based printers are for you! 

**Just connect the WooPrinter to the Internet via WiFi or LAN connection through your router and it will be up and running!**It will start monitoring its Cloud based email address and waiting for print jobs! Last but not least, with the purchase of a WooPrinter, you also receive a license for Woo Instant Notifications PRO, which allows you to use extra features (See below).

Cloudy - Android Based Thermal Printing System Demonstration

[youtube https://www.youtube.com/watch?v=0bZuD1BtDLw]

**Printing hardware options and links**

1. [WooPrinter WiFi NG](https://hwgroup-bg.com/product/wooprinter-wifi-ng/) thermal receipt printer , developed specially for woo instant notifications. Provides WiFi and wired connection to the wifi router / internet
2. [WooPrinter WiFi](https://hwgroup-bg.com/product/wooprinter-wifi-automatic-order-printing-for-woocommerce/) thermal receipt printer , developed specially for woo instant notifications. Provides WiFi and wired connection to the wifi router / internet
3. [WooPrinter Lan](https://hwgroup-bg.com/product/wooprinter-lan/) thermal receipt printer, also a product specially developed for woo instant notifications; provides wired connection to the wifi router / internet
4. [Cloudy - Android Printing System](https://hwgroup-bg.com/product/cloudy) Android based thermal printing system. 
5. Any Printer / Thermal printer , connected to a computer that runs mozilla thunderbird with the auto printing tools installed.([Auto Printing emails with Mozilla ThunderBird - Video Tutorial](https://www.youtube.com/watch?v=8qIafd4xLgg))

The main benefit of using WooPrinter WiFi, WooPrinter Lan or Cloudy is that they **do not require a connection to a computer in order to print woocommerce order receipts** and they are **printing receipts almost instantly** after an order is placed as their polling interval (checking for new orders) is 10 - 20 seconds. The unit's directly connect to the internet via the client router and regularly check / retrieve for new orders/receipts. You can also use your own printer. In that case you will need a computer, running thunderbird with autoprint tools.

The plugin is very useful for online shops as the order notification receipts are automatically printed and the person responsible for order processing just sees the receipts and processes the order (Example - the person responsible for order processing goes to work in the morning and sees what is ordered and processes the orders without the need of even opening wordpress admin section. The receipts can also be used for marketing, coupon codes printing and sent with the ordered products etc.)


WooPrinter WiFi NG & LAN Demonstration

[youtube https://www.youtube.com/watch?v=WMVJs-Z85AM]

A setup with printer, connected to a computer that runs Thunderbird:

[youtube https://www.youtube.com/watch?v=RD-VG6Dmsl8]

== Why Thermal Printers? ==

* Low Cost consumables per print (CPP) ~ 0.0038 EUR per print
* No Ink / Toners needed (Thermal printing technology)
* Standard thermal paper rolls available anywhere
* Zero Maintenance
* Fast Printing

== Woo Instant Notifications Pro ==

The Pro version of Woo Instant Notifications has additional features and options.

***What is included in the Pro Version***

* More shortcodes for use with the Plugin Templates
 * Shortocodes for Woo Local Pickup Plus (suitable for restaraunts and coffee shops with more than one physical location. Purchase is made via the merchant online shop and the customer chooses at which location the products will be picked locally)
 * Shortcode for WooCommerce order Shipping address field #2
 * Shortcodes for Checkout Editor Pro (add custom fields on the receipt)
 * Shortcodes for WooCommerce Checkout Manager(add custom checkout fields on the receipt)
 * Shortcodes for ByC WooCommerce Order Delivery or Pickup (add delivery pickup information on the receipt)
* Shortcodes for Websolution Delivery Date & Time
* Shortcode to print PayPal transaction id if PayPal is used (as a confirmation that payment is made)
* Shortcodes for order billing address details (in case only order billing is added by the customer)
* Shortcode for Order time and date
* Send order notification to a list of different email addresses (other thank the admin email configured in WordPress)
* Other useful shortcodes
* Ability to have printers installed in different locations (for Restaurants,Bar chains).
* Possibility to print Company logo on every printed receipt
* Ability to choose wheter to send the receipt to the customer via email as well as to the shop administrator & the receipt printer
* Guide for printing automatically more than one copy of the receipt to the thermal printer (in some businesses two copies of the receipt is needed - one for the kitchen personnel and one for the delivery / preparation personnel)
* Guide for using a standard LaserJet printer for automatically printing the receipts on A5 or A6 small paper sizes.
* Video tutorials for Software Setup
* Installation Support via phone or email

[Go Pro -> Woo Instant Notifications Pro](https://ji4ka.com/woo-instant-notifications-pro/)

***You still have unanswered questions? Talk to us now!***

* BG Landline info&support - [phone:+359890325649](tel://+359890325649)

= Contributing to Woo Instant Notifications =
Submit your pull request or issue on [Github WooInstantNotifications](https://github.com/irdroid/woo-instant-notifications)

== Installation ==

= From your WordPress dashboard =

1. Visit 'Plugins > Add New'
2. Search for 'Woo Instant Notifications'
3. Activate Woo Instant Notifications from your Plugins page.
4. Go to WordPress Settings menu -> Woo Instant Notifications.
5. Read [Plugin Documentation](https://ji4ka.com/download/woo-instant-notifications-users-manual/)

= From WordPress.org =

1. Download Woo Instant Notifications.
2. Upload the 'woo-instant-notifications' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc...)
3. Activate Woo Instant Notifications from your Plugins page.
4. Go to WordPress Settings menu -> Woo Instant Notifications.

== Screenshots ==

1. Add/Edit instant notifications
2. View notifications list
3. Example Packing slip receipt
4. WooPrinter WiFi Thermal Receipt Printer
5. WooCommerce Automatic Order Printing via WooPrinter WiFi / LAN, connected directly to the Internet via WiFi or LAN / Wired connection.  
6. WooCommerce Automatic Order Printing via Printer, connected to a PC with Mozilla Thunderbird and auto printing tools.

== Changelog ==

= 1.0 =
* Initial release
* WooCommerce Instant Notifications
* WP Print Instant notifications on a thermal printer
* Based on woo custom emails plugin (GPL2.0)
