---
description: >-
  In this section, you activate showing the the “Client Service” header button
  and configure its popup.
---

# Services

{% hint style="info" %}
**Theme settings -> Services**
{% endhint %}

## General

&#x20;Here you can decide, whether a “Client Service” header button should be shown:

![](<../.gitbook/assets/Screenshot\_22 (4).png>)

## Popup

&#x20;Decide whether you want a popup for client services to appear when clicking on the “Client Service” header button simply by enabling or disabling a popup. You can choose a content for the popup by selecting a page. How to add or edit a page is described below. If no page is selected, a default page: 'Include Popup Services' will be used and shown in the popup:

![](<../.gitbook/assets/Screenshot\_23 (3).png>)

&#x20; If you disable this option, the client will be redirected to a “Client Services” page, when clicking on the “Client Services” header button.

**Default page: 'Include Popup Services'**

&#x20;Now you might have a question, how one can edit this default page “Include Popup Services”. In order to do that please follow these steps:

* Go to your **** _Shopify Admin -> Online Store_;
* Click on Pages;
* Search for “Include Popup Services” and click on it;
* Start editing the page;
* Save changes

&#x20;That is all. Once you follow these steps you will get to the page editor, where you can change the content of this page. In such a way each page can be added and edited. You can read more in our section [<mark style="color:blue;">**How to add and edit a page**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/get-started/how-to-add-and-edit-a-page). **** This is how the editor of the page looks like:

![](<../.gitbook/assets/Screenshot\_24 (4).png>)

&#x20;**Demo content, HTML code**

* Create page at _Online store -> Pages_
* Switch editor to the code mode. Press Show HTML button.
* Paste demo code and save the page.

```
<div class="popup-services__head d-flex align-items-center mb-10">
<h5 class="m-0">HERE TO HELP</h5>
</div>
<div class="popup-services__content">
<p>Have a question? You may find an answer in our <a href="/pages/answers-to-your-questions" class="btn-link">FAQs</a>.<br />But you can also contact us:</p>
<h6 class="mb-20">Customer Services</h6>
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-197]</i>Call Us: 800-123-4567</p>
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-234]</i>Mon-Fri: 9:00 am - 6:00 pm<br />Sat: 9:00 am - 4:00 pm<br />Sun: 9:00 am - 2:00 pm</p>
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-153]</i><a href="mailto:shellashopify2018@gmail.com" class="btn-link">Send us an email</a></p>
</div>
<hr />
<div class="popup-services__head d-flex align-items-center mb-15">
<h5 class="m-0">SHIPPING</h5>
</div>
<div class="popup-services__content">
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-116]</i>Free shippingdelivery all orders of $49 or more of eligible items across any product category qualify.</p>
</div>
<hr />
<div class="popup-services__head d-flex align-items-center mb-15">
<h5 class="m-0">PAYMENTS</h5>
</div>
<div class="popup-services__content">
<h6 class="mb-20">Accepts the following payment methods:</h6>
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-125]</i>Credit Card: Visa, MasterCard, Maestro, American Express. The total will be charged to your card when the order is shipped.</p>
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-157]</i>PayPal: Shop easily online without having to enter your credit card details on the website.</p>
</div>
<hr />
<div class="popup-services__head d-flex align-items-center mb-15">
<h5 class="m-0">RETURN POLICY</h5>
</div>
<div class="popup-services__content">
<p class="d-flex align-items-start"><i class="mr-10 colorize-theme-primary-f-ins">[icon:theme-009]</i>You can return any item purchased on Shella within 20 days of the delivery date.</p>
</div>
```
