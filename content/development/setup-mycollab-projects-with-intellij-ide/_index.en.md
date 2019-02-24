---
title: Setup Mycollab projects with IntelliJ
weight: 1
pre: <b>1. </b>
---

You can customize the community MyCollab edition freely to fit your team's requirements and you can controbute back to the community follows the GPL v3 terms. 

## Clone MyCollab on Github

Clone MyCollab on Github https://github.com/MyCollab/mycollab, you should watch this project and fork it on Github. It would be nicer if you star MyCollab, it would encourage us to share our works to the community without any fee.

## Import MyCollab projects to IntelliJ

Open the IntelliJ, and create the new project from the existing sources `Files > New > Project from existing sources ...` then you choose `Import project from external model: Maven`

Then select import options, tick two non-default options `Search for project recursively` and `Import Maven projects automatically`. Follow next steps to finish

![Import Maven projects](/images/development/import_maven_projects.png)

Wait for a couple minutes to let IntelliJ import MyCollab projects.

## Install MySQL database and create MyCollab schema
Go to MySQL site, and download the latest MySQL database. At least, your MySQL version is greater than 5.6.

Create MyCollab schema by executing this command
```
CREATE SCHEMA `mycollab` DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci ;
```

## Run MyCollab program

Choose to run MyCollab application, 
![Run MyCollab](/images/development/run_mycollab.png)

then you can setup the first MyCollab program as the step of [installing MyCollab](//getting-started/installation/#install-mycollab-on-your-server). Then it is done!