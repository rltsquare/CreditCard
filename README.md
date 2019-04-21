# RLTSquarePaymentMethod-Magento2

# Overview

RLTSquare Payment Method is an extension for Magneto 2 which comprises of modular services. This extension helps in connecting different business payment methods to a global payment processing method and helps the customers to reduce the cost and complexity they had to face while carrying out different e-commerce operations. RLTSquare payment method will make the process of e-commerce transactions easy and swift. There are a number of ways in which this extension is going to make an impact like improving the revenue growth, improve the overall checkout experience, keep customer’s payment credentials safe and secure, options to use multiple payment methods and experience more mobile-friendly shopping.

Here are some of the salient features for the extension:

```
1. Seamless integration of your online store with Payment Processing. 
2. Secure acceptance of payments through web and mobile
3. Support for one-click checkout
4. Payer authentication
5. Mobile-optimized
6. For global deployment, it supports international currency
7. Payment Tokenization to ensure protected payments 
These tokens are generated using algorithms and cannot be reversed.
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/creditcard
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/CreditCard
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_CreditCard
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.2.5 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/creditcard-magento-2-extension/
