---
title: Skills for developing MyCollab
weight: 5
pre: <b>2. </b>
---

MyCollab uses the varieties of frameworks, libraries to develop the entire product. Its main programming languages are Java and Kotlin. We don't have any specific rules which files we should write by Java or Kotlin. But, we try to write the good code, and we found that Kotlin helps us to write cleaner code, less error prone. However, it is difficult to write entire existing codebase in Kotlin. There are tips that many back-end codes are written by Kotlin.

Below are the main frameworks, libraries are used in MyCollab.

## Spring boot
MyCollab uses the micro service architecture, although you can see see it in the community codebase. We use Spring boot 2 to manage all services in MyCollab from both front-end, back-end.

## Mybatis
Mybatis is the persistence framework to interact with MySQL. We use MyBatis customize SQL alot to provide the dynamic query SQL, complex SQL execution. 

## Vaadin
Vaadin is an UI framework for the MyCollab front-end. At this moment, we are using the Vaadin 8.

## Guava
Guava is used extensively in MyCollab as the complementary APIs for the lacking support from the standard Java API. We also use Guava Eventbus for the event-based programming model in MyCollab project.

## Quartz
The scheduler framework. All MyCollab schedule tasks are the Quart jobs that are managed as Spring services.