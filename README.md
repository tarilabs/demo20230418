This is a *hack* to have Gradle orchestrate the Kogito maven plugin codegen, via a Maven wrapper.
This is NOT SUPPORTED solution.
Limitations apply and YMMV: for instance: 
 - LIMITATIONS: must keep dependencies aligned between gradle and maven pom

```
./gradlew clean build --info
```

or

```
./gradlew bootRun --info
```

