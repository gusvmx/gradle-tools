# Jacoco plugin usage
You need 2 things:

* Import the plugin dependencies into your build.gradle
* Apply the jacoco.gradle file into your build.gradle

Finally you build your project using one of these, depending on your project.

## Single project
You can compile using
```
gradle clean build jacocoTestReport
```

## Multiproject
You can compile using
```
gradle clean build jacocoRootReport
```