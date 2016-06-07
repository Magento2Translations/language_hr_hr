# Croatian (hrvatski) Magento2 Language Pack (hr_HR)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Croatian (hrvatski) translations used can be found [here](https://crowdin.com/project/magento-2/hr).
This translation is usefull for people living in the Croatia (Hrvatska).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.0.7](https://crowdin.com/project/magento-2/hr#/2.0.7) at Crowdin and based on the Magento 2.0.7 sourcefiles.
There have been  231 strings translated of the 7782 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/3)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_hr_hr:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_hr_hr/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_hr_hr`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/hr_HR/hr_HR.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Croatian (Croatia)*'

# Contribute
To help push the '*Croatian (hrvatski) Magento2 Language Pack (hr_HR)*' forward please goto [this](https://crowdin.com/project/magento-2/hr) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).