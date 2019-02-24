---
title: Installation
weight: 15
pre: <b>2. </b>
---

## Check Java requirements

You must need [Java JRE 1.8 or higher](https://www.java.com/en/) to run MyCollab. Before you begin, you should check your current Java installation by using the following command:

```
java -version
```

## Create the new MySQL Schema

Create the new MySQL schema with the following command
```
CREATE SCHEMA `mycollab` DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci ;
```

## Download MyCollab

Go to https://mycollab.com/on-premise/ and select the appropriate MyCollab distribution for your organization. Download it and unzip on your local server, from now let's call $MYCOLLAB_HOME is the folder where you unzip MyCollab distribution.

## Install MyCollab on your server

Start MyCollab is different between Windows, and Unix. 

{{%expand "Windows" %}}
Open the Windows Explorer, go to the folder `$MYCOLLAB_HOME/bin` and click the bat file `startup.bat`
{{% /expand%}}

{{%expand "Linux, MacOS" %}}
Open the terminal, go to the folder `$MYCOLLAB_HOME/bin` and run the script file `startup.sh`
{{% /expand%}}

The default port of running MyCollab is 8080. You are able to change the port by edit the value of the key `server.port` in the template configuration file `$MYCOLLAB_HOME/config/application.properties.ftl`. After running the executable file `startup.sh` (on Linux / MacOS) or `startup.bat` (on Windows) then you open the browser with the address `http://<serveraddress>::<port>`

{{% notice info %}}
The server address could be the server name or the IP value depends on your specific environment
{{% /notice %}}

You fill the appropriate values per the page instructions

![Set up page](/images/installation/Setup_Page.png "Setup Page")

and press 'Setup' when you've done. Wait for a couple of minutes to let MyCollab prepare the database, and other settings. After it is done, it will redirect you to the site setting page

![Setting up page](/images/installation/Setting_Page.png "Setting Page")

Choose your admin username/password, and the date time format then press `Setup` button, you are ready for using MyCollab!