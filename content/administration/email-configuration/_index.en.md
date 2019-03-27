---
title: Email configuration
weight: 15
pre: <b>3. </b>
---

You need to set up email to send the notifications about the changes in the project, or send the invitation to other people join to MyCollab. You can set up the email configuration while set up MyCollab, or you can can change these settings later in the `%MYCOLLAB_HOME%/config/application.properties`. Open the config file, and find the section
```
mail.smtphost= <your smtp host>
mail.port= 
mail.username=
mail.password=
mail.startTls= // true if secure method is startTls or false if otherwise
mail.ssl= // true if secure method is ssl or false if otherwise. SSl and startTls must not have the same true value
```

Change these properties to the appropriate values according to the email provider user manual. Restart MyCollab to take the change is affected.