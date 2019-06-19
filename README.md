# Magento 2 Sales Promotion Pro (with FREE Gift)

## Overview
[Magento 2 Sales Promotion Pro](https://www.magepsycho.com/magento2-sales-promotion-pro-free-gift.html) extension extends the default rule-based promotions of Magento 2 by adding new rules like FREE gift based on several sets of new conditions(New/Specific Customers, All/Specific Subscribers, First Order, Total Number/Amount of Sales, etc.)

![Magento 2 Sales Promotion Pro Extension](https://www.magepsycho.com/media/catalog/product/cache/207e23213cf636ccdef205098cf3c8a3/m/a/magento2-sales-promotion-pro-450x450.png)

## Key Features
* Extends default cart rule promotion with new offers
* Extends default cart rules conditions with many customer & sales history related attributes
* Configure cart rule to give FREE Gift of your choice
* Offer discounts to all new customers
* Offer discounts to only selected customers
* Offer discounts to all subscribers
* Offer discounts to only selected subscribers
* Offer discounts on customer’s first order
* Offer discounts to customers having a certain amount of sales
* Offer discounts to customers having a certain number of sales
* Option to configure gift icon for cart & mini-cart display
* Option to configure valid order statuses which will be taken into account for customer sales history
    
![Magento 2 Sales Promotion Pro Backend Demo](http://g.recordit.co/1q1h41WZW8.gif)
    
## Installation
* Download the extension `.zip` file and extract the files.
* Copy the extension files from `src` folder to the `{magento2-root-dir}`
* Run the following series of command from SSH console of your server:
```
php bin/magento module:enable MagePsycho_SalesPromotionPro --clear-static-content
php bin/magento setup:upgrade`
```
* Flush the store cache
`php bin/magento cache:flush`
* Go to Admin > STORES > Configuration > MagePsycho > Sales Promotion Pro > Configure your settings here...

* Go to Admin > MARKETING > Cart Price Rules > Create your new cart rules here...

## Live Demo:
* [Frontend Demo](http://m2default.mage-expo.com/)  
* [Backend Demo](http://m2default.mage-expo.com/admin_m2demo/)

## Changelog
**Version 1.0.0 (2019-06-15)**
    
* Initial Release.    
