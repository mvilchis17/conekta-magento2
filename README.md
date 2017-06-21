![alt tag](https://raw.github.com/conekta/conekta-magento/master/readme_files/cover.png)

Magento 2 Plugin v.1.1.5 (BETA)
========================

Installation
-----------

1. First add this repository in your composer config

    ```bash
    composer config repositories.conekta git https://github.com/conekta/conekta-magento2.git
    ```
2. Add the dependency

    ```bash
    composer require conekta/magento2-module dev-master
    ```
3. Update your Magento

    ```bash
    php bin/magento setup:upgrade
    ```
4. Compile your XML files

    ```bash
    php bin/magento setup:di:compile
    ```
    
Updates
-----------

For update this plugin execute the next command

```bash
php bin/magento setup:upgrade # version bump
php bin/magento setup:di:compile # version bump
composer update conekta/magento2-module
```

Magento Version Compatibility
-----------------------------
The plugin has been tested in Magento 2.0.7. Support is not guaranteed for untested versions.
