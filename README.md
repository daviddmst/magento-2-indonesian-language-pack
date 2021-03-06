## Magento 2 Indonesian Language Pack

**Magneto 2 Indonesian Language Pack** is one of the series of the translation tutorials Mageplaza offers free guides to thousands of store owners. In case you are planning to do a business at Indonesia, Magento 2 Indonesia Language Pack is really ideal solution. Only need to do as the following instructions, you can proceed to translate both the frontend and the backend of Magento 2 store, and then begin selling your porducts without any worry about the barrier of communication.

Read more [Magento 2 Indonesian Language Pack](https://www.mageplaza.com/magento-2-indonesian-language-pack.html)


## Overview

- Download & Contribute
- Install Indonesian Language Pack
- How to Install Indonesian Language Pack

## Download & Contribute to Indonesian Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Indonesian Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-indonesian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-indonesian-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/id.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Indonesian Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Indonesian language pack via composer is never easier.

**Install Indonesian pack**:

```
composer require mageplaza/magento-2-indonesian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy id_ID
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Indonesian pack**:

```
composer update mageplaza/magento-2-indonesian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy id_ID
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Indonesian language pack
- Step 2: Unzip Indonesian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Indonesian language pack

You can download the language pack from above link

#### Step 2: Unzip Indonesian pack

Unzip the Indonesian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Indonesian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-indonesian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-indonesian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `id_ID.zip` into `app/i18n/mageplaza/id_ID/id_ID.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Indonesian language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Indonesian Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/id

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-indonesian-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/