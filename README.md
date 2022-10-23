# minecraft-builder

Upstream: [rmheuer/McAssetExtractor](https://github.com/rmheuer/McAssetExtractor)

This is a fork of the original McAssetExtractor. It's repurposed to be a part of [Algorythm](https://github.com/Subilan/Algorythm) for downloading vanilla Minecraft game assets and other files from source provided by Mojang *or* its mirror, BMCLAPI.

## Build

Different from the upstream, this project uses Gradle. To create a runnable build, just run

```bash
gradle clean shadow # Include dependencies to make a runnable jar file.
```

then the `jar` will appear in `build/libs` with the suffix `-all`.

## License

MIT