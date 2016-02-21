# robokassa2

This module contains basic integration with Robokassa.
https://www.robokassa.ru

The module works with Drupal Commerce (https://drupal.org/project/commerce).

INSTALLATION:
Before you'll start the installation process you must register on Robokassa
https://www.robokassa.ru and create your own merchant.

1) Download the module from Drupal.org and extract it to your modules folder.
2) Enable it.
3) Go to /admin/commerce/config/payment-methods and edit Robokassa rule.
4) Edit Payment method
(Just click edit before 'Enable payment method: Robokassa payment').
5) Setup the settings according your data from Robokassa.

That's it :)

Additional information:
Default Success url - /commerce_robokassa/commerce_robokassa/status
Default Fail url - /commerce_robokassa/commerce_interkassa/status
Default Result url - /commerce_robokassa/commerce_robokassa/result