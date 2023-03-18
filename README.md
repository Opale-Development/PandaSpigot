# PandaSpigot

Fork de PandaSpigot.

Patchs server [ici](./patches/).

[Discord](https://discord.gg/m6vCCX6Hvr) de PandaSpigot.

## API
API patchs [ici](./patches/api/).
<details>
<summary>Maven</summary>

```xml
<repositories>
    <repository>
        <id>hpfxd-repo</id>
        <url>https://repo.hpfxd.com/releases/</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>com.hpfxd.pandaspigot</groupId>
        <artifactId>pandaspigot-api</artifactId>
        <version>1.8.8-R0.1-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
</dependencies>
```
</details>

<details>
<summary>Gradle (kts)</summary>

```kotlin
repositories {
    mavenCentral()
    maven(url = "https://repo.hpfxd.com/releases/")
}

dependencies {
    compileOnly("com.hpfxd.pandaspigot:pandaspigot-api:1.8.8-R0.1-SNAPSHOT")
}
```
</details>
