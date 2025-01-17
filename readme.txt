﻿=== Plugin Name ===
NetPay Payment Gateway API Module For WooCommerce
Contributors: NetPay
Donate link: 
Tags: woocommerce netpay, netpay.co.uk, payment gateway, woocommerce, woocommerce payment gateway
Requires at least: 3.0.1
Tested up to: 4.4
Stable tag: 1.0.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This Payment Gateway For WooCommerce extends the functionality of WooCommerce to accept payments from credit/debit cards using netpay.co.uk Gateway

== Description ==

<h3>NetPay Payment Gateway for WooCommerce</h3> makes your website ready to use NetPay API Method to accept credit/debit cards on your ecommerce store in safe way. 

NetPay is most widely used payment gateway to process payments online and accepts Visa, MasterCard, Maestro, Amex, Dinners, and other variants of cards.

With API Integration Method the payer will enter the card information on Merchant’s e-commerce web site. The plugin fully support 3D Secure Card Validation and Tokenization. All these features are optional and Merchant can enable or disable on module configuration.

When 3D Secure Card Validation is enabled, the payer will be redirected to issuer bank’s validation page if the card supports 3D Secure Validation. Once the card validated by the bank, the payer will be redirected to Merchant’s e-commerce web site and payment will process. After successful payment, the payer will be redirected to Merchant’s confirmation page otherwise if any error occurred, the payer will be notified with error message on checkout page.

When Tokenization is enabled, merchant can able to store the payer’s card information against a Token on NetPay’s secure servers. The payer can able to give permission to Merchant to store card information on checkout page.

Merchant needs to obtain SSL Certification and PCI DSS Certification.

Tested with Wordpress 4.4 , WooCommerce version 2.4.12

= Features =
Few features of this plugin:

1. Easy to install and configure
2. Option to configure accepted Cards
3. Safe way to process credit cards and debit cards on WooCommerce using NetPay API and 3D Secure method
4. This plugin use API solution provided by NetPay and payment is processed on secured servers of NetPay


== Installation ==

Easy steps to install the plugin:

1. Upload `netpayapi-payment-gateway-for-woocommerce` folder/directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to WooCommerce => Settings
4. On the "Settings" page, select "Payment Gateways" tab.
5. Under "Payment Gateways" you will find all the available gateways, select "NetPay" option
6. On this page you will find option to configure the plugin for use with WooCommerce
7. Enter the API details (Merchant Id, Merchant Login, Password)

== Frequently Asked Questions ==
= What version of Wordpress and Woocommerce does this work with? =
* Version 1.0.4 has been tested with Wordpress 4.4 , WooCommerce version 2.4.12

== Screenshots ==

1. NetPay Logo
2. Checkout Sample
3. WooCommerce Settings
4. Plugin Configuration

== Changelog ==
= 1.0.6 =
* Fix 3DS goods_description field issue. It has been removed from form submission

= 1.0.5 =
* Fix 3DS error response issue

= 1.0.4 =
* Option for disable usage of SSL certificate for authentication
* Compatibility changes for wordpress 4.4 and woocommerce 2.4.12 versions
* Additional compatibility with data sent to NetPay servers

= 1.0.3 =
* Changes for 2.2.x compatability

= 1.0.2 =
* Added changes so that client certificate can be used easily
* Use billing address for shipping if shipping address is not available
* Strict string checks and 3ds url fix
* Fixed issue getting price when proceed to checkout
* Updated all redirects for full woocommerce 2.1.x compatability
* Changed variable names

= 1.0.1 =
* Updated for woocommerce 2.1 and higher

= 1.0 =
* First Version

== Upgrade Notice ==
* Please upgrade to 1.0.4 for full functionality on newest versions of wordpress and woocommerce

== Arbitrary section ==