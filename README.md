# leJOS EV3 Maven packages

Creates Maven packages from leJOS EV3 distribution packages

[![Circle CI](https://circleci.com/gh/mindstorms-cop/lejos-ev3-maven-packages/tree/master.svg?style=shield)](https://circleci.com/gh/mindstorms-cop/lejos-ev3-maven-packages/tree/master)

## Publish the packages to the Maven local repository 

```shell
./gradlew publishToMavenLocal
```

## Including the built packages as dependencies

We use [Jitpack](https://jitpack.io/#mindstorms-cop/lejos-ev3-maven-packages) for building Maven packages.

Use the following in your Gradle configuration to get the packages:

```
repositories {
    // ...
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.mindstorms-cop.lejos-ev3-maven-packages:ev3classes:0.9.0-beta'
}
```
