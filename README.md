# Magento 2 Dutch Translations

- Complete translations for Magento 2.x CE and EE.
- Added Dutch [address formatting](src/etc/config.xml)

## Installation through composer
```bash
composer require webeau/magento2-nl-nl
```

## How are translations files loaded
In the file `Magento\Framework\App\Language\Dictionary::readPackCsv` all `*.csv` files are loaded, no specific filename
required.

## Credits
This repo is forked from https://github.com/ho-nl/magento2-nl_NL.

This extension was developed by H&O with a lot of help from the Magento Community on CrowdIn. www.h-o.nl
