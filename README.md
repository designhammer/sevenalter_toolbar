# Seven Alter Toolbar - Module

**Seven Alter Toolbar** is a theme created for the Drupal [Admin Toolbar](https://www.drupal.org/project/admin_toolbar) module. It works best with the [Seven Alter admin theme](https://github.com/designhammer/sevenalter).

<img src="screenshot.png" width="335" height="250">

## Add to a Drupal site

[Drupal.org doc: Managing dependencies for a custom project](https://www.drupal.org/docs/develop/using-composer/managing-dependencies-for-a-custom-project)

Add to composer.json (the first part is already there).

    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.drupal.org/8"
        },
        {
            "type": "git",
            "url": "https://github.com/designhammer/sevenalter_toolbar.git"
        }
    ],

Require the modules.

    composer require designhammer/sevenalter_toolbar
