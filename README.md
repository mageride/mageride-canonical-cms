# Magento 2 Module by MageRide to include Canonical Meta tag in Head of CMS pages.

**To overcome the issue of Missing self-referencing tag use this module and enable the setting from Store-> Catalog-> Catalog-> Seo-> Use Canonical Link Meta Tag For CMS Pages**

The module is very simple to implement and also work with the Mageplaza Blogs extension.

To install the module run composer command : **composer require mageride/mageride-canonical-cms**

Run Commands :
<ul> 
<li>php bin/magento setup:upgrade</li>
<li>php bin/magento setup:di:compile</li>
<li>php bin/magento setup:static-content:deploy</li>
<li>php bin/magento cache:flush</li>
</ul> 

After module enable flush the cache and check pages you can easily see the canonical link.
