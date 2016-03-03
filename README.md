# Magento 2 : Add view Product link to admin product edit page

Find the related tutorial - http://www.learnmagento.com/magento-2-add-view-product-link-to-admin-product-edit-page/

#Installation
1. To install the extension clone the repository to the <magento-root>/app/code/Muaw/ViewProduct directory
2. run commands on magento root `php bin/magento setup:upgrade` and then `php bin/magento cache:flush`
3. Now deploy static content `php bin/magento setup:static-content:deploy`
4. Edit an existing product and you should see green colour block with links under page action header
