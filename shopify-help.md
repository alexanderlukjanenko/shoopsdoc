---
description: >-
  This page helps you to get an idea of how to organize your store at the
  backend and steps that should be done before to start theme customizations.
---

# Shopify help

&#x20;Before you start with the theme, please check if you are familiar with Shopify software. Pay attention how to add and edit Product, Collection, Navigation menus. You have to be familiar with product tags, product meta fields and general store settings.

### Register store <a href="#register-store" id="register-store"></a>

&#x20;The Shella theme is not an independent product. You must have a Shopify store to use it. [<mark style="color:blue;">**Create a Shopify store now**</mark>](https://www.shopify.com/?ref=mpthemes) **** if you don't have it.

&#x20;Shopify offers a 14-day trial period. In case you want more time to prepare your store, consider starting with a [<mark style="color:blue;">**development store**</mark>](https://blog.mpthemes.net/2018/10/09/trial-vs-developer-shopify-store-what-to-choose/)**.**

&#x20;Need to migrate your store to Shopify?\
&#x20;Use the litextension service.\
&#x20;[![litextension - Automated Shopping Cart Migration Service](https://mpthemes.net/shella-shopify-theme/tf-desc/update4-8/logo\_litextension\_blog.png)\
&#x20;** **<mark style="color:blue;">**Automated Shopping Cart Migration Service**</mark>](https://litextension.com)<mark style="color:blue;">****</mark>

### Store settings <a href="#store-settings" id="store-settings"></a>

1.  Multi currency at checkout page (optional)

    By default theme shows currencies configured at [<mark style="color:blue;">**Shopify Payments**</mark>](https://help.shopify.com/en/manual/payments/shopify-payments/multi-currency). If you want to show unsupported currencies by Shopify Payments - enable the info currency conversion at theme settings and configure currency format described below.

    Please note. Info multi-currency works only on store pages. Checkout page works in default store currency.
2. Currency format (optional, info multi-currency)
   1. Go to [_<mark style="color:blue;">Store Admin -> Settings -> General</mark>_](http://shopify.com/admin/settings/general)_<mark style="color:blue;"></mark>_
   2. Scroll down to **Standards and formats** and press **Change formatting** link
   3. Update fields:\
      &#x20;HTML with currency to `${{amount}} USD`\
      &#x20;HTML without currency to `${{amount}}`
3. Allow customer's accounts
   1. Go to [_<mark style="color:blue;">Store Admin -> Settings -> Checkout</mark>_](http://shopify.com/admin/settings/checkout)_<mark style="color:blue;"></mark>_
   2. Find **Customer accounts** section
   3. Set value to **Accounts are optional**
   4. Save changes

### Products <a href="#products" id="products"></a>

&#x20;Check following Shopify help pages:

1. <mark style="color:blue;"></mark>[<mark style="color:blue;">Add and update products</mark>](https://help.shopify.com/en/manual/products/add-update-products)<mark style="color:blue;"></mark>
2. [<mark style="color:blue;">Variants</mark>](https://help.shopify.com/en/manual/products/variants)<mark style="color:blue;"></mark>
3. <mark style="color:blue;"></mark>[<mark style="color:blue;">Managing inventory</mark>](https://help.shopify.com/en/manual/products/inventory)<mark style="color:blue;"></mark>
4. [<mark style="color:blue;">Metafields</mark>](https://help.shopify.com/en/manual/products/metafields)<mark style="color:blue;"></mark>
5. [<mark style="color:blue;">Tags</mark>](https://help.shopify.com/en/manual/products/details/tags)<mark style="color:blue;"></mark>

Shella theme includes <mark style="color:blue;"></mark> [<mark style="color:blue;">**Product page**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/products/product-page) <mark style="color:blue;">****</mark> and [<mark style="color:blue;">**Related products carousel**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/products/related-product-carousel) <mark style="color:blue;">****</mark> sections.

#### **Metafields**

Shella theme uses metafields for custom tabs, labels, sale countdown and size guide popup.

Check [<mark style="color:blue;">**Shella Metafields**</mark>](https://www.youtube.com/watch?v=u7xcBE9MVUY\&list=PLj-506KaR\_vcQjwcpC6yII-1JY0bSj7df\&index=35) video tutorial for more details.

#### **Tags**

&#x20;Tags are searchable keywords that you can associate with your product. Tags can help customers find your product through your online store search.

&#x20;Filters at collection page work based on tags. First, you have to add tags to your products. Second, configure filter block at theme settings.

### Collections <a href="#collections" id="collections"></a>

&#x20;Check following Shopify help page about [<mark style="color:blue;">**Collections**</mark>](https://help.shopify.com/en/manual/products/collections).

&#x20;Shella theme includes [<mark style="color:blue;">**Sidebar**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/theme-settings/collection-page-1#sidebar) **** and [<mark style="color:blue;">**Content**</mark> ](https://mpithemes.gitbook.io/shella-shopify-theme/theme-settings/collection-page)static sections, and [<mark style="color:blue;">**dynamic**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/shopify-help) sections for a page.

### Navigation, Menus

&#x20;Check following Shopify help page about [<mark style="color:blue;">**Menus and links**</mark>](https://help.shopify.com/en/manual/sell-online/online-store/menus-and-links).

&#x20;To configure Mega menu at theme you have to create nested menu at _Online store -> Navigation_ and second configure Mega menu popups at _Sections -> Header._
