# Magento2.1.X_AddCompanyColumnToSalesOrderGrid
Magento2.1.X_AddCompanyColumnToSalesOrderGrid

You can see the company column on sales order grid at backend page like this 

Default loading page 
https://github.com/meezin/Magento2.1.X_AddCompanyColumnToSalesOrderGrid/blob/master/readme/3.png

After clicking the filter
https://github.com/meezin/Magento2.1.X_AddCompanyColumnToSalesOrderGrid/blob/master/readme/2.png

- BUG FIX 

If you use this module of prior version, filter would be loacted at bottom of page because it comes from how UI components are rendered. Before fixing a bug, the loading time was so slow and filter was located below. But after configuring `<listingToolbar name="listing_top"/> above your <columns>tag`, it works fine. Thank you @kanduvisla 

Reference : https://github.com/magento/magento2/issues/5408


Enjoy Have fun! 
