# Seven Alter Toolbar - Module

Seven Alter Toolbar is a theme for Drupal admin_toolbar.

![Seven Alter Toolbar](images/sevealter_toolbar.png)

## Add to a Drupal site

https://www.drupal.org/docs/develop/using-composer/managing-dependencies-for-a-custom-project

Add to composer.json (the first part is already there).

    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.drupal.org/8"
        },
        {
            "type": "git",
            "url": "https://github.com/frankyonnetti/sevenalter_toolbar.git"
        }
    ],

Require the modules.

    composer require frankyonnetti/sevenalter_toolbar
