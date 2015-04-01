VOID MENU
===========

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Requirements
 - Installation
 - Permissions
 - Usage
 - Sponsors

INTRODUCTION
------------

Void Menu creates valid link item placeholders for use in the Backdrop menu system. This module allows you to use items in your links that would previously be rejected by Backdrop.

You may have seen this technique in the "single page" websites that are often step based marketing pages for an event, company services or a new product.

You can assign up to ten void items any HTML value that you desire and have it instantly available as a menu item. Including JavaScript function calls.

Void Menu allows you to set custom href attributes for your menu items, which unlocks the potential to (among other things) invoke JavaScript functions from your menus.

An example

Let's say you have created a custom JavaScript function that will set or check a cookie for a user and then send them to a specified location or apply a new condition to the page based on that operation. Prior to void menu we needed to add long winded alter functions in order to accomplish this. Now we simply assign javascript: MyCustomFunction(); to one of our void tags, and we can freely use that in any Backdrop menu.

There's more

As an added bonus, and because of the functionality of this module, you are also able to use actual anchors as menu items that serve no other purpose than placeholders. This is accomplished with a void tag that is set to javascript: void(0); or even a simple hash tag #. The benefit to using this module over special_menu_items for this is that your menus will not require any additional styling to account for the added span tags used by special_menu_items, and will be W3C valid because every anchor must have an href attribute.

Written by William Hall - www.mrtheme.com
Based off of the work done in special_menu_items and menu_firstchild

You may also email me directly at will@mrtheme.com

TESTED
-----

@todo
This module has been manually tested successfully creating several working menu items in Backdrop.

KNOWN ISSUES
---------------------
@todo

Security
--------
This module allows users to enter javascript and hook it into the Drupal menu system. Any user with "Administer Site Configuration" will have access to this module, and many others that could prove harmful if a malicious user was given free reign over your web site. Always verify which users you are granting access to Administer your site.

REQUIREMENTS
------------

@todo

This module depends on Menu module.

INSTALLATION
------------

@todo
Configure the module settings at Administer -> Configuration -> User Interface -> Void Menu (admin/config/user-interface/void_menu).


PERMISSIONS
------------

@todo


USAGE
-----
@todo


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- seeking

Current Maintainers on Drupal:

Jibus <https://www.drupal.org/u/jibus>
WillHall <https://www.drupal.org/u/willhall>

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
