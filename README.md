# Material-UI-Swing
[![Maven Central](https://img.shields.io/maven-central/v/io.github.vincenzopalazzo/material-ui-swing?color=%237cc4f4&style=for-the-badge)](https://search.maven.org/search?q=g:%22io.github.vincenzopalazzo%22%20AND%20a:%22material-ui-swing%22)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/vincenzopalazzo/material-ui-swing/build?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/vincenzopalazzo/material-ui-swing?color=%237cc4f4&style=for-the-badge)
![GitHub All Releases](https://img.shields.io/github/downloads/vincenzopalazzo/material-ui-swing/total?color=%234caf50&style=for-the-badge)

<div align="center">
    <img src="https://raw.githubusercontent.com/material-ui-swing/material-ui-swing-icon/main/svg/java-red-icon.svg" />
</div>

## Description
![GitHub issues](https://img.shields.io/github/issues/vincenzopalazzo/material-ui-swing.svg?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/vincenzopalazzo/material-ui-swing.svg?style=for-the-badge)
[![Donation](https://img.shields.io/website/http/material-ui-swing.github.io/material-ui-swing-donations.svg?style=for-the-badge&up_color=yellow&up_message=Donation)](https://material-ui-swing.github.io/material-ui-swing-donations)
[![Gitter chat](https://img.shields.io/gitter/room/vincenzopalazzo/material-ui-swing.svg?style=for-the-badge)](https://gitter.im/material-ui-swing/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

A modern, Material Design UI for Java Swing

# Overview

- [Introduction](https://github.com/vincenzopalazzo/material-ui-swing/wiki/Introduction)
- [Component Supported](https://github.com/vincenzopalazzo/material-ui-swing/wiki/Component-Supported)
- [Material Theming](https://vincenzopalazzo.medium.com/swing-theming-basic-introduction-to-materialtheme-system-150395392a7)
- [Develop a new Theme](https://github.com/vincenzopalazzo/material-ui-swing/wiki)
- [Screenshots](https://github.com/vincenzopalazzo/material-ui-swing/wiki/Screenshots)
- [How Contribute](/docs/dev/MAINTAINERS.md)
- [Built with](https://github.com/vincenzopalazzo/material-ui-swing/wiki/Built-with)
- [Community](https://gitter.im/material-ui-swing/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
- [License](https://github.com/vincenzopalazzo/material-ui-swing/tree/development#license)

## Repository

 _Maven_
 ```xml
<dependency>
  <groupId>io.github.vincenzopalazzo</groupId>
  <artifactId>material-ui-swing</artifactId>
  <version>1.1.2</version>
</dependency>
 ```

 _Gradle (Groovy)_
```groovy
implementation 'io.github.vincenzopalazzo:material-ui-swing:1.1.2'
```

 _Gradle (Kotlin DSL)_
```kotlin
implementation("io.github.vincenzopalazzo:material-ui-swing:1.1.2")
```

Others version [here](https://search.maven.org/artifact/io.github.vincenzopalazzo/material-ui-swing)

### Snapshot version

Each master version has a SNAPSHOT version that is the official version `x.x.x + 1`, so for example for the version `v1.1.2-rc1`
the version on if exist a new version of the master branch is `v1.1.2-rc2-SNAPSHOT`

An example of gradle configuration is reported below

_Gradle (Kotlin DSL)_
```kotlin
configurations.all {
    resolutionStrategy.cacheDynamicVersionsFor(0, "seconds")
    resolutionStrategy.cacheChangingModulesFor(0, "seconds")
}

repositories {
    ... other suff
    maven("https://oss.sonatype.org/content/repositories/snapshots")
}

dependencies {
    ... other stuff
    implementation("io.github.vincenzopalazzo:material-ui-swing:1.1.3-rc1-SNAPSHOT")
}

```

## Code Style
> We live in a world where robots can drive a car, so we shouldn't just write code, we should write elegant code.

This repository use [google-java-format](https://github.com/sherter/google-java-format-gradle-plugin) to maintains the code of the repository elegant, so
before submit the code check the Java format with the following command on the root of the directory

```bash
./gradlew verifyGoogleJavaFormat
```

If any error are reported please run the following command to fix them

```bash
./gradlew googleJavaFormat
```

P.S.: The gradle plugin works with all the JDK versions >= 9 (or better with java byte code version compatible with the version  55.0)

For more details about the JDK support see [this issue](https://github.com/sherter/google-java-format-gradle-plugin/issues/58) 
and to know more about the Google Java code Style see [this reference](https://google.github.io/styleguide/javaguide.html)

## Build with Material-UI-Swing
_**List of projects with Material-UI-Swing theme**_
- [Krayon for SBGN](https://github.com/wiese42/krayon4sbgn)
- [JMars 5](https://JMars.mars.asu.edu): Used by NASA and United Arab Emirates (UAE) for the last Mars missions.

Contact us if you use this look and feel, so we can add your project to the list 🙂

### _Donors_
- [lilili87222](https://github.com/lilili87222)
- Arizona State University
- [zanderson9](https://github.com/zanderson9)

You can support the project on the [Material-UI-Swing donation site](https://material-ui-swing.github.io/material-ui-swing-donations/)

## Supporters

<div align="center">
  <img src="docs/jetbrains-logos/jetbrains-variant-4.png" width="325" height="180"/>
</div>

[JetBrains' support](https://www.jetbrains.com/?from=material-ui-swing)

<div align="center">
  <img src="https://www.yourkit.com/images/yklogo.png"/>
</div>
The YourKit is used also by Google, Microsoft, PayPal, ecc.

- **YourKit**: it supports open source projects with innovative and intelligent tools
for monitoring and profiling Java and .NET applications.
YourKit is the creator of <a href="https://www.yourkit.com/java/profiler/">YourKit Java Profiler</a>,
<a href="https://www.yourkit.com/.net/profiler/">YourKit .NET Profiler</a>,
and <a href="https://www.yourkit.com/youmonitor/">YourKit YouMonitor</a>.

## License

<div align="center">
  <img src="https://opensource.org/files/osi_keyhole_300X300_90ppi_0.png" width="150" height="150"/>
</div>

Copyright (c) 2018 atharva washimkar.

Copyright (c) 2019-2020 atharva washimkar, Vincenzo Palazzo vincenzopalazzodev@gmail.com

Copyright (c) 2021 Vincenzo Palazzo vincenzopalazzodev@gmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, 
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, 
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE 
OR OTHER DEALINGS IN THE SOFTWARE.

