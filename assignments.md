---
title: Assignments
layout: default
start: 01 Sep 2020, 00:00 (Europe/Zurich)
index: 3
---

### Administrivia

Over the course of the semester, we will post five assignments that will require you to code up five moderately complex Scala applications (one per each assignment) that highlight certain theoretical aspects of the course.

Every assignment will become available on this website at due time (usually after the deadline of the previous assignment). We will be notifying you about the arrival of new assignments on the [mailing list](/index.html#mailing-list), so be sure to join it.

### Team Registration

We encourage you to team up when working on assignments. Teams can consist of one, two or three students and should not intersect with each other. It is okay to share ideas between teams, but sharing code is prohibited.

<!-- Please fill in the form below before __September 29, Sunday__:

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfO9b6a5TIFKUNTCFmy5zjYQ-5I8WckXB8KK_vFHps7J4QwNw/viewform?embedded=true" width="640" height="650" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe> -->


### Getting started with Scala

All development during the course will be done in Scala. Here we provide the instructions
how to setup the Scala development tools.

First, you need to install [the sbt build tool](http://www.scala-sbt.org/download.html).
You can run `sbt compile` and `sbt run` in the console to compile and run the project.

We recommend using [VS Code](https://code.visualstudio.com/) with the
extension [Metals](https://marketplace.visualstudio.com/items?itemName=scalameta.metals)
for development. It suffices to open the assignment directory in VS Code.

You can also use [IntelliJ IDEA](https://www.jetbrains.com/idea/download) for development.
You can import the project into the IDE:

1. Click `Import Project`.
1. Select the directory where you unpacked the assignment.
1. Click `Open`.
1. Select `Import project from external model > SBT`, click `Next`.
1. Click `Finish`.

If you don't like IntelliJ IDEA, feel free to use alternative editors or even develop in the console,
as long as your project passes our tests.

### Submitting your solutions

<!--
1. Register your team, if you haven't done so already. Note that the teams are updated manually, so if you just registered, the bot should be updated the next (more-or-less) morning.
-->

1. Zip your project directory, making sure that:
  * you haven't created or removed any files from the provided template for the corresponding project. For instance, if the template contained files Arithmetic.scala and Terms.scala in /src/main/scala/fos, don't move these files around or create additional helper files.
  * you don't zip the `target` directory, which contains binary files that might trip Google's anti-virus.

1. Send the archive produced during the previous step to grading bot's email address: [lamp.fos.bot@gmail.com](mailto:lamp.fos.bot@gmail.com)
  * The subject of the email should be "Project X (YYYYYY, ZZZZZZ, ...)", where X is the number of the project, and YYYYYY/ZZZZZZ/... are SCIPER numbers of the authors.
  * The body of the email doesn't matter, because our grading bot can't read.
  * Don't forget the attachment.

1. Wait for a response from the grading bot. The response will either contain a rejection notice along with the detailed error message or an acceptance notice with the results of running your submission against our test suite.

1. If you don't receive a response from the bot, or you get your submission rejected without a good reason, contact the staff.

1. If you're not content with your results, follow the instructions in the reply email to try and improve your score. You can retry the submission as many times as you want before the deadline hits, and that won't result in any penalties to your final score.

### Late submissions

If you miss a deadline, you can still submit your project, however your grade will be reduced. Late submissions will be graded with 30% deduction of points for every day after the deadline.

### Feedback on submissions

If you need more detailed feedback on your submission, please send an email to
one of the assistants to reserve an office slot, so that we may study your code
together.

### FAQ

In case of error, please check the following list:

1. You need to submit assignments using your _EPFL email address_.
2. Make sure your email is not encrypted.