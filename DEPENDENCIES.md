# Gradle Dependencies

The multiplatform dependency situation is somewhat problematic currently.

In more stable ecosystems (JVM, JS), publishing dependencies using maven repos will work across a wide range of gradle versions. By that I mean if I publish a library, assuming it isn't itself a gradle plugin, it's not super important what version of gradle I am using.

However, Kotlin/Native dependencies use a new feature of gradle called "metadata", which besides an arguably bad name choice (many things have "metadata"), is not yet at a stable version. That means version changes are not backwards compatible. It now matters what version of gradle I publish a library with.

The practical outcome of that is as follows. Pretty much all Jetbrains' multiplatform libraries are publishing for gradle 4.7. Gradle 4.7 has gradle metadata version 0.3. Android gradle plugin 3.3, which is arriving soon (you can use it in early access channels now), *requires* gradle 4.10. Gradle 4.10 uses metadata 0.4.

## TL;DR

You *cannot* use gradle 4.7 native dependencies in a 4.10 project, and vice versa.

