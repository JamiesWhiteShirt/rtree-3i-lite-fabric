# rtree-3i-lite-fabric
[![Maven Repository](https://img.shields.io/maven-metadata/v/https/maven.jamieswhiteshirt.com/libs-release/com/jamieswhiteshirt/rtree-3i-lite-fabric/maven-metadata.xml.svg)](https://maven.jamieswhiteshirt.com/libs-release/com/jamieswhiteshirt/rtree-3i-lite-fabric/)

Provides the [rtree-3i-lite](https://github.com/JamiesWhiteShirt/rtree-3i-lite) library as a [Fabric](https://fabricmc.net/) mod.

## Usage

rtree-3i-lite-fabric is designed to be included as a nested jar. To use this library in your workspace and to have it included as a nested jar, add the following to your `build.gradle`:

```groovy
repositories {
    maven {url "https://maven.jamieswhiteshirt.com/libs-release/"}
}

dependencies {
    include "com.jamieswhiteshirt:rtree-3i-lite-fabric:<VERSION>"
    modCompile "com.jamieswhiteshirt:rtree-3i-lite-fabric:<VERSION>"
}
```

NOTE: Requires fabric-loom >=0.2.1
