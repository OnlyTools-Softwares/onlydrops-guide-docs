---
description: A GUI tool to help you cop limited items over certain websites.
---

# Myntra



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

* Fill out all relevant details, in the password field enter the complete cookie value.
* For Myntra, the address field does not matter as it chooses your default address saved/selected on Myntra.
* Once filled, enter the Profile Name (identifier), and click on save.
* If you wish to add another profile, make sure you click on the drop down menu below the **SAVE/DELETE** buttons and set it to load profile again.&#x20;
* To clear filled data, click on delete when the drop down menu has Load Profile selected.
* To delete or edit a profile, navigate to the **Profile** from the drop down menu, make the relevant changes and then press the **SAVE/DELETE** button accordingly.

!!! info
For any other queries, open a ticket on the OnlyDrops server.




### GET COOKIE VALUE

1. Login to your account and then open the homepage or account profile page.
2. Open the web inspector (inspect element/devtools). Use the shortcut for your respective browser ([google search](https://www.google.com/search?q=command+for+opening+inspect+element)), or right click and inspect element if applicable.
3. Once in the web requests inspector, filter requests by XHR/Fetch by clicking on it, press **Ctrl + R (Windows) or Command + R (MacOS),** enter user-data in the search field. Will work with most other API requests (search [https://www.myntra.com/gateway](https://www.myntra.com/gateway/) or v1/v2/v3 or api) too.
4. Right click on the request and select Copy as CURL (in copy sub menu in Google Chrome) or search [Google](https://www.google.com/search?q=how+to+copy+as+curl).
5. Once you've successfully copied as CURL, go to [CURL Converter ](http://curlconverter.com)([http://curlconverter.com](http://curlconverter.com)) and paste it in the box. Python conversion should be selected by default.
6. Copy whatever the value is corresponding to the **cookies** variable.
7. Once copied, paste it into the **Password** field on the respective **Profile** in the Profile section of the bot.
8. If you've followed all the steps as described, there should not be any problem.&#x20;
9. Video Walkthrough: [https://i.imgur.com/vP897AD.mp4](https://i.imgur.com/vP897AD.mp4)



Incase of issues, open a support ticket or ask in support channels for help.

### SETTING PROXIES (Alternative IPs to avoid blocks - not recommended for Myntra)

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

<div>![Screenshot 2023-04-11 at 3.27.09 AM.png" alt=""><figcaption></figcaption></figure> ![Screenshot 2023-04-11 at 3.27.03 AM.png](../../assets/Screenshot 2023-02-14 at 5.15.19 PM.png" alt=""><figcaption></figcaption></figure>

!!! warning
**NOTE:** Please make sure you only use **STICKY** proxies and not **ROTATING** proxies as your cookies might get mixed up (usually should not but to be on the safer side).




### SETTINGS&#x20;

Clicking on the **SLIDER ICON** should navigate you to the settings page of the automation.

<div>![Screenshot 2023-04-11 at 3.27.09 AM.png" alt=""><figcaption></figcaption></figure> ![Screenshot 2023-04-11 at 3.27.03 AM.png)</div>

* Enter the webhook in the **"DISCORD WEBHOOK"** field. Once done, make sure you've checked the Order Placed checkmark for you to get the webhook. Should be checked by **default** as well.
* Remember to press **SAVE** to save the webhook in the automation. You can also **TEST WEBHOOK** to make sure you've set the right webhook.
* If you want the **BOT** to solve the captcha as is, enter your **CAPTCHA KEY from Capmonster (**[**capmonster.cloud**](http://capmonster.cloud)**).** Remember to **SAVE** it. If you don't enter a key, it will open an image and ask you to manually input the captcha from the image (if you're pre-running a task, it is qually fast and more accurate).
* There is also an option to trigger the browser on a successful checkout, which opens the payment page. To enable it, make sure it's checked in the settings and henceforth **SAVE**d as well.

### TASK CREATION

Once all of the above have been set and saved, head over back to the homepage menu from the **HOME/HOUSE** icon.



![Screenshot 2023-07-27 at 11.26.47 PM.png](../../assets/Screenshot 2023-07-27 at 11.26.47 PM.png)

1. Choose site/module, **Myntra**.
2.  There is only 1 way to set/monitor a product:

    * **by Myntra SKU/PID:** Enter the **Product ID of the product**. You can find the PID within the product URL, either the numbers at the end of a Myntra Wishlist Url, or the numbers before /buy on the URL. Also visible on the product page (Ctrl + F and type Product Code). Add this in the LINK FIELD.

    eg. 20271428
3.  **Size selection:** Add the size in the size/qty field.

    1. RA -  Random size.
    2. Incase of half sizes, Myntra notation for them is - 5.5, write 5.5.
    3. Incase of normal sizes, write the size as is.

    eg. 5.5, 8.5, 8
4. **Set Profile and Proxy** from the remaining 2 fields. NOT RECOMMENDED TO USE PROXY AS IT MIGHT MAKE THE FLOW SLOWER. OKAY ON RESTOCKS.
5. **Monitor Delay and Error Delay:** Should be explanatory, Monitor Delay is the delay it has between each check, and Error Delay is the delay the automation adds after an error. Keep 1.0 for both by default. On a slower site, increase the error delay to 3.0/5.0.
6. **Create Task Counter:** You can increase the counter to duplicate the same task multiple times if you wish to try on multiple sizes.

Once all is done, add the task and then, all other buttons should be explanatory.&#x20;

Use **Start All** to start all tasks, **Stop All** to stop all tasks, **Delete All** to Delete all tasks.

To micromanage tasks, it has buttons by the side to manage it, and each should be simple to decipher by the icons.



## COMMON FAQ/ERRORS



**1)  ERROR GETTING CSRF TOKEN - CART NOT PAYABLE (STATUS: 403)**

-> The cookie could be incomplete, copy another cookie and convert the same. Or, you might have been soft banned (rate limit) by the website, try again in a bit.

**2) ERROR GETTING CSRF TOKEN - CART NOT PAYABLE (STATUS: 400)**

-> The product you're trying to checkout might already be OOS or is inactive/unavailable.

**3) ADDRESS FETCH ERROR**

-> The cookie you've converted might either not be converted correctly or is incomplete, try another cookie.

**4) FETCH ERROR AFTER CAPTCHA FETCHED (RATE LIMIT/COOKIE INVALID)**

-> Either the CapMonster Key is wrong/not saved/inactive/out of balance/capmonster service is down, or the login cookie is invalid (the one you converted).



