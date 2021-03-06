# Pojo Forms #
[![Dependency Status](https://david-dm.org/pojome/pojo-forms/dev-status.svg)](https://david-dm.org/pojome/pojo-forms#info=devDependencies) [![WordPress](https://img.shields.io/wordpress/v/pojo-forms.svg?style=flat-square)](https://wordpress.org/plugins/pojo-forms/) [![WordPress](https://img.shields.io/wordpress/plugin/r/pojo-forms.svg?style=flat-square)](https://wordpress.org/plugins/pojo-forms/) [![WordPress](https://img.shields.io/wordpress/plugin/v/pojo-forms.svg?style=flat-square)](https://wordpress.org/plugins/pojo-forms/) [![WordPress](https://img.shields.io/wordpress/plugin/dt/pojo-forms.svg?style=flat-square)](https://wordpress.org/plugins/pojo-forms/) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.svg)](http://gruntjs.com/)

**Contributors:** pojo.me, KingYes, ariel.k  
**Tags:** contact, contact form, contact form builder ,contact form plugin, custom form, feedback, form, forms, form builder, forms plugin,  
**Requires at least:** 4.1  
**Tested up to:** 4.4.2  
**Stable tag:** 1.3.3  
**License:** GPLv2 or later  

Pojo Forms allows you to create any form you want with a simple drag and drop interface.

## Description ##

**Please Note:** This plugin is for [Pojo Framework][1] users only.

Pojo Forms is the ultimate form creation solution for WordPress sites that work with Pojo Framework. It allows you to easily and quickly design complex forms through a drag and drop interface and all this with no CSS knowledge or coding required.

<strong>Field Type (HTML5):</strong>

* Text
* Textarea
* Email
* URL
* Tel
* Checkbox
* Radio
* Drop-down (Select)
* Number
* Button
* Upload File

Here are just a few of the things you will find in Pojo Forms:

* Set required fields
* Set placeholder
* 3 sizes for Field or Button
* Custom style for fields and button
* Add form data to submition (time, date, page URL, user agant, IP)
* After submitting redirect to custom URL
* Add a custom CSS class for each field
* Set field width (6 columns)
* Spam Filter - Integretion with Akismet plugin.
* Submit your form by reloading the page or asynchronously with AJAX.

You can place any form in any page or widget by embedding it in the Text Editor with a unique shortcode:

<code>[pojo-form id="ID"]</code>

**Contributions:**

Would you like to like to contribute to Pojo Forms? You are more than welcome to submit your requests on the [GitHub repo][2]. Also, if you have any notes about the code, please open a ticket on this issue tracker.

 [1]: http://pojo.me/?utm_source=wp-repo&utm_medium=link&utm_campaign=forms
 [2]: https://github.com/pojome/pojo-forms

## Installation ##

**Automatic Installation**

1. Install using the WordPress built-in Plugin installer > Add New
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to the Builder tab in the Pages or Widgets menu
1. Drag and drop the widget and set it
1. Enjoy!

**Manual Installation**

1. Extract the zip file and just drop the contents in the <code>wp-content/plugins/</code> directory of your WordPress installation
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to the Builder tab in the Pages or Widgets menu
1. Drag and drop the widget and set it
1. Enjoy!

## Screenshots ##

### 1. Forms admin page ###
![Forms admin page](http://s.wordpress.org/extend/plugins/pojo-forms/screenshot-1.png)

### 2. Form builder ###
![Form builder](http://s.wordpress.org/extend/plugins/pojo-forms/screenshot-2.png)

### 3. Form style options ###
![Form style options](http://s.wordpress.org/extend/plugins/pojo-forms/screenshot-3.png)


## Changelog ##

### 1.3.3 - 17/03/2016 ###
* New! - Added reCAPTCHA Style and Size options
* Tweak! - Enqueue reCAPTCHA API just when is needed
* Fixed! - Upload file in non-required field

### 1.3.2 - 08/03/2016 ###
* New! - Added html5 validation in Telephone field

### 1.3.1 - 23/02/2016 ###
* Fixed! - Error from reCAPTCHA when is not defined

### 1.3.0 - 23/02/2016 ###
* New! - Added upload file field (Thanks to [Yehuda Hassine](https://github.com/yehudah))
* New! - Added reCAPTCHA validation (Thanks to [Yehuda Hassine](https://github.com/yehudah))

### 1.2.2 - 08/02/2016 ###
* Tested up to WordPress v4.4

### 1.2.1 - 07/02/2016 ###
* New! - Added filter `pojo_forms_email_credit` to change the credit line
* Tweak! - Print as plain text in checkbox field
* Tweak! - Added JS trigger when the form submitted

### 1.2.0 - 19/08/2015 ###
* New! - Added custom messages
* New! - Added form-id class for element form
* Tweak! - Added limit from name default

### 1.1.2 ###
* Fixed! - Removed reply-to name field was added in v1.1.0 (conflict with Hebrew language)

### 1.1.1 ###
* Tweak! - change some translate string
* Fixed! - unselectable item in dropdown

### 1.1.0 ###
* New! - Added [CF7DB](https://wordpress.org/plugins/contact-form-7-to-database-extension/) support
* New! - Added reply-to name 
* Tweak! - Drop-down new option: Set the First Option as unselected 
* Tweak! - Improved upgrade old pojo themes
* Fixed! - min/max numbers

### 1.0.1 ###
* Fixed! - problem with multiple email addresses

### 1.0.0 ###
* Initial Public Release!