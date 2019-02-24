---
title: Testing
weight: 10
pre: <b>3. </b>
---

We don't have the set of test cases that cover all MyCollab codebase, but we have the test cases that cover major branches of the critical business of MyCollab. We share these test cases in the folder `test` of the module `mycollab-services-community`.

We use JUnit 5, Spring test framework, assertJ and DbUnit for our integration testing against the H2 database. We are trying to keep the green status for all codes commit to Github, if you changes our codebase then make sure all test cases are passed.