---
title: MyCollab 7.x.x
weight: 7
pre: <b>3. </b>
---

Version 7.0.2
-------------

**Library Upgrades**

* Vaadin 8.7.2, Mybatis 3.5.1

**Bug Fixes**

* Can not send the email notification to all members in the project
* Not display the permissions when editing the project member
* Display the pretty time against the UTC timezone instead of the user timezone

**Improvements & New Features**

* [Premium] Can change the border color of action, option or danger buttons
* [Premium] Milestone display the wrong logging time in some special cases
* Support bulk invitations of users
* Minor UI improvements
* Support versions, components relationship in task, and risk
* Support relationship among tickets
* Easy navigating among tickets by ticket key

Version 7.0.1
-------------

**Improvements & New Features**

* Add file module to the project
* Manage email verification statuses

**Bug Fixes**

* Show error message when user edit ticket which has unset duration value
* Some long text don't display in the box
* Can not display the right date value in project notification

Version 7.0.0
-------------

**Library Upgrades**

* Java driver, Mybatis, Spring boot, Vaadin, Infinispan, etc.

**Improvements & New Features**

* Improve the overall performance
* Remove the CRM, and File Management module
* Support multiple database. Tested MyCollab with MySQL, H2
* New theme
* Mobile friend-ly support
* Upgrade the UI pages to Vaadin 8
* Support java 8 date time
* Reliable testing test cases
* Can reuse the resource assets across multiple MyCollab instances
* Update localization from the community
* Support basic report features in the community version

**Bug Fixes**

* Can not reset password
* Do not display project dashboard when project is archived
* Only display open projects in the project list view
* Export to Excel documents are failed in some categories
* Can not search by types in the ticket dashboard
* Export files support localization
* Admin can see all projects in the organization not only their involved projects only
* Do not display the changesets of Project type
* Fix issue can not send notification for some users
* Fix issue can not send email invitation when invite user

