=== Robokassa for WooCommerce ===
Contributors: akurganow, loomst
Tags: robokassa, payment getaway, woo commerce, woocommerce, ecommerce
Requires at least: 3.0
Tested up to: 3.3.2
Stable tag: trunk

Allows you to use Robokassa payment gateway with the WooCommerce plugin.

== Description ==

* После активации плагина через панель управления в WooCommerce прописывем
Логин мерчат, пароль 1, пароль 2


* В Robokassa прописываем:
** Result URL: http://your_domain/?robokassa=result
** Success URL: http://your_domain/?robokassa=success
** Fail URL: http://your_domain/woocommerce/?robokassa=fail
** Метод отсылки данных: POST

* Более подробно на <a href="//polzo.ru/wc-robokassa">странице плагина</a>

* Плагин теперь в опенсорсе, кто хочет помочь в его разработке прошу на <a href="https://github.com/Akurganow/WooCommerce-Robokassa">GitHub</a>


== Installation ==

1. Убедитесь что у вас установлена посленяя версия плагина <a href="//www.woothemes.com/woocommerce" title="WooCommerce">WooCommerce</a>
2. Распакуйте архив и загрузите "robokassa-for-woocommerce" в папку ваш-домен/wp-content/plugins
3. Активируйте плагин


== Changelog ==
= 0.7 =
* Добавлены поля description и instructions 
= 0.6 =
* Сняты ограничения бесплатной версии, плагин теперь бесплатен
= 0.5 =
* Несколько мелких нововведений
* И еще немного мелких исправлений
= 0.4.1 =
* Еще немного мелких исправлений
= 0.4 =
* Другие мелкие исправления
= 0.3 =
* Решена проблема с конфликтующими функциями
* Другие мелкие исправления
= 0.2.1 =
* Решена проблема с отображением логотипа робокассы
= 0.2 =
* Решена проблема с обновлением данных в БД
= 0.1.2 =
* Исправления ошибок
= 0.1.1 =
* Добавлены ограничения бесплатной версии
= 0.1 =
* Релиз плагина
