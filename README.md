# Magento 2 Module by MageRide to include Canonical Meta tag in Head of CMS pages.

To overcome the issue of Missing self-referencing tag use this module and enable the setting from Store-> Catalog-> Catalog-> Seo-> Use Canonical Link Meta Tag For CMS Pages

The module is very simple to implement and also work with the Mageplaza Blogs extension.

Run Commands : 
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:flush

After module enable flush the cache and check pages you can easily see the canonical link.
