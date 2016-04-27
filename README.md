# galleryguide
Install profile for The Gallery Guide


[![Stories in Ready](https://badge.waffle.io/GalleryGuide/galleryguide.svg?label=ready&title=Ready)](http://waffle.io/GalleryGuide/gall)

## Installation

Depends on the [Address module](https://www.drupal.org/project/address), so need to run the following commands before installing.  

From the Drupal root directory, initialize composer_manager, and run it for the first time:

    php modules/contrib/composer_manager/scripts/init.php  
    composer drupal-update  


Install the profile:

    drush si galleryguide --account-pass=admin -y


