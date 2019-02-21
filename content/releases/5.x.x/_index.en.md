---
title: MyCollab 5.x.x
weight: 5
pre: <b>1. </b>
---

Version 5.4.10
--------------

**Library Upgrades**

* Vaadin 7.7.10, Jackrabbit 2.15.3
* Other libraries

**Improvements & New Features**

* Update CRM links mobile

**Bug Fixes**

* Customize table columns may cause duplicated items

Version 5.4.9
-------------

**Library Upgrades**

* Mybatis 3.4.4, Infinispan 9.0.0.Final, Flyway 2.3.0, Quartz Scheduler 2.3.0
* Vaadin 7.7.9, Jackrabbit 2.15.2
* Other libraries

**Improvements & New Features**

* Support CRM mobile
* Update languages

**Bug Fixes**

* Display the wrong total opportunities value
* Several text areas don't support the line-end character


Version 5.4.8
-------------

**Library Upgrades**

* Jackrabbit 2.15.1
* HikariCP 2.6.1, Cglib 3.2.5

**Improvements & New Features**

* Theme modification
* Allow upload icons for CRM account
* Several minor bug fixes

**Bug Fixes**

* [Premium] Can not edit bug in the mobile application
* Export files may fail to export wrong file type


Version 5.4.7
-------------

**Improvements & New Features**

* Export CSV file without header
* Update Bulgarian language

**Bug Fixes**

* Always export to CSV even if user select PDF or Excel type in some cases
* Can not send the email notification for edit CRM entities

Version 5.4.6
-------------

**Library Upgrades**

* Jackrabbit 2.15.0
* DynamicReports 5.0.0
* Guava 21.0
* Other libraries

**Improvements & New Features**

* Easy to navigate project tickets
* Drag & drop support in ticket dashboard
* Update language files
* Other minor improvements

**Bug Fixes**

* Can not install two different MyCollab instances on the same server
* UI issues on IE and Edge.


Version 5.4.5
-------------

**Library Upgrades**

* Guava 20.0
* Other libraries

**Improvements & New Features**

* [Premium] Replace the own customer logo in front pages
* [Premium] Replace the own customer logo in emails
* [Premium] Check ticket satisfy the current query criteria to display or hide
* Display order of show more tickets
* Display color of milestone and task in associated views
* Remove redundant javascript libraries in mobile browser
* Other minor improvements

**Bug Fixes**

* Go to previous entry of task, bug go to the first entry
* Unresolved tickets display wrong entries
* Throw error when user enter the empty page view without having the write permission

Version 5.4.4
-------------

**Improvements & New Features**

* Revise the menu navigator
* The project UI is more intuitive
* Update Spanish language
* Other minor improvements

Version 5.4.3
-------------

**Library Upgrades**

* Hiraki CP 4.5.1
* Jackson 2.8.4
* Vaadin 7.7.3
* Jackrabbit 2.13.4
* MySQL 5.1.40
* Jetty 9.3.12.v20160915
* Other libraries

**Improvements & New Features**

* [Premium] Kanban board for phases/sprint
* [Premium] Close phase, assignments have option to close the sub-assignments
* Fix UI issues on Firefox, Safari
* Simplify the views of tasks, bugs, and risks
* More stable of mobile web application
* Support Indonesian language (Contributor: farizichwan), Update other languages
* Other minor improvements

**Bug Fixes**

* [Premium] Can not mass update project risks
* [Community] Can not preview bug, task on mobile web page because of lacking time service
* Update the localization updates of Crm module
* Lead source chart throws error
* Can not display the opportunity when user click chart legend
* Can not send the opportunity in several special cases
* Minor issues are fixed on Crm module
* Update the mail settings is not effect immediately

Version 5.4.2
-------------

**Library Upgrades**

* Vaadin 7.7.0
* Jackrabbit 2.13.2
* Jackson 2.8.2
* Other libraries

**Improvements & New Features**

* Allow users to drag file to upload
* Add the Russia language, and update the language files
* Minor improvements

**Bug Fixes**

* [Premium] Can not receive the update notification from some clients
* Display date format associates with user language
* Can not recognize some languages files due to the incompatibility issue of getlocalization service
* Can not create the new case, campaign
* Can not export the CSV, Excel with Asia languages like Japanese, Korean and Chinese
* Not display the user language in the tooltip
* Project component, version can not display rich text description
* Other minor issues fixed

Version 5.4.1
-------------

**Library Upgrades**

* Java Mail 1.5.6
* Jetty 9.3.11.v20160721
* Other libraries

**Improvements & New Features**

* Update the language files. Add the Danish (Contributor: KrestenB), Spanish (Contributor: jfigueroa) to the supported list 
* Minor improvements

**Bug Fixes**

* Can not send email for user who do not have the avatar
* Remove the false thread causes the CPU always high 100%


Version 5.4.0
-------------

** Notes

* Due to the clean code and other improvements of MyCollab, we only support Java 8 and higher

**Library Upgrades**

* Jackrabbit 2.13.1
* Spring framework 4.3.2.RELEASE
* Vaadin 7.6.8
* DynamicReports 4.1.1
* Jetty 9.3.10.v20160621
* Jackson 2.8.1
* Flyway 4.0.3
* MyBatis 3.4.1
* Hikari CP 2.4.7
* Freemarker 2.3.25
* Other libraries

**Improvements & New Features**

* Improve the email template theme
* Remove redundant files in the community edition
* Support German, French, Portuguese (Brazil) and Chinese languages (Contributor: Marco Gantenbein, BonnetYB, Cpichard, Dawnchen, Wilkance, Eduardofl)
* Other minor improvements

**Bug Fixes**

* Fix the pdfEncoding mistyping in the reporting module (Thanks to mchubby)
* The NumberFormatException throws when the user types a valid day duration in task form. 
* [Premium] Not adding the second cache layer to the service classes
* [Premium] Can not remove favorite flag in Favorite view 
* [Premium] Fix the form layout text 
* [Premium] Not include the total risks in the milestone information

Version 5.3.4
-----------------------------

**Library Upgrades**

* Spring 4.3.0.RELEASE 
* Flyway 4.0.2

**Improvements & New Features**

* [Premium] Allow adding the new assignment in calendar view
* [Premium] The new Hourly weekly report
* Change the template engine from Velocity to Freemarker
* Allow customizing the report fieldMetas
* Externalize more strings for localization
* Reduce the SQL queries in schedule task by caching objects
* Support German language (Contributor: Marco Gantenbein)
* Other minor improvements

**Bug Fixes**

* [Premium] Can not quickly edit value in the popup field
* Send emails to project assignments are not successfully in a few special cases

Version 5.3.3
-----------------------------

**Library Upgrades**

* Joda Time 2.9.4
* Jackson 2.6.6
* Other libraries

**Improvements & New Features**

* Allow to customize the report fieldMetas in the project module
* Allow project member can set time for task and issue
* Apply the date formats in report and tooltip
* Support localization for languages easier
* Support running MyCollab as startup scripts in Linux OS
* Allow the site owner can allow other users can not see email
* Other improvements

**Bug Fixes**

* [Premium] Time-log window causes error in several special cases
* Can not search projects in the project list view
* Timezone on several date fieldMetas are not correct
* Not check validate dates in the issue entry
* Upload project favicon does not work with Java 7
* Can not change the timezone in the user profile view in several cases

Version 5.3.2
-----------------------------

**Library Upgrades**

* Spring framework 4.2.6.RELEASE
* MySQL Connector 5.1.39
* Jetty 9.2.17.v20160517
* Jsoup 1.9.2
* Other libraries
 
**Improvements & New Features**

* Support DLS in timezone setting
* Revise the invitation process simpler
* Remove redundant libraries to reduce the download size
* Other minor improvements

**Bug Fixes**

* Several email providers can not send email (Yahoo and several company email providers)
* Return from forgot password throws error

Version 5.3.1
-----------------------------
**Library Upgrades**

* Vaadin 7.6.6
* Other libraries

**Improvements & New Features**

* [Community] Allow site administrator can change the site basic information
* Add the new task navigation buttons
* Add the new issue navigation buttons
* Site administrator can define the default timezone, language, date formats
* Do not limit the supported languages
* Display the custom date format of account in all form fieldMetas
* General performance improvement
* Other minor improvements

**Bug Fixes**

* [Premium] Not edit hours in time edit window can cause the system error

Version 5.3.0
-----------------------------
**Library Upgrades**

* Mybatis 3.4.0, Mybatis spring 1.3.0
* Jetty 9.2.16.v20160414
* Quartz 2.2.3
* Vaadin 7.6.5
* Hiraki CP 2.4.6
* Other libraries

**Improvements & New Features**

* [Premium] Add views to manage projects/tasks and time of client
* [Premium] Print invoice page
* [Premium] Allow attachment in the invoice form
* [Premium] Allow attachment in the risk form
* Allow site owner create the admin user instead of system default user
* Create sample project for the new MyCollab installation
* Add the context help for project forms
* Change the issue workflow similar than Bugzilla
* Allow to edit description in file management
* Allow user add attachments in phase form
* Revise the bug workflow in  the kanban view
* General performance improvement in project module
* Other minor improvements

**Bug Fixes**

* [Premium] Report url resolver redirect to the user dashboard when browser page reload
* [Premium] Standup url resolver redirect to the user dashboard when browser page reload
* [Premium] It is difficult to quick edit value of popup field
* Clean resources properly when user signout MyCollab
* Get following items return the wrong list in several cases
* Tooltip still show after mouse over event occurs
* Can not preview image file which has special characters

Version 5.2.12
-----------------------------
**Library Upgrades**

* Cglib 3.2.2
* Other libraries

**Improvements & New Features**

* [Premium] Allow uploading client logo
* Allow uploading project logo
* Can adjust the parent-child relationship of tasks
* New Project list view
* Adjust the java memory settings
* Other minor improvements

**Bug Fixes**

* [Premium] Can not print client page
* Can not modify basic properties of kanban columns
* Several cases of bug dependencies do not work as expected
* Can not upload/rename the file include the special Unicode characters

Version 5.2.11
-----------------------------
**Library Upgrades**

* Joda Time 2.9.3
* Mybatis spring 1.2.5
* Other libraries

**Improvements & New Features**

* [Premium] Export timesheet into PDF and Excel
* [Premium] Edit overtime field of time tracking
* Optimize dependency libraries to reduce the distribution file
* Support print function
* Slightly change the JVM settings
* Other minor improvements

**Bug Fixes**

* Report still throws error in some machines due to the order of loading jar files. This version remove this issue 
completely.


Version 5.2.10
-----------------------------
**Library Upgrades**

* Hiraki CP 2.4.5
* Other libraries

**Improvements & New Features**

* [Premium] Invoice management in project
* [Premium] Favorite view in project
* [Premium] Project members can enter overtime hours per assignment
* [Premium] Add 'Can read financial data' permission in project
* [Premium] Tag management supports for components and versions
* [Premium] Favorites management support for components and versions
* [Premium] Can calculate the financial data in timing view
* Support install MyCollab as windows service
* Other minor improvements

**Bug Fixes**

* Form display badly when the field shows long text
* Can not export pdf report at the first time
* File management is more stable
* Re-invite user does not update the latest user information
* Project Member still receive his watched items updates though he leaved the project already

Version 5.2.9
-----------------------------
**Library Upgrades**

* Vaadin 7.6.4
* Spring framework 4.2.5.RELEASE
* Jackrabbit 2.12.1
* Jetty 9.2.15.v20160210
* Flyway 4.0
* Commons Collection 3.2.2
* Other libraries

**Improvements & New Features**

* [Premium] Tag management is supported
* [Premium] Project client management is added
* [Premium] Support tag for phase and risk
* New user group for task and bug views
* Allow to change color column of Kanban board
* Improve error handling page mechanism
* Other minor improvements

**Bug Fixes**

* [Premium] Display wrong list of history fieldMetas in several special cases
* [Premium] Save the new project throws error
* Rename option column may cause the error in trending chart
* Websocket timeout error

Version 5.2.8
-----------------------------
**Improvements & New Features**

* [Premium] Revise the Calendar view
* Support project template
* Add 'Won't Fix' status to bug workflow
* Other minor improvements

**Bug Fixes**

* [Premium] Export project timelog is failed
* Delete the selected resource is failed

Version 5.2.7
-----------------------------
**Library Upgrades**

* Vaadin 7.6.3
* MyBatis 3.3.1
* Other libraries

**Improvements & New Features**

* Display issues, risks in Gantt chart besides tasks, milestones as well
* Several minor improvements
* Add lead field to the project
* Display delete action in the activity stream
* Enhance and improve stability of Gantt chart
* Improve the stability of upgrade process on Windows
* [Premium] Support calendar event types are issues, risks, milestones

**Bug Fixes**

* [Mobile] Throws silent exception when display the empty activities in account
* Throws exception when assign the Project Owner role to the existing user
* Not display deleted entries in the activity stream

Version 5.2.6
-----------------------------
**Library Upgrades**

* Jetty 9.2.14.v20151106
* Other libraries

**Improvements & New Features**

* Lighter email template
* Send overdue assignments email
* Notify project members when the new member join

**Bug Fixes**

* Can not assign user as the account owner
* Can not load fonts of reporting
* [Premium] Display events with no project throws exception
* [Mobile] Can not redirect the login view when the obsolete password id stored in the local storage

Version 5.2.5
-----------------------------
**Library Upgrades**

* Vaadin 7.6.1
* Other libraries

**Improvements & New Features**

* The new mobile UI revised
* Minor UI improvements
* Improve error handling

**Bug Fixes**

* None


Version 5.2.4
-----------------------------
**Library Upgrades**

* Gson 2.5, Guava 19, Jackrabbit 2.11.3, Spring framework 4.2.4.RELEASE
* Other libraries

**Improvements & New Features**

* Add upcoming tasks in the project dashboard
* Customize color of task statuses in kanban board
* Display detail watchers in the sidebar
* The new project dashboard
* Improve theme compatibility
* Several minor improvements


Version 5.2.3
-----------------------------
**Library Upgrades**

* Joda 2.9.1, Hiraki CP 2.4.2, SLF4J 1.7.13
* Spring framework 4.2.3.RELEASE
* Dynamic Reports 4.0.2

**Improvements & New Features**

* Allow inline edit task, milestone and bug summary field in dashboard view
* Minor UI updates

**Bug Fixes**

* Upgrade process still keeps the old version value of class path items

Version 5.2.2
-----------------------------

**Library Upgrades**

* Joda 2.9
* Quartz 2.2.2
* Http component 4.4.4, other libraries

**Improvements & New Features**

* Add timeline tracking chart
* Major UI updates includes animations, consistent UI controls and colors
* Detect more potential issues of installation and give the solutions to users

**Bug Fixes**

* Fix several issues of push events in the corporate networks
* Advanced user layout does not keep values of the simple user layout
* Pretty time text is wrong with several timezones

Version 5.2.1
-----------------------------

**Library Upgrades**

* Spring framework 4.2.2.RELEASE and others

**Improvements & New Features**

* Predefined query for tasks, bugs
* Allow user rename or delete column in the task kanban board
* Do minor UI improvements
* Validate the file permission in the installation script
* Add shutdown script to allow admin can shutdown MyCollab properly
* The new modal window
* Faster form binding and improve the performance a little bit
* Autofill username and password for the login form
* Allow user can switch from push to poll method if their network proxy prohibit the push method

**Bug Fixes**

* Wrong user avatar of assignments in project roadmap view
* Validate date constraints of entity is wrong in several cases
* Calendar information is not refresh if the new set is empty
* Update search query is not effected

Version 5.2.0
-----------------------------

**Library Upgrades**

* Upgrade Gson 2.4, HirakiCP 2.4.1 and more

**Improvements & New Features**

* Make bug management is easier
* Introduce the new roadmap view
* Introduce the calendar of tasks management

**Bug Fixes**

* Word-wrap title for long text of several views
* Task duration calculating with timezone

Version 5.1.4
-----------------------------

**Library Upgrades**

* Upgrade Vaadin 7.5.7
* Upgrade Hiraki CP 2.3.11, Hibernate Validator 5.2.2 and others

**Improvements & New Features**

* Gantt chart bug fixes
* Calculating end date by start date and duration
* Toggle project menu in MS Edge, Firefox is not effective
* Other minor UI improvements
* A lot of reporting enhancements: better layout, more detail information, font awesome and more
* New installer tool, clean release notes and license view

**Bug Fixes**

* Can not change the role of project member
* Several minor bug fixes of reporting

Version 5.1.3
-----------------------------

**Library Upgrades**

* Vaadin 7.5.5
* Spring framework 4.2.1.RELEASE
* Scala 2.11.7, Jackson 2.6.2

**Improvements & New Features**

* Reduce the startup time
* Several minor UI improvements
* Support task predecessors
* Edit inline on Gantt chart
* Many Gantt chart improvements
* Site response is faster by using the proper server push
* More reliable upgrade process

**Bug Fixes**

* Has redundant scrollbar on internet explorer
* Navigate folder by clicking file breadcrumb throws exception in several cases
* Notification setting minimal may cause can not send email
* Better diagnosis error message to the end users


Version 5.1.2
-----------------------------

**Improvements & New Features**

* Menu navigator is easy to understand for geeks
* Improve the product layout general

**Bug Fixes**

* Search in project throws error
* Remove redundant warning message of permission when user access the profile page


Version 5.1.1
-----------------------------
**Library Upgrades**

* Jackson library 2.6.1, DynamicReports 4.0.1, MyBatis 3.3.0, Spring 4.2.0.RELEASE, Infinispan 7.2.4
* Vaadin 7.5.3
* JQuery 2.1.4

**Improvements & New Features**

* New kanban board for project tasks, bugs
* Update attachment display
* Generate thumbnail for images
* Update the task management workflow to remove the task group !!!
* Reduce the time response for heavy loading page
* Improve Gantt chart

**Bug Fixes**

* General bug fixes of file module
* Can not download file folder
* The bug widgets do not refresh when bug status changed
* Can not display tooltip of CRM bug
* Upload files do not show the progress properly


Version 5.1.0
-----------------------------
**Library Upgrades**

* Spring framework upgrade to 4.1.7.RELEASE, Infinispan, MySQL Connector

**Improvements & New Features**

* Redesign the email template
* Can resend the invitation
* Optimize Vaadin widgetsets
* Remove Camel library and reduce the number of threads daemons
* Reduce chart generator memory footprint
* Theme color consistent fixed
* Add outlook smtp help message
* Many minor UI improvements

**Bug Fixes**

* Fix gzip response since the version 5.0.10 uses Jetty 9.3 deprecate servlet gzip filter
* Can not change the default port 8080 on Windows
* MyCollab can not run with Java 7
* Can not run MyCollab in some rare cases due to the order of service beans is not controlled
* Refresh page of bug list and gantt view shows internal error


Version 5.0.10
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.5.0
* Upgrade other libraries: Tika

**Improvements & New Features**

* Make the UI more consistent and minor UI improvements
* Other general improvements

**Bug Fixes**

* System error when user accept the project invitation with project owner role
* Modal window overlays on tooltip


Version 5.0.9
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.4.8
* Upgrade libraries: AspectJ, Jetty, MyBatis, Joda-Time, etc

**Bug Fixes**

* User can not upload non english file name document
* Proper handling system roles
* The resource paths still throw error in several cases
* Email notification could be sent multiple times to the recipients
* Some assets has wrong paths


Version 5.0.8
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.4.7
* Upgrade libraries: HirakiCP, Jackrabbit, Commons-Email, Jetty

**Improvements & New Features**

* Parse html better, display rich html text smoothly
* Improve code quality overall
* Optimize the hash query and improve the site performance a little bit
* Revise the Gantt chart display
* Remove redundant assets and libraries to reduce the size of downloaded file size
* Support send email via StartTls or Ssl/Tls protocols

**Bug Fixes**

* Search project may throw exception in some special case
* Export report document is sometimes failed
* Upload file in page editor throws exception
* Add a new project page throws exception
* Fix several bugs relate to Gantt chart
* Display the new user information when user re-login by another account
* Fix missing assets in email template
* Some views can not display well on internet explorer browser
* Crm menu does not refresh if user logout then login with two different accounts

Version 5.0.7
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.4.6
* Upgrade other libraries

**Improvements & New Features**

* Revise the runner process. Important for auto upgrade feature
* Remove redundant images assets
* Change the default cdn url
* Change the default browser cache of vaadin
* Add context support for project
* Improve sending email with various SMTP settings
* Add warning message if user ask retrieve password without configuring SMTP (#fix per user's feedback)

**Bug Fixes**

* Minor bug fixes on IE browsers when user press button
* Email subject of bug group has project name is null

Version 5.0.6
-----------------------------
**Library Upgrades**

* Upgrade other libraries

**Improvements & New Features**

* Redirect to the server host instead localhost after installing successfully
* Minor change in bug display
* Add help menu in view
* More comprehensive message to instruct user understand field value better
* Request user change username for the first time login after installation
* Increase the size of database connection pool to 50 for heavy load sites
* Improve the build process

**Bug Fixes**

* Display the error message when user upgrade MyCollab failed due to the file permission
* Did not display detail error message when validate form but the empty string
* Install MyCollab in Internet Explorer has several issues

Version 5.0.5.1
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.4.5

**Improvements & New Features**

* Revise the notification window to makes it looks nicer

**Bug Fixes**

* Can not send email in port different 25 in several cases
* Fix log location
* Exception when get the default user avatar


Version 5.0.5
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.4.4
* Upgrade other libraries

**Improvements & New Features**

* Revise CRM comments and history features to make it similar than project module
* Revise the layout of CRM module
* Display comment in CRM activity stream
* Support font awesome in emails
* Minor bug fixes in reporting
* Cache reflection fieldMetas hence upgrade the app performance up to 5%
* Add time summary for bug group, milestone, component, version views
* Allow system admin can change the SMTP setting on the fly
* Enable gzip compression for assets by default
* Replace the old log4j library by logback

**Bug Fixes**

* Checkbox in Chrome, IE has the unintended border
* Other minor CSS issues on IE, Firefox

Version 5.0.4
-----------------------------

**Library Upgrades**

* Upgrade Vaadin to 7.4.3
* Upgrade Jetty Server version
* Upgrade other libraries

**Improvements & New Features**

* Auto update the new MyCollab version
* Ask system admin or warn users need to set up smtp setting for features which need to send email
* The new project file module
* Revise the application variable scopes
* Support quick review with instant tooltip
* Revise the bug list display
* Minor improve on page view
* Display uploaded file size
* Add detail information for uploaded file in tooltip
* Display the friendly timezone name in tooltip

**Bug Fixes**

* The default created time of user should match with the default timezone
* The empty list view of bug, component and version has the horizontal scrollbar
* Fix links of MyCollab document


Version 5.0.3
-----------------------------

**Library Upgrades**

* Upgrade Vaadin to 7.4.2
* Upgrade other libraries: Spring framework, Jackrabbit, SLF4J etc

**Improvements**

* Easier to navigate among projects
* Add search of generic assignments to project
* Revise and do several bug fixes the file module
* Support tooltip for multi select component
* Display pretty time on label and detail date tooltip
* Add description for the project generic assignment
* Revise the invite project member view

**Bug Fixes**

* Edit project member throws exception
* Display bug context menu properly according to coordination of mouse
* Can not change the project information
* Correct year format of contact birthday
* Prevent the issue of can not view bug or bug because the project short name is invalid
* Do not display year in birthday combo box

Version 5.0.2
-----------------------------

**Library Upgrades**

* Upgrade Vaadin to 7.4.1
* Upgrade other libraries

**Improvements**

* Add help message for project views

**Bug Fixes**

* Template select the default locale if the user locale is not existed
* The activity stream service throws exception when saving project page in several special cases
* Export project page include the title in the document
* Saving comment may throw exception in several cases
* Email notification for the created item does not display the detail of information


Version 5.0.1
-----------------------------
**Library Upgrades**

* Upgrade libraries version

**Improvements**

* Optimize SQL query and there are some processes are 2x faster !!!
* Add custom notifiers
* Support default button in windows
* Improve search result of bug list
* Support tag for tasks, bugs
* User is able to manage the favorites
* User is able to select the notifiers when he creates the new bug
* Display number of items in the search panel
* Support tooltip for project message widget
* Screen navigator works more efficiently
* Add more strictly validation constraint to project bug

**Bug Fixes**

* Attachment box in Safari display wrongly
* Query project member tasks show wrong items
* Query project roles did not work
* Export bug list to document throws exception
* Can not sending email in several cases

Version 5.0.0
-----------------------------
**Library Upgrades**

* Upgrade Vaadin to 7.3.10
* Upgrade Spring frameworks to 4.1.5.RELEASE
* Upgrade several Vaadin addons
* Upgrade all libraries up-to-date, there are few name are Infinispan, Apache commons, etc

**Improvements**

* Check the latest version notification
* Replace icons by font awesome
* Revise bug group layout
* Support sub tasks for project bug
* Simplify application configuration (for developers) to utilize convention over configuration
* Using Scala for several back-end components such as scheduler
* Allow assign user in bug view
* Allow deselect assignee in bug or bug
* Revise project and crm views
* Revise the related bug relationship
* Remove redundant css elements
* Fix layout issues in the Internet Explorer browsers

**Bug Fixes**

* Load the empty list of projects throws error in some special cases
* Internal issue causes the lazy views load infinitely
* Save crm call throws exception
* Update time logging but not update the project information immediately
* Tooltip of several entities do not display properly
* Time logging display the double value wrongly some times
* Gantt chart display to miss the last day of bug
* Default permission of guest role is wide open