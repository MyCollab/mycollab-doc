---
title: Manual Upgrade
weight: 10
pre: <b>2. </b>
---

Manual upgrade is similar than [installing the new MyCollab instance](/getting-started/installation/), except you re-use the database files and the file assets of the previous version.

## Stop the current MyCollab running

{{%expand "Windows" %}}
Open the Windows Explorer, go to the folder `$MYCOLLAB_HOME/bin` and click the bat file `shutdown.bat`
{{% /expand%}}

{{%expand "Linux, MacOS" %}}
Open the terminal, go to the folder `$MYCOLLAB_HOME/bin` and run the script file `shutdown.sh`
{{% /expand%}}

## Download MyCollab

Go to https://mycollab.com/on-premise/ and select the appropriate MyCollab distribution for your organization. Delete the folders `bin`, `lib`, `config`, `i18` and unzip the downloaded file to the existing MyCollab folder.

{{% notice warning %}}
Do not delete the entire old MyCollab installation folder before getting everything done! All of file assets are kept in the hidden folder .mycollab. If you delete this folder then all file uploads such as attachments, profile pictures, documents, etc. will be deleted permanently.
{{% /notice %}}

Then you follow the instruction [Install MyCollab on your server](/getting-started/installation/#install-mycollab-on-your-server), and re-enter your database information, mail settings, etc. Then it will redirect you to the login page without setting up the application parameters again.