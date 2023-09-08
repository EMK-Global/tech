---
title: Migrate Email Data from Yandex to Gmail
author: Hieu Xuan Leu
date: 2023-09-08
category: Mail Configuration
layout: post
mermaid: true
---

**Step 1: Log in to your Yandex account**

First, make sure you are logged in to your Yandex account.

**Step 2: Allow POP3 access in your Yandex account**

- In your Yandex account, navigate to the settings by clicking on the circular icon in the top-right corner and select "Settings."

- In the Settings section, choose "Email Client".

-Enable the option "From the pop.yandex.com server via POP3", "Inbox", "Sent", "Mark all messages received using the POP3 server as read in the Yandex Mail web interface." and then click "Save."

**Step 3: Create a POP3 connection in Gmail**

- Log in to your Gmail account.

- Click on the gear icon in the top-right corner and select "See all settings."

- In the "Accounts and Import" tab, choose "Add another email account."

- In the pop-up dialog, enter your Yandex email address and click "Next."

- In the "Name" field, enter the display name you want when sending emails from this Yandex account through Gmail.

- Next, you'll need to enter the POP3 configuration details for Yandex:
  - **Username:** Enter your Yandex email address.
  - **Password:** Input your password for the Yandex account.
  - **POP Server:** Enter `pop.yandex.com`.
  - **Port:** Choose port 995.
  - **Connection type:** Select "SSL/TLS."

- After you've entered the POP3 configuration details, click "Next."

- Gmail will then ask if you want to send email from this Yandex account through Gmail. Choose "Yes" if you wish to do so.

**Step 4: Verify and complete the configuration**

Gmail will perform a check on the connection information with your Yandex account. Once the verification is complete, you'll have the option to configure "Send As" and "Check mail from other accounts" settings if desired.

After completing these steps, Gmail will be able to retrieve emails from your Yandex account using the POP3 protocol. The emails will be copied to your Gmail inbox, and you can manage them from there.

Please note that Yandex and Gmail may change their settings and configuration methods over time, so be sure to check their help documentation or support if you encounter specific issues.