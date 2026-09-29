# Ender Dragon Overhaul 26.2 Fabric

Based on the supplied 425-line specification.

### Explicit change
Phantom guardians for caged End Crystals are NOT implemented. Caged crystals remain breakable normally.

### Target
- Minecraft 26.2
- Fabric Loader 0.19.3
- Fabric API 0.158.0+26.2
- Fabric Loom 1.18-SNAPSHOT
- Java 25

### Build
Use `gradlew.bat build` on Windows or `./gradlew build` on Linux/macOS.
The production JAR is written to `build/libs/`.

This chat runtime does not have Java 25, Gradle, or the Minecraft/Fabric dependency cache, so an installable production JAR cannot be compiled here without falsely claiming it was tested.
