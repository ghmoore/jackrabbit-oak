Getting Started
---------------

To get started with Oak, build the latest sources with
Maven 3 and Java 7 (or higher) like this:

    mvn clean install

To enable all integration tests, including the JCR TCK, use:

    mvn clean install -PintegrationTesting

Run this with Ekstazi: mvn ekstazi:ekstazi -fn
Run this with STARTS: mvn starts:starts -fn

In my VM(Number 80), it ran Ekstazi for 27 min. However, in Starts, it only 
ran 7 min.
The author said " you can enable integration tests by default by setting the
OAK_INTEGRATION_TESTING` environment variable". However, I am still not sure
how to do this



