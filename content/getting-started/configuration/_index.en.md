---
title: Configuration
weight: 20
pre: <b>3. </b>
---

You can change the MyCollab settings such as server name (or IP), port, emails etc. in the configuration file locates in $MYCOLLAB_HOME/config/application.properties

```
#=====================================================
# You can visit link https://doc.mycollab.com/getting-started/configuration/
# to get all configuration fieldBuilder and their meanings
#=====================================================

#=====================================================
#    SITE CONFIGURATION
#=====================================================
app.siteName=MyCollab
app.notifyEmail=<email notification>

# You do not change the rest server information if you are not sure what you are doing
server.address=localhost
server.apiUrl=https://api.mycollab.com/
server.storageSystem=file
server.siteUrl=http://%s:%d/
server.resourceDownloadUrl=http://%s:%d/file/
server.cdnUrl=http://%s:%d/assets/

#=====================================================
#    DATABASE CONFIGURATION
#=====================================================
spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost/mycollab?useUnicode=true&characterEncoding=utf-8&autoReconnect=true&rewriteBatchedStatements=true&useCompression=true&useServerPrepStmts=false&verifyServerCertificate=false&useSSL=false&allowPublicKeyRetrieval=true
spring.datasource.username=<username>
spring.datasource.password=<password>

#=====================================================
#    MAIL CONFIGURATION
#
# SMTP Mail setting to use in 
#=====================================================
mail.smtphost=
mail.port=0
mail.username=
mail.password=
mail.startTls=false
mail.ssl=false

#=====================================================
#    ERROR REPORTING
# This email is used to receive any error causes during 
# MyCollab running. It just collects java stack trace not
# any end user sensitive data. In case you are serious not
# want to send report automatically to our team, you can
# leave this field to empty
#=====================================================
mail.errorTo=error@mycollab.com
```