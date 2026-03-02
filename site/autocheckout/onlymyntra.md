---
description: An auto-checkout tool for the most chupa-rustam site, Myntra!
---

# OnlyMYNTRA

## Downloading the tool, i.e, the Browser Extension

#### To download the latest version of the extension, click on the link below.

**[OnlyMyntra v1.0 [with Captcha Solver API]](https://s3.onlytools.in/saneaio-downloadable-content/releases-or-downloads/OnlyMYNTRA%20v1.0.zip)**

!!! success
    Make sure you've been provided a license key by the team before trying to set this up, if not, please ask if your membership is eligible for one.

Once you're done installing it, the first popup, i.e, auth should look like this:

![Login page](../assets/OnlyMyntra_LOGIN.png)

Once you see this page, fetch your key, and paste it into the box over the "Enter your key to activate" placeholder, once pasted, click on activate.

![Key activation](../assets/OnlyMyntra_KEY.png)

!!! success
    **NOTE:** You don't need to do this every time you want to use the tool, once verified and logged in, it should stay that way as long as you don't change your WiFi (your key is bound to your IP), or the key has been revoked.

![Size Selection and Refresh Interval Settings.](../assets/OnlyMyntra_SETUP.png)

**Size Selection:**  With this dropdown setting, you're able to set your preferred size for checking out. If you've no such preference, and buy solely to flip, "**Random"** is an option that selects any size for you at random, and continues the checkout flow.&#x20;



**Refresh:** With Refresh, you're able to choose between a bunch of speeds, i.e, the refreshing interval to check the stock status of any product.

* _**Sonic Mode:**_ The fastest, script executes as soon as the last reload is complete (+ 0 seconds).
* _**4x:**_ The most recommended option on most drops, does not get as many "too many request" flags (+1 seconds)
* _**2x:**_ (+2 seconds).
* _**1x:**_ (+4 seconds).
* _**Restock Mode:**_ The safest, script executes every few seconds, so as to not send too many requests and possibly destroying your captcha pass probability and/or increasing bot activity. (+ 5 seconds).

Then, **Toggle ON** the slider, and once done, **SAVE** the settings.

![Settings saved](../assets/OnlyMyntra_SAVED.png)

### BONUS - CAPTCHA SOLVER:

**Configuring Captcha Solver API:**

1. Head over to [http://azcaptcha.com](http://azcaptcha.com), the support ImageCaptcha solver service.
2. **Login to the service**, use Google or Sign Up for an account.
3. Once in, you should be redirected to the [Client Dashboard.](http://azcaptcha.com/clients/dashboard.php) On the dashboard homepage and over to the right, you can see _**API KEY,**_ click on **SHOW** and then _copy_ the same.
4. Head over to OnlyMYNTRA ACO's (unzipped) file location, select the _**js**_ folder, open _**shared.js**_ in any Text Editor (Notepad/TextEdit). Paste the copied _**KEY**_ over there between the marked " " space.
5. Once pasted, re-open your browser, head over to the [Extensions Manager](chrome://extensions) and click on the **Reload (↻)** arrow.
6. Done, you've successfully reloaded your extension after the change.&#x20;



!!! warning
    **NOTE:** The AZCaptcha solver API provides you with 0.02$ in Free Credit to use the solver with 50 some Captchas. If exhausted, you can recharge from the [website's dashboard](http://azcaptcha.com/clients/pay.php).

    **Pricing per 1000 attempted Captchas** = 0.4$

    **Minimum Recharge** = 10$



Now, head over to any product link, viola, sit back and enjoy!





