$Id: README.txt,v 1.0.0.0 2013/06/02 15:48:24 asak Exp $

Description
===========
Ubercart Product Actions SKU provides a set of Drupal Action for usage by Ubercart
shop administrators for conducting site-wide changes to product data, using
custom codes or the excellent Views Bulk Operations (VBO) module.

It does so by provding a few new actions:

- Modify product SKU


These actions can be used to manipulate the prices of multiple products, using
three methods:

1. Node ID
2. Title
3. URL

All stock information will be not updated!
	 
Usage
=====
The module does nothing on it's own. Here's how to quickly get it up and running:
 1) Download and install the Views and VBO modules:
    http://drupal.org/project/views
	http://drupal.org/project/vbo
 2) Create a new view, using a "Page" display and "VBO" as the display style.
 3) Filter the view to display products only, and expose some filters so that
    you can filter the list of products as you wish.
 4) In the VBO settings of that view, check the boxes next to the new "Modify
    product Sell Price" and "Modify product Weight" actions.
 5) Save the view, and visit the page.
 6) Filter the list (or simply select some products) and select the desired
    action from the Bulk Operations select box, and click Execute.
 7) On this screen enter your desired change, and click "Next".
 8) Make sure you got the right products, and click "Confirm".
 
 You're done! ;)

 
If you've got any problems/questions/ideas - please visit the Issue Queue and let us know:
http://drupal.org/project/issues/search/uc_product_actions
 
Author
======
Asaph (asak) - asaph at cpo.co.il