# JDK9 PNG Writer Backport [![License](https://img.shields.io/badge/license-GPL2+CE-blue.svg)](http://openjdk.java.net/legal/gplv2+ce.html) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/net.gredler/jdk9-png-writer-backport/badge.svg)](https://maven-badges.herokuapp.com/maven-central/net.gredler/jdk9-png-writer-backport)

It is a project based on https://github.com/gredler/jdk9-png-writer-backport
With the following differences:

* moved to a different package to avoid com.sun.* package restrictions
* switched to maven build system
* fixed junit tests
* upgraded junit to fix CVE

###Building

mvn clean install 
