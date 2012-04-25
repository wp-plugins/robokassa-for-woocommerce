=== Robokassa for WooCommerce ===
Contributors: akurganow, loomst
Tags: robokassa, payment getaway, woo commerce, woocommerce, ecommerce
Requires at least: 3.0
Tested up to: 3.3.2
Stable tag: 0.2.1

Allows you to use Robokassa payment gateway with the WooCommerce plugin.

== Description ==

*После активации плагина через панель управления в WooCommerce прописывем
Логин мерчат, пароль 1, пароль 2


*В Robokassa прописываем:
Result URL: http://your_domain/?robokassa=result
Success URL: http://your_domain/?robokassa=success
Fail URL: http://your_domain/woocommerce/?robokassa=fail
Метод отсылки данных: POST


*В бесплатной версии в корзине и на странице подтверждения


== Installation ==

1. Ensure you have latest version of [WooCommerce](http://www.woothemes.com/woocommerce/) plugin installed
2. Unzip and upload contents of the plugin to your `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress


== Changelog ==
= 0.2.1 =
* Fixed problem with displaying the logo of robokassa
= 0.2 =
* Fixed problems with the update option in the database
= 0.1.2 =
* Bug fixes
= 0.1.1 =
* Added restriction to the free version, previous version are not available
= 0.1 =
* First public release
