# Seven Alter Toolbar - Module

**Seven Alter Toolbar** is a theme created for the Drupal [Admin Toolbar](https://www.drupal.org/project/admin_toolbar) module. It works best with the [Seven Alter admin theme](https://github.com/frankyonnetti/sevenalter).

![Seven Alter Toolbar](images/sevenalter_toolbar.png)

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
