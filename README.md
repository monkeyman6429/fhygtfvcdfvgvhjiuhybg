# Pearl FX (Fabric, Minecraft 26.3)
Requires: Fabric Loader 0.19.5+, Fabric API for 26.3, Java 25.

Build the jar:
  A) GitHub: push this folder to a repo -> Actions tab -> "Build mod" -> download artifact `pearlfx-jar`.
  B) Locally: JDK 25 + Gradle 9.6, run `gradle build` -> build/libs/pearlfx-1.0.0.jar

If the build can't find Fabric API, set fabric_api_version in gradle.properties to the exact
26.3 version shown at https://fabricmc.net/develop

Swap the sound: replace src/main/resources/assets/pearlfx/sounds/pearl_warp.ogg (mono OGG Vorbis).
