---
title: Migrate Email Data from Yandex to Gmail
author: Hieu Xuan Leu
date: 2023-09-08
category: Mail Configuration
layout: post
mermaid: true
---

## Purpose
In the near future, we'll switch Email service providers. Temporarily stop using Yandex services.
Therefore, migrating Email data from Yandex to Gmail is an important step to backup email data before Yandex accounts stop working **(an additional 21 days from September 10, 2023)**.
Hopefully everyone can back up all email data to Gmail to ensure no loss of important data as soon as possible.

**NOTE:** You need to create a new Google Email account. (Purpose used to Backup Data)
![alt](https://upload.wikimedia.org/wikipedia/commons/a/ab/Gmail2020.logo.png)

## Migrate Email Data
**Step 1: Log in to your Yandex account**

First, make sure you are logged in to your Yandex account.

**Step 2: Allow POP3 access in your Yandex account**

- In your Yandex account, navigate to the settings by clicking on the circular icon in the top-right corner and select **Settings**.

- In the Settings section, choose **Email Client**.

![alt](https://drive.google.com/file/d/1VrLoBpZfvqUFLL2D0NVeM9rOLUZZzIko/view?usp=sharing)

![alt](https://drive.google.com/file/d/1Ye3arGq5ueB7o-zz_es2091kzASor556/view?usp=sharing)

Enable the option "From the pop.yandex.com server via POP3", **Inbox**, **Sent**, **Mark all messages received using the POP3 server as read in the Yandex Mail web interface** and then click **Save**


![alt](https://drive.google.com/file/d/1q-1TGedMj3o3nyzJ6BrPffOuPhYoDbct/view?usp=sharing)

**Step 3: Create a POP3 connection in Gmail**

- Log in to your Gmail account.

- Click on the gear icon in the top-right corner and select **See all settings**.

![alt](https://www.groovypost.com/wp-content/uploads/2022/05/1-see-all-settings.png)

- In the **Accounts and Import** tab, choose **Import mail and contacts**.

![alt](https://drive.google.com/file/d/1gkMPpaX_eeluCwhek9vqPu1l8Qx_o3E2/view?usp=sharing)

- In the pop-up dialog, enter your Yandex email address and click **Continue**.

![alt](https://drive.google.com/file/d/1kUCYpENgdQ1HtscIKhcOK4aLGB16-iq4/view?usp=sharing)

- Next, you'll need to enter the POP3 configuration details for Yandex:
  - **Username:** Enter your Yandex email address.
  - **Password:** Input your password for the Yandex account.
  - **POP Server:** Enter **pop.yandex.com**.
  - **Port:** Choose port **995**.
  - **Connection type:** Select **Use SSL**.

- After you've entered the POP3 configuration details, click **Continue**.

![alt](https://drive.google.com/file/d/1iev9U9ZmbuLQx6lpObSbEaUgA0CUKhNl/view?usp=sharing)

- Select the import options, lick **Start Import**

![alt](https://drive.google.com/file/d/13RIQEeLcuN68_YIF-Waa2dtyA0sAEndC/view?usp=sharing)

- Finish, click **OK**

![alt](https://drive.google.com/file/d/1OUeyxBNdIEFBVJBHxKlhQYBD_YbYzKh4/view?usp=sharing)

After completing these steps, Gmail will be able to retrieve emails from your Yandex account using the POP3 protocol. The emails will be copied to your Gmail inbox, and you can manage them from there.
