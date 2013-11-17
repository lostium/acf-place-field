# ACF { Place Field

Adds a 'Google Maps' field type for the [Advanced Custom Fields](http://wordpress.org/extend/plugins/advanced-custom-fields/) WordPress plugin.

-----------------------

### Overview

This add-on adds a Google Map Location field type to the Advanced Custom Fields plugin for both versions 3 & 4. This field allows you to find places and coordinates of a desired location.

The Place field provides:

* a search field where you can type in some coordinates or a place and hit `Enter`. 
* a Google map which you can click at the desired location.

In both cases, Google will find the location and return the coordinates and the complete address, phone and website url from a place. A marker will be added at the desired location.


### Compatibility

This add-on will work with:

* version 4 and up


### Installation

This add-on can be treated as both a WP plugin and a theme include.

**Install as Plugin**

1. Copy the 'acf-place-field' folder into your plugins folder
2. Activate the plugin via the Plugins admin page

**Include within theme**

1.	Copy the 'acf-place-field' folder into your theme folder (can use sub folders). You can place the folder anywhere inside the 'wp-content' directory
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the acf-location.php file)

```php
include_once('acf-place-field/acf-location.php');

```

### More Information

Please read the readme.txt file for more information