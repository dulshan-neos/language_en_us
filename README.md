# American English (American English) Magento2 Language Pack (en_US)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The American English (American English) translations used can be found [here](https://crowdin.com/project/magento-2/en).
This translation is usefull for people living in the United States (United States).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.2.2](https://crowdin.com/project/magento-2/en#/2.2.2) at Crowdin and based on the Magento 2.2.2 sourcefiles.
There have been  14 strings translated of the 9734 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/0)

# Maintainance mode
These [Magento2Translations](http://magento2translations.github.io/) packages are updated on a non-regular basis. We have a system in-place to do the updating automatically but running this is still a manual job and requires financial investment to automate.
This means that from time to time we will run the sync and build from Crowdin. If you would like to assist please send us a message.

Magento has started the [Magento Localization](https://github.com/magento-l10n) Community Engineering Project to facilitate translating Magento2.
In the future we might decide to merge this project with [Magento Localization](https://github.com/magento-l10n).
If they have a similar language pack to this one you can find it [here](https://github.com/magento-l10n/language-en_US).

Or have a look at all the other great community maintained packages at [e-conomix/magento-translations](https://github.com/e-conomix/magento-translations) and [Mageplaza maintained packages](https://github.com/mageplaza?q=language).

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_en_us:2.2.2-dev
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_en_us/archive/2.2.2.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_en_us`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/en_US/en_US.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*American English (United States)*'

# Contribute
To help push the '*American English (American English) Magento2 Language Pack (en_US)*' forward please goto [this](https://crowdin.com/project/magento-2/en) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).
