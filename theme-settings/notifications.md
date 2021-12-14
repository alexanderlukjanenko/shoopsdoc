---
description: In this section, you can apply settings for cookie and purchase notifications.
---

# Notifications

{% hint style="info" %}
**Theme settings -> Notifications**
{% endhint %}

## Cookie notification

&#x20;You can decide whether a cookie notification should appear on your store page by enabling or disabling this option:

![](<../.gitbook/assets/Screenshot\_28 (3).png>)

Please note, that the content of this notification you can change by following these steps:

* Go to your _Shopify Admin -> Online store -> Actions_;
* Click on Edit languages;
* In General find Notifications Cookies (or simply write “cookies” in Search);
* Start editing your content.

This is how it looks like:

![](<../.gitbook/assets/Screenshot\_30 (2).png>)

### **Button information link**

&#x20;Here you can decide what information/ page should be shown once the customer clicks on the left button in the cookie notification. Simply click on the “paste or search” field and you will get a dropdown list with the pages, which you can select as a button information link. If there is still no page you need in the list, create it in your Shopify Admin.

&#x20;For example, if the content you want to add as a button information link is a legal content, go to your _Shopify Admin -> Settings -> Legal_. Here you can manage your store´s legal pages:

![](<../.gitbook/assets/Screenshot\_31 (3).png>)

&#x20;If the content you want to add is a simple page, which is not in the dropdown list and you need to create it, you can follow the instructions described in [<mark style="color:blue;">**How to add and edit a page**</mark>](https://mpithemes.gitbook.io/shella-shopify-theme/get-started/how-to-add-and-edit-a-page)**.**

### **Delay (sec)**

&#x20;This time scale enables you to decide how many seconds after refreshing the page the cookie notification should appear. The time span is from 1 to 60 seconds.

### **Show once?**

&#x20;Here you can decide how often the cookie notification will be shown on the store page. If you enable this option, it will be shown only once, in case the customer closes the notification.

### **Cookies life**

&#x20;Here you can decide how long the system should work with the client´s cookies or how often they should be refreshed in the system. You can choose 1 day, 3 days, 1 week, 1 month, or 1 year.

## Purchase notification

&#x20;In this section, you can enable or disable a purchase notification:

![](<../.gitbook/assets/Screenshot\_32 (2).png>)

&#x20;Please note, that the content of this notification you can change by following these steps:

* Go to your _Shopify Admin -> Online store -> Actions_;
* Click on Edit languages;
* In General find Notifications purchase;
* Start editing your content.

&#x20;This is how it looks like:

![](<../.gitbook/assets/Screenshot\_33 (2).png>)

&#x20;You can also decide from which collection these notifications should be shown, simply by selecting a collection. Make sure you have created the collection in your Shopify Admin, otherwise it will not be shown in the collection list when selecting.

&#x20;Here you can configure the time scale values of the purchase notifications. Let´s take a look at each of them.

**Min time value in line #2 (minutes) - days? sec? hours?**

&#x20;Here you can set the minimum time value for the purchase notification on the time scale from 1 to 60.

**Max time value in line #2 (minutes) - days? sec? hours?**

&#x20;Here you can set the maximum time value for the purchase notification on the time scale from 1 to 60.

**Delay (sec)**

&#x20;This time scale enables you to decide how many seconds after refreshing the page the purchase notification should appear. The time span is from 1 to 60 seconds.

**Min interval (sec)**

&#x20;This time scale enables you to set the minimum interval in seconds after which the purchase notifications will be changed to the new ones. The time span is from 1 to 60 seconds.

**Max interval (sec)**

&#x20;This time scale enables you to set the maximum interval in seconds after which the purchase notifications will be changed to the new ones. The time span is from 1 to 60 seconds.

**Max time life (sec)**

&#x20;This time scale enables you to set the maximum time life (how long it will be shown) of the purchase notification in seconds. The time span is from 1 to 60 seconds.

**Example**

**Min time value in line #3:**

3

**Max time value in line #3:**

20

**Delay (sec):**

8

**Min interval (sec):**

5

**Max interval (sec):**

15

**Max time life (sec):**

10

&#x20;Now according to this example, the purchase notification will have some configurations. In the text line #3 of the purchase notification there will be shown time from 3 to 20 minutes, e.g.: 5 minutes ago from Madrid, Spain. The first purchase notification will appear 8 seconds after refreshing the page because its delay was set for 8 seconds. All next purchase notifications will appear with an interval between 5 and 15 seconds after the previous one. The duration of the purchase notification will be up to 10 seconds, which means, that this notification will be shown 10 seconds long maximum, but the system can also choose any other time value which doesn´t exceed the maximum time life set in the scale.
