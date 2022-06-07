# jacoco-offline-instrumentation

A sample project that demonstrates how to use Jacoco offline instrumentation for multimodule gradle project

To generate full coverage report run:
```
./gradlew clean report
```

Open HTML report to observe the results
```
build/reports/jacoco/index.html
```

# Alternative solution

There is [Offlins plugin](https://github.com/SurpSG/offlins-gradle-plugin)(Alternative JaCoCo Gradle plugin) that works in JaCoCo [offline instrumentation mode](https://www.jacoco.org/jacoco/trunk/doc/offline.html). 
The plugin in general do the same things that is shown in this example project but the plugin is well tested, easy using and supports Gradle versions 5.1-7.+
