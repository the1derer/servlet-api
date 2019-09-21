## 1. Unannotated Code is present at master branch.


## 2. To use checker-framework  use following steps(Annotated code present at 'typecheck-nullness' branch)

Made a pull request to master to indicate file changes(https://github.com/the1derer/servlet-api/pull/1/files)

(i) To checkout annotated branch
     ``git checkout typecheck-nullness``

(ii) To Check initial Errors given by Checker-Framework
    a. ``git checkout 16ffe34c705b55248ee8611a38f9a52fbf5ed652``


Java Servlet API
================

Building
--------

Prerequisites:

* JDK8+
* Maven 3.0.3+

Run the build: 

`mvn install`

The build runs copyright check and generates the jar, sources-jar and javadoc-jar by default.

Checking findbugs
-----------------

`mvn -DskipTests -Dfindbugs.threshold=Low findbugs:findbugs`

