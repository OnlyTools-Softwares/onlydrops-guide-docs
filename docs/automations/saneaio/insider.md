---
description: A GUI tool to help you cop limited items over certain websites.
---

# Insider



![Key Prompt](../../assets/Screenshot 2023-02-14 at 4.42.38 PM.png)

Once you've typed out or entered your ONLYACO KEY, press ENTER to continue.

!!! warning
If you're sure about the key's validity, and it is still remarking it as "Invalid", reset your key using the "**$onlyaco reset"** command.


### NOTE: All features going ahead are common for both Windows and MacOS.



### PROFILE CREATION

Once started up, the first thing you'd see is the homescreen of the automation.

![Profile Set Page](../../assets/Screenshot 2023-02-14 at 4.52.27 PM.png" alt=""><figcaption></figcaption></figure>

Navigate to the **WALLET ICON** to set your profiles.

![Screenshot 2023-02-14 at 4.52.41 PM.png)

* Fill out all relevant details carefully. **I would recommend mobile numbers to be unique.**
* Please verify the relevant state code for your particular state.
* Once filled, enter the Profile Name (identifier).
* In the email field, write your google email (gmail) where you would be receiving the e-tickets and the OTP process.
* In the password field, write your gmail's APP PASSWORD for the bot to login to your gmail with IMAP to check the OTP. To setup app passwords for IMAP, follow this video.
* For enabling IMAP: [https://www.youtube.com/watch?v=hu9xp4piYPs](https://www.youtube.com/watch?v=hu9xp4piYPs)
* For making APP PASSWORDS: [https://www.youtube.com/watch?v=hXiPshHn9Pw](https://www.youtube.com/watch?v=hXiPshHn9Pw) | [https://www.youtube.com/watch?v=6ANKk9NQ3GI](https://www.youtube.com/watch?v=6ANKk9NQ3GI)
* You need to do this for each Profile's email that you wish to run on the Insider module as there are no other alternatives to logging in currently. Make sure you enable IMAP and make app passwords on each of them.



* If you wish to add another profile, make sure you click on the drop down menu below the **SAVE/DELETE** buttons and set it to load profile again.&#x20;
* To clear filled data, click on delete when the drop down menu has Load Profile selected.
* To delete or edit a profile, navigate to the **Profile** from the drop down menu, make the relevant changes and then press the **SAVE/DELETE** button accordingly.

!!! info
For any other queries, open a ticket on the OnlyDrops server.




### SETTING PROXIES (Alternative IPs to avoid blocks - not necessary)

From the previous page or any other page, clicking on the **WIFI ICON,** will take you to the proxy settings page.

![Screenshot 2023-02-14 at 4.53.53 PM.png](../../assets/Screenshot 2023-02-14 at 4.53.53 PM.png)

* Copy your proxies or download a file from your proxy dashboard.
* Your proxies are usually in the **ip:port:user:pass** format which our automation natively supports. **IP Auth'ed** proxies are also supported and are usually easier to use for most. Ask your proxy provider or experienced users about the same and how to **IP auth** your proxies. Once IP authed, only **ip:port** is needed.
* Please make sure there is only one proxy per line (all proxies are separated).
* Make sure your proxies are not blocked, to verify - use chrome extensions like [**BP PROXY SWITCHER** ](https://chrome.google.com/webstore/detail/bp-proxy-switcher/bapeomcobggcdleohggighcjbeeglhbn?hl=en)and visit the websites.
* Once entered, give your proxy list a name and press **SAVE**.
* To **enter** **another proxy list**, use the drop down menu on the right of the name and switch it to **load list** and repeat the above process.
* To **delete**, select the PROXY LIST from the drop down menu and press on delete.

![Screenshot 2023-02-14 at 5.15.19 PM.png" alt=""><figcaption></figcaption></figure>

!!! warning
**NOTE:** Please make sure you only use **STICKY** proxies and not **ROTATING** proxies as your cookies might get mixed up (usually should not but to be on the safer side).




### SETTINGS&#x20;

Clicking on the **SLIDER ICON** should navigate you to the settings page of the automation.

![Screenshot 2023-02-15 at 11.22.56 AM (1).png" alt=""><figcaption></figcaption></figure>

* Enter the webhook in the **"DISCORD WEBHOOK"** field. Once done, make sure you've checked the Order Placed checkmark for you to get the webhook. Should be checked by **default** as well.
* Remember to press **SAVE** to save the webhook in the automation. You can also **TEST WEBHOOK** to make sure you've set the right webhook.
* There is also an option to trigger the browser on a successful checkout, which opens the payment page. To enable it, make sure its checked in the settings and henceforth **SAVE**d as well.

### TASK CREATION

Once all of the above have been set and saved, head over back to the homepage menu from the **HOME/HOUSE** icon.

![Screenshot 2023-07-13 at 3.36.13 PM.png](../../assets/Screenshot 2023-02-14 at 5.15.19 PM.png" alt=""><figcaption></figcaption></figure>

!!! warning
**NOTE:** Please make sure you only use **STICKY** proxies and not **ROTATING** proxies as your cookies might get mixed up (usually should not but to be on the safer side).




### SETTINGS&#x20;

Clicking on the **SLIDER ICON** should navigate you to the settings page of the automation.

![Screenshot 2023-02-15 at 11.22.56 AM (1).png" alt=""><figcaption></figcaption></figure>

* Enter the webhook in the **"DISCORD WEBHOOK"** field. Once done, make sure you've checked the Order Placed checkmark for you to get the webhook. Should be checked by **default** as well.
* Remember to press **SAVE** to save the webhook in the automation. You can also **TEST WEBHOOK** to make sure you've set the right webhook.
* There is also an option to trigger the browser on a successful checkout, which opens the payment page. To enable it, make sure its checked in the settings and henceforth **SAVE**d as well.

### TASK CREATION

Once all of the above have been set and saved, head over back to the homepage menu from the **HOME/HOUSE** icon.

![Screenshot 2023-07-13 at 3.36.13 PM.png)

1. Choose site/module, **Insider** in this case.
2.  There is only 1 way to set/monitor an event and a ticket:

    1. **by Link and variant ID: Enter a product link (copied from the website) of the event in the Link Field**, eg. [**https://insider.in/ritviz-in-concert/event**](https://insider.in/ritviz-in-concert/event) , and **a variant ID in the size/variant/qty field** (which is the ID of the specefic ticket category/region you want to go for), eg. **64ae3eb7fdf8950008fa37d6**.

    To get the variant ID, use OnlyDrops' scraper in one of the channels or privately in a ticket and copy the variant ID complementing the Price of the ticket you're looking for, if there are multiple same prices, refer to the online listing as the ticket prices/variants are in descending order. **Example Command:** /insider url:[**https://insider.in/ritviz-in-concert/event**](https://insider.in/ritviz-in-concert/event)

![Screenshot 2023-07-13 at 4.06.17 PM.png" alt="" width="375"><figcaption></figcaption></figure>

1. The bot will check for stock and will keep looping until it finds stock.
2. Once found, it will **cart the ticket.** Most tickets on **Insider.in have a 10 minute cart hold.**
3. It will then **send an OTP for login**, **log into your email to get the OTP** and will continue the process afterwards.
4. Most tickets are e-tickets and are to be collected at the venue so the don't worry much about the address (just don't keep it empty in the profile), but make sure your mobile number is CORRECT in the profile.
5. Once completed, it **will send you a checkout link if you've set a webhook** in the Settings tab, and **open the payment link/links in browser** if you have the option checked. NOTE: I HIGHLY RECOMMEND SETTING THE WEBHOOK.

![Screenshot 2023-07-13 at 3.49.21 PM.png" alt=""><figcaption></figcaption></figure>

1. **Set Proxy** from the remaining field. Not necessary for the Insider as of now.
2. **Monitor Delay and Error Delay:** Should be explanatory, Monitor Delay is the delay it has between each check, and Error Delay is the delay the automation adds after an error. Keep 1.0 for both by default. On a slower site, increase the error delay to 3.0/5.0.
3. **Create Task Counter:** You can increase the counter to duplicate the same task multiple times if you wish to try on multiple sizes. For each profile, only KEEP/RUN A SINGLE TASK at once or else you might encounter a cart/login/otp mixup error.

**SAMPLE CHECKOUT LOGS FLOW:**

![Screenshot 2023-07-13 at 3.56.37 PM.png](../../assets/Screenshot 2023-07-13 at 4.06.17 PM.png" alt="" width="375"><figcaption></figcaption></figure>

1. The bot will check for stock and will keep looping until it finds stock.
2. Once found, it will **cart the ticket.** Most tickets on **Insider.in have a 10 minute cart hold.**
3. It will then **send an OTP for login**, **log into your email to get the OTP** and will continue the process afterwards.
4. Most tickets are e-tickets and are to be collected at the venue so the don't worry much about the address (just don't keep it empty in the profile), but make sure your mobile number is CORRECT in the profile.
5. Once completed, it **will send you a checkout link if you've set a webhook** in the Settings tab, and **open the payment link/links in browser** if you have the option checked. NOTE: I HIGHLY RECOMMEND SETTING THE WEBHOOK.

![Screenshot 2023-07-13 at 3.49.21 PM.png" alt=""><figcaption></figcaption></figure>

1. **Set Proxy** from the remaining field. Not necessary for the Insider as of now.
2. **Monitor Delay and Error Delay:** Should be explanatory, Monitor Delay is the delay it has between each check, and Error Delay is the delay the automation adds after an error. Keep 1.0 for both by default. On a slower site, increase the error delay to 3.0/5.0.
3. **Create Task Counter:** You can increase the counter to duplicate the same task multiple times if you wish to try on multiple sizes. For each profile, only KEEP/RUN A SINGLE TASK at once or else you might encounter a cart/login/otp mixup error.

**SAMPLE CHECKOUT LOGS FLOW:**

![Screenshot 2023-07-13 at 3.56.37 PM.png)

**SAMPLE WEBHOOK:**

![Screenshot 2023-07-13 at 3.54.28 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**SAMPLE PAYMENT PAGE:**

![Screenshot 2023-07-13 at 3.54.46 PM.png" alt="" width="375"><figcaption></figcaption></figure>

**NOTE:** The final webhook also has the expiry time that keeps on changing for you to keep a check on the time left for you to complete the payment, please always complete the payment within the required time!

Once all is done, add the task and then, all other buttons should be explanatory.&#x20;

Use **Start All** to start all tasks, **Stop All** to stop all tasks, **Delete All** to Delete all tasks.

To micromanage tasks, it has buttons by the side to manage it, and each should be simple to decipher by the icons.



### COMMON FAQ/ERRORS



