# Magento 2 WhatsApp Share Extension

## Introduction
Magento 2 WhatsApp Share Extension allows customers to easily share products with their contacts via WhatsApp. This helps in increasing product visibility and boosting sales through social sharing. With a single click, users can instantly share product details, images, and links on WhatsApp.

## How it Works
The Magento 2 WhatsApp Share Extension integrates a share button on product pages, enabling users to directly share product links via WhatsApp. Once installed and configured, the button will appear on the product page. When clicked, it opens WhatsApp with a pre-filled message containing the product URL and description. This helps merchants increase traffic and conversions through social referrals.

## Key Features
- **One-Click Sharing:** Allows users to share product details on WhatsApp instantly.
- **Customizable Button:** Modify the share button's style, text, and position to match your store design.
- **Mobile & Desktop Compatibility:** Works seamlessly on both mobile and desktop versions of WhatsApp.
- **Multi-Store Support:** Compatible with multiple store views and languages.

## One-Click Sharing
Customers can share products with their friends and family in just one click, making it easy to spread product recommendations.

## Customizable Button
Merchants can customize the WhatsApp share button appearance, including color, size, and text, to align with the store’s branding.

## Mobile & Desktop Compatibility
The extension is optimized to work on both WhatsApp Web and the mobile app, ensuring users can share links across all devices.

## Multi-Store Support
Supports multiple store views and allows customization per store to cater to different audiences and regions.

## Extension Installation
To install the Magento 2 WhatsApp Share Extension, follow these steps:

### Step 1: Install the extension using Composer
```sh
composer require vendor/whatsapp-share
```
For a specific version:
```sh
composer require vendor/whatsapp-share:version
```
**Note:** You may need authentication keys from the vendor or Magento Marketplace.

### Step 2: Run Magento Setup Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 WhatsApp Share Extension
Follow these steps to configure the extension in your Magento store.

### Step 1: Navigate to Configuration
Go to **Stores** > **Configuration** > **CodeDecorator** > **WhatsApp Share**.

### Step 2: Enable the Extension
Set **Enable WhatsApp Share** to **Yes**.

### Step 3: Customize Button
- Choose the button position on the product page.
- Customize the button text, color, and icon.

### Step 4: Save Configuration
Click **Save Config**, then clear the cache using:
```sh
php bin/magento cache:flush
```

## Download Our [Magento 2 WhatsApp Share](https://codedecorator.com/magento-2-whatsapp-share-extension.html) Extension
