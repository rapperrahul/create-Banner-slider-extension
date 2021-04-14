# create-Banner-slider-extension
Banner Extension for Magneto 2 developed by Rahul Mohanty

Welcome to Banner Slider Extension for Magneto 2 developed by Rahul Mohanty.

The extension lets the store owners place smart banners on their website and also helps in creating unlimited images and video banners for your website to reach the target audience.

##Support: 
version - 2.3.x, 2.4.x

##How to install Extension

1. Download the archive file.
2. Unzip the files
3. Create a folder [Magento_Root]/app/code/Krisha/Banner
4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Krisha/Banner'

#Enable Extension:
- php bin/magento module:enable Krisha_Banner
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush

#Disable Extension:
- php bin/magento module:disable Krisha_Banner
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush
