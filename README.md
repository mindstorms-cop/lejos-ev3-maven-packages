# leJOS EV3 Maven packages

Creates maven packages from leJOS EV3 distribution packages

[![Circle CI](https://circleci.com/gh/Jimdo/mindstorms-cop/lejos-ev3-maven-packages/master.svg?style=shield)](https://circleci.com/gh/mindstorms-cop/lejos-ev3-maven-packages)

[![Release](https://img.shields.io/github/release/mindstorms-cop/lejos-ev3-maven-packages/master.svg?label=maven)](https://jitpack.io/#mindstorms-cop/lejos-ev3-maven-packages)

## Publish the packages to the Maven local repository 

```shell
./gradlew publishToMavenLocal
```

## Including the build packages as dependencies

We use [Jitpack](https://jitpack.io/#mindstorms-cop/lejos-ev3-maven-packages) for building maven packages. 

Use the following in your Gradle configuration to get the packages:

```
repositories {
    // ...
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.mindstorms-cop.lejos-ev3-maven-packages:ev3classes:20645ba'
}
```