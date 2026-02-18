---
title: Superkicks
summary: A GUI tool to help you cop limited items
description: SaneAIO is a GUI automation tool for purchasing limited items from supported websites
keywords: saneaio,automation,gui,cop,bot
author: OnlyDrops
order: 8
sidebar_title: Superkicks
---
# SK



![Key Prompt](../../assets/Screenshot 2023-02-14 at 4.42.38 PM.png)

Once you've typed out or entered your ONLYACO KEY, press ENTER to continue.

!!! warning "Note:"
    If you're sure about the key's validity, and it is still remarking it as "Invalid", reset your key using the "**$onlyaco reset"** command.

### PROFILE CREATION

Once started up, the first thing you'd see is the homescreen of the automation.

![Profile Set Page](../../assets/Screenshot 2023-02-14 at 4.52.27 PM.png)

Navigate to the **WALLET ICON** to set your profiles.

![Screenshot 2023-02-14 at 4.52.41 PM.png](../../assets/Screenshot 2023-02-14 at 4.52.41 PM.png)

* Fill out all relevant details, leave the password fields empty unless mentioned for releavant module.
* Please verify the relevant state code for your particular state.
* Once filled, enter the Profile Name (identifier), and click on save.
* If you wish to add another profile, make sure you click on the drop down menu below the **SAVE/DELETE** buttons and set it to load profile again.
* To clear filled data, click on delete when the drop down menu has Load Profile selected.
* To delete or edit a profile, navigate to the **Profile** from the drop down menu, make the relevant changes and then press the **SAVE/DELETE** button accordingly.

!!! info "Information:"
    For any other queries, open a ticket on the OnlyDrops server.


### SET PROXIES

From the previous page or any other page, clicking on the **WIFI ICON,** will take you to the proxy settings page.

![Screenshot 2023-02-14 at 4.53.53 PM.png](../../assets/Screenshot 2023-02-14 at 4.53.53 PM.png)

* Copy your proxies or download a file from your proxy dashboard.
* Your proxies are usually in the **ip:port:user:pass** format which our automation natively supports. **IP Auth'ed** proxies are also supported and are usually easier to use for most. Ask your proxy provider or experienced users about the same and how to **IP auth** your proxies. Once IP authed, only **ip:port** is needed.
* Please make sure there is only one proxy per line (all proxies are separated).
* Make sure your proxies are not blocked, to verify - use chrome extensions like [**BP PROXY SWITCHER** ](https://chrome.google.com/webstore/detail/bp-proxy-switcher/bapeomcobggcdleohggighcjbeeglhbn?hl=en)and visit the websites.
* Once entered, give your proxy list a name and press **SAVE**.
* To **enter** **another proxy list**, use the drop down menu on the right of the name and switch it to **load list** and repeat the above process.
* To **delete**, select the PROXY LIST from the drop down menu and press on delete.

![Screenshot 2023-02-14 at 5.15.19 PM.png](../../assets/Screenshot 2023-02-14 at 5.15.19 PM.png)

!!! warning "Important:"
    Please make sure you only use **STICKY** proxies and not **ROTATING** proxies as your cookies might get mixed up (usually should not but to be on the safer side).


### SETTINGS

Clicking on the **SLIDER ICON** should navigate you to the settings page of the automation.

![Screenshot 2023-02-15 at 11.22.56 AM (1).png](../../assets/Screenshot 2023-02-15 at 11.22.56 AM (1).png)

* Enter the webhook in the **"DISCORD WEBHOOK"** field. Once done, make sure you've checked the Order Placed checkmark for you to get the webhook. Should be checked by **default** as well.
* Remember to press **SAVE** to save the webhook in the automation. You can also **TEST WEBHOOK** to make sure you've set the right webhook.
* There is also an option to trigger the browser on a successful checkout, which opens the payment page. To enable it, make sure its checked in the settings and henceforth **SAVE**d as well.
* For **HYPE PRODUCTS,** SK usually puts up a captcha check on the page. To tackle that, you need to put in a [CapMonster](http://capmonster.cloud) API key in the field under API Keys, and save it. Only a 5-10$ recharge should last you months on months.
* Make sure you've saved it.

### TASK CREATION

Once all of the above have been set and saved, head over back to the homepage menu from the **HOME/HOUSE** icon.

![Create Task Dialog](../../assets/Screenshot 2023-08-03 at 2.11.53 AM.png)

1. Choose site/module, **SK (Safe)** is the recommended module for all products, and use **SK (Discount)** if time is not of extreme importance.
2. In case of **HYPE PRODUCTS,** where there exists a captcha checkbox on the product page, you need to make a **Captcha** Task from the Create Tasks Dialog. In the **Size/Variant/CaptchaQty** field, enter the max no. of captcha tokens you wish to generate using the Captch API.
3. Always **start the Captcha Task** a good 4-5 minutes before each drop, each _captcha token is valid for 2 minutes_ but don't worry, it keeps cycling out old expired tokens.&#x20;

!!! info "Note:"
    If you do not start the Captcha Task, the **SK (Safe)** **task** will use in-task generation to fetch Captcha Tokens (slower).




![Screenshot 2023-08-03 at 12.30.41 AM.png](../../assets/Screenshot 2023-08-03 at 12.30.41 AM.png)

![Screenshot 2023-08-03 at 12.30.55 AM.png](../../assets/Screenshot 2023-08-03 at 12.30.55 AM.png)

1.  **To monitor a product, by Link:** Enter a product link (copied from the website).

    eg. [https://www.superkicks.in/products/wmns-dunk-low-premi-um-white-university-red-obsidian-wolf-grey?variant=44703751536891](https://www.superkicks.in/products/wmns-dunk-low-premi-um-white-university-red-obsidian-wolf-grey?variant=44703751536891)
2. **Size selection:** After adding the link, click on the Size/Variant/CaptchaQty and then type one of the following.
   1. RA - for Random size.
   2. Incase of normal sizes, write the size as is. eg. 9
   3. If you want to go for multiple specific sizes, add them and seperate with a "," (comma). eg., 9,10,11

!!! info "Note:"
    If you leave the Size/Variant/CaptchaQty field in the SK (Safe) task empty, it defaults to using **RA (Random)** size during size selection step.


3. **Set Profile and Proxy** from the remaining 2 fields.
4. **Monitor Delay and Error Delay:** Should be explanatory, Monitor Delay is the delay it has between each check, and Error Delay is the delay the automation adds after an error. Keep 1.0 for both by default. On a slower site, increase the error delay to 3.0/5.0.
5. **Create Task Counter:** You can increase the counter to duplicate the same task multiple times.



![Created Task Idling](../../assets/Screenshot 2023-08-03 at 2.12.10 AM.png)

![Created Task Running](../../assets/Screenshot 2023-08-03 at 2.12.22 AM.png)

![Created Task Completed](../../assets/Screenshot 2023-08-03 at 2.15.42 AM.png)

![Webhook Sample at Task Successful Checkout](../../assets/Screenshot 2023-08-03 at 2.13.29 AM.png)



Once all is done, add the task and then, all other buttons should be explanatory.&#x20;

Use **Start All** to start all tasks, **Stop All** to stop all tasks, **Delete All** to Delete all tasks.

To micromanage tasks, it has buttons by the side to manage it (Start, Stop, Edit and Delete), and each should be simple to decipher by the icons.



### COMMON FAQ/ERRORS

/// details | line 701 Token Error / location (on Submitting Shipping)
This means that the product has gone out of stock or is not available on SK's stock hold/inventory API, and hence cannot proceed further than Submitting Shipping.
///

/// details | tlsClient Exception or Similar Errors
Usually this is because of a bad proxy, I recommend using good quality resis if you resort to using proxies. If you face this error often, either switch your proxies or run your tasks on LocalHost (without proxies).
///







