Java-POM
========

A skeleton Maven project designed to be the parent project for Shawwware Java projects. That is, it collates common project settings in a single place for re-use and consistency across projects.

Common Specifications
---------------------

The parent POM specifies:

* a groupID of <code>au.com.shawware</code>
* the shawware organisation name and URL
* source encoding of UTF-8
* GPL licensing information
* Java 1.8 source and target files
* Generation of JavaDoc and Surefire reports for the site
* a test-scoped dependency on JUnit 4
* inclusion of GitHub's standard README.md in the built jar file
* inclusion of LICENSE.TXT in the built jar file
