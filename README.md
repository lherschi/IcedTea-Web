# IcedTeaWeb
[![Build Status](https://travis-ci.com/AdoptOpenJDK/IcedTea-Web.svg?branch=master)](https://travis-ci.com/AdoptOpenJDK/IcedTea-Web)

This repository contains all sources of IcedTeaWeb. 

## About IcedTeaWeb
IcedTeaWeb is an open source implementation of [JSR-56](http://www.jcp.org/en/jsr/detail?id=56) that is better known as Java Web Start.

## Development origin
The project was formerly hosted as part of the [icedtea.classpath.org](https://icedtea.classpath.org) project but moved to github.

The 1.7 and 1.8 release branches of IcedTeaWeb have been migrated to GitHub for fixing bugs in the previews releases.
Next to this a new project structure has been established in the `master` branch.
Here the project is being migrated to Maven and more usage of Java 8 APIs are being introduced.
Based on this IcedTeaWeb can be transformed to a general WebStart / JNLP API that JDK and tool vendors can use to offer JNLP functionality.
A good example is [OpenWebStart](https://openwebstart.com/) that will be based on IcedTeaWeb.

All issues of the former Bugzilla issue tracker at classpath.org were already migrated to GitHub and marked by the `bugzilla-import` label.

## First Timers Support
We love open source. Based on this we develop IcedTeaWeb as an open source project.
If you are new to open source development we have some specific issues for you.
Just have a look at [all issues with the `good first issue` label](https://github.com/AdoptOpenJDK/IcedTea-Web/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22).
This issues are reserved for people who never contributed to Open Source before.
We know that the process of creating a pull request is the biggest barrier for new contributors.
This issues are for you 💝 We use such issues for example to get involved at [Hacktoberfest](https://hacktoberfest.digitalocean.com).
If you want to know more about open source development and contribution in general you should have a look at [this overview](https://github.com/firstcontributions/first-contributions).

## License
The project is released as open source under the GPLv2 with exceptions.
