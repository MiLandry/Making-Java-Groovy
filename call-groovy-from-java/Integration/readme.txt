Source code for Chapter 3, Code-level Integration,
 of Making Java Groovy by Ken Kousen, http://manning.com/kousen.

The source includes a Gradle build file that will compile
all the code and run all the tests, ultimately producing HTML
output in build/reports/test/index.html.

If you have gradle installed, run
> gradle build

otherwise, the wrapper will download and install gradle for you:

> gradlew build
