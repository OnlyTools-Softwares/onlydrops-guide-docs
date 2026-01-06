---
description: >-
  This command line automation tool helps you post multiple entries to skicks
  raffles.
---

# SaneAIO Raffles

### Installation

* Download Python 3.10 [on Windows - from Microsoft Store](https://apps.microsoft.com/store/detail/python-310/9PJPW5LDXLZ5?hl=en-us\&gl=us) and [for Mac from the Official Site.](https://www.python.org/downloads/release/python-3100/) &#x20;
* Open a command prompt window on Windows or a terminal window on Mac.
* The below videos can be followed both on Mac and Windows in similar fashion.
* Install the setup.txt file as shown in the video, it will install all required modules. VIDEO: [https://i.imgur.com/wy8nNQS.mp4](https://i.imgur.com/wy8nNQS.mp4)
* Run the saneaio-raffles.py file. VIDEO: [https://i.imgur.com/FBz4NzD.mp4](https://i.imgur.com/FBz4NzD.mp4)

### Setting Up

**profiles.json** : Add your addresses, instagram usernames, mobile numbers and names in this particular file in the mentioned example\_profiles.json file.

**proxies.txt :** To make your entries even unique, we've added proxy support. Add your proxies line by line in "ip:port:user:pass" format (make sure they are each in a different line).

**.env :** Add the relevant keys (auth key and captcha key) and discord notification webhook. The Auth Key is your ACO key (the same key you use everywhere).

!!! warning
    If you don't find the .env file in your folder (specially in MacOS), it might be hidden. Press CMD + SHIFT + . (dot) key, will make it visible and then open it with TextEdit.

#### How To Get The Captcha Key?

Head to capmonster.cloud, you can setup your account, get your key from the capmonster.cloud/dashboard and recharge through card/bitcoin and as low as 1-2$ is enough for MONTHS!

![CapMonster Dashboard](../assets/Screenshot%202022-11-21%20at%2011.23.15%20PM.png)

### Running the Automation

Once the above has been set, make sure you are connected to a secure network (use Cloudfare WARP to make it more secure - masks your IP).

Run the .py file in terminal or command prompt, as per your operating system, or just simply right click on the file and run on python.

Follow the prompts from the script and enter each detail carefully.&#x20;

**Raffle Links:** These are just slightly different from the actual raffle link, and have a format similar to #gf\_formid at the end.

**Size List/Size Choice:** Here, you enter the list of sizes, seperated by a '/', to instruct the script to only go for a set list of sizes, the script ignores all other sizes and randomly distributes the entries between these sizes.

**Use Proxies (y/n):** You have the option to run with or without proxies. Using proxies is recommended.

![SaneAIO Raffles](../assets/saneaio_raffles.png)

!!! warning
    If you see any error, open a ticket to get it resolved.

