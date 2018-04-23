Palasis_Mobilelistmode
=====================

Allows you to specify a different default Catalog List mode for mobile users.

When?
-----
Intended use if for stores using a responsive theme that covers both Desktop and mobile views. (ie. RWD / default variants)
No need to change the package/theme or use an exception.
No need to tweak the template to override the global default setting.

How?
-----
Relies on Zend_Http_UserAgent_Mobile to identify UAs (Browser's User Agent string) of mobile users.

Rewrites
-----
Mage_Catalog_Block_Product_List_Toolbar


