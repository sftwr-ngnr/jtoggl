<h1>What is it about?</h1>

jtoggl wraps the [Toggl Track REST/JSON API](https://github.com/toggl/toggl_api_docs) for Java. 

This repository is a fork of [bbaumgartner/jtoggl](https://github.com/bbaumgartner/jtoggl) and contains minimal changes to keep it working.


<h1>Get it!</h1>

Please have a look at the fork [konikvranik/jtoggl](https://github.com/konikvranik/jtoggl) which might contain a more suitable solution for you.


<h2>I use Gradle</h2>

You can fetch jtoggl-api via [https://jitpack.io](https://jitpack.io):

Gradle example:

```gradle
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
 implementation 'com.github.sftwr-ngnr:jtoggl:master-SNAPSHOT'
}
```


<h2>I use Maven</h2>

You can fetch jtoggl-api via [https://jitpack.io](https://jitpack.io):

Maven example:

```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>

<dependency>
  <groupId>com.github.sftwr-ngnr</groupId>
  <artifactId>jtoggl</artifactId>
  <version>master-SNAPSHOT</version>
</dependency>
```

<h1>OK, but how do I use this</h1>

Have a look at our [tests](./jtoggl-api/src/test/java/ch/simas/jtoggl/) and [Toggl API documentation](https://github.com/toggl/toggl_api_docs). 
