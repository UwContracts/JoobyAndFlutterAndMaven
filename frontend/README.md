### Directories, and files:

1: lib/ a small Flutter app

In here a Flutter app that takes the text/plain output from http://localhost:8080/ and places it in the center of the page.

2: test/ a Flutter widget test that confirms that the rectangle could display some text in the center

3: flutterDriver/ a FlutterDriver test that brings up the app (that gets data from http://localhost:8080/) and confirms it is in the page, before bring it all down.

4: pom.xml (Maven pom for a non-Java project):

* Should be able to run widget tests using mvn command (see pom.xml)

* Should be able to run flutter driver tests using mvn command (see pom.xml) with a Jooby server hosting the "hello world" app (that was brought up before the flutter driver tests and torn down afterward).
