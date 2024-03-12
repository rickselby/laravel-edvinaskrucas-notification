# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [6.6.0]
### Added
- Support for Laravel 11.x

## [6.5.0]
### Added
- Support for PHP 8.3

### Fixed
- Fix return type for `count` function

## Removed
- Support for PHP 8.0

## [6.4.0]
### Added
- Support for Laravel 10.x

## [6.3.0]
### Added
- Support for Laravel 9.x

## [6.2.0]
### Added
- Support for Laravel 8.x

## [6.1.0]
### Added
- Support for Laravel 7.x

## [6.0.1]
### Fixed
- Support for PHP 8.0

### Added
- Support for Laravel 6.x

## Previous changelog from fork

---

#5.1.1
---

* Update version matrix information

---

#5.1.0
---

* Improved configuration options
* Create new containers dynamically
* Add messages via closures
* Removed message aliasing
* Improved message positioning
* Render messages via blade extension

---

#5.0.0
---

* Fully supported Laravel 5

---

#4.0.0
---

* Support for Laravel 5

---

# 2.0.1
---

* Fix ```$this``` usage when in Closure in ServiceProvider

---

# 2.0.0
---

* Add message types dynamically
* Changes in position and alias API
* Added events
* Updated ```config.php``` file
* Messages now flashed using events
* Refactored library

---

# 1.2.3
---

* Check if ```session.store``` is set before using it.

---

# 1.2

---

* Refactored how messages are stored in bag.
* Added method ```getAtPosition($position)``` to a NotificationBag.
* Added method ```getAliased($alias)``` to a NotificationBag and Collection classes.
* Added method ```group()``` to NotificationBag to allow render grouping.
* When working directly with ```Notification```, you will work just with default container.
* Session prefix now is configurable.
* Refactored ```Notification``` class, now uses ```__call()``` to call methods on a default container.

---

# 1.1.1

---

* Added test to test message flashing after adding alias and / or position.
* Fix message flashing when using ```alias()``` and / or ```atPosition```.

---

# 1.1

---

* Added methods to clear notifications for a given type / all in a container.
* Message aliasing, allows to use alias on message, so it can be overridden when needed.
* Message positioning.

---

# 1.0.1

---

* Fixed $app scopes when registering component.

---

# 1.0

---

* Initial release.
