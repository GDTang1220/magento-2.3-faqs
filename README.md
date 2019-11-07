# Magento 2.3 FAQ Extension Free
This is an awesome module, Admin can create unlimited, update, delete FAQs and FAQ categories free. The interface is easy to use. This extension is the best FAQ extension for your bussiness.


## Features of this extension:

### Frontend:
- Advanced Search for FAQs
- Filter the FAQs via Category
- The page detail about FAQ
- Vote on the FAQ page
- URL rewrite standard for SEO
- Display FAQs via multi stores

### Backend:
- Add unlimited FAQs and FAQ categories
- Update, delete FAQs and FAQ categories

## Introduction installation:

### 1 - Installation Magento 2 FAQ extension
#### Manual Installation
Install FAQ extension for Magento2
 * Download the extension
 * Unzip the file
 * Create a folder {Magento root}/app/code/PHPCuong/Faq
 * Copy the content from the unzip folder


##### Using Composer

```
composer require php-cuong/magento2-faqs-extensions

```

### 2 - Enable FAQ extension
 * php bin/magento module:enable PHPCuong_Faq
 * php bin/magento setup:upgrade
 * php bin/magento cache:clean
 * php bin/magento setup:static-content:deploy

### 3 - See results
Log into your Magento admin, goto FAQs -> Manage FAQs, goto FAQs -> Manage FAQs Categories
