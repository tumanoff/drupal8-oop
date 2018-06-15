# Перевод на русский язык/translating to Russian language #

# Drupal 8 Основы объектно-ориентированного программирования

Этот учебник призван помочь тем, кто новичок в объектно-ориентированном программировании (ООП) и разбирается с основами, 
необходимыми для комплексной разработки Drupal 8. 
Drupal 8 - огромный сдвиг ООП по сравнению с процедурным программированием предыдущих версий Drupal.

Большая часть, а вернее почти все в этом учебнике относится к PHP, а не к Drupal. Любой разработчик PHP может
найти полезные рекомендации, но нужно имейть в виду, что некоторые из примеров и конкретных приложений будут основаны на Drupal 8.

### Предпосылки

Многие из затронутых тем являются вводными и написаны для новичков, но желательно у вас должен быть небольшой опыт в PHP. 
Кроме того, этот учебник не предназначен для замены универсального учебного руководства по ООП.
Это предназначено для дополнения любого существующего и объясняет некоторые детали, которые вы не понимаете.

### Ограничения

Этот учебник не будет охватывать все варианты использования и минуты технических деталей. Он предназначен для общего использования.

Для пользователей Drupal - это не руководство по разработке модулей. Это поможет вам в разработке своего модуля,
но не ожидайте объяснений плагинов, сервисов и много чего.

Если вы используете среду IDE, такую как, например, PHPStorm, она поможет с предупреждениями о возникающих проблемах с некоторыми из используемых классов. Это потому, что среда видит классы во всех каталогах и может предположить, что они дублируются. 
Сами скрипты при выполнении работают правильно.

Файлы PHP, представленные в этом руководстве, исполняемые, но результаты могут отличаться. 
И, как всегда, если вы найдете любые ошибки, пожалуйста, откройте проблему или создайте запрос на исправление.

### Содержание

* 01 - Методы, свойства, оператор для указания классов и объектов (`->`) и оператор разрешения области видимости (`::`) 
* 02 - Public, protected, private, and static keywords
* 03 - `$this` and `self`
* 04 - `__construct` methods
* 05 - How classes work together, inherit methods and properties, and `parent`
* 06 - Naming conventions for classes, methods, variables, constants, etc
* 07 - Including classes from other files and using an autoloader
* 08 - Namespacing and how it relates to the autoloader
* 09 - Using namespaces, `use` statements, and more on the global space
* 10 - Declaring parameter types in method and function definitions
* 11 - Interfaces
* 12 - Abstract classes, and using them as base classes
* 13 - Using traits to reuse code
* 14 - Using factories to generate objects
* 15 - Late static binding and how it works with Drupal's dependency injection
* 16 - Tips to help you on your journey
* 17 - Common error messages
* 18 - Let's take all we've learned and build an application
