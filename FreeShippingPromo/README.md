# FreeShippingPromo

Project developed based on the course <a href="https://m.academy/courses/magento-frontend-ui-components"> Frontend UI Components</a> 

The project consists of a banner that will be updated as the user adds products to the cart. As products are added to the cart, the messages in the banner will be updated and a bar will be displayed informing the progress to receive the promotion.

## Using the project

clone the project in your vendor folder

```
 app/code/vendorFolder 
 ```

After cloning the project

```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush 
```
## Preview

![alt text](./preview.gif "Preview FreeShippingPromo")
