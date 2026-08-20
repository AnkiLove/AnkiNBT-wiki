# Build Notes

## Environment

| Target | Java |
|---|---|
| Minecraft 1.21 through 1.21.11 | Java 21 |
| Minecraft 26.1 through 26.2 | Java 25 |

The Windows build environment in this repository uses:

- Java 21: `C:\Program Files\Zulu\zulu-21`
- Java 25: `C:\Program Files\Zulu\zulu-25`
- Proxy port: `127.0.0.1:7897`

## Common Command

```powershell
.\gradlew.bat clean build --no-daemon
```

For versioned builds, enter the matching directory first:

```powershell
cd versions\26.2
.\gradlew.bat clean build --no-daemon
```

## Output

Build artifacts are written to `build/libs` inside each version directory. NeoForge targets live under `versions`, Fabric targets under `fabric-versions`, while Fabric 1.21.1 uses the root `fabric` directory. Normal builds are not encrypted or obfuscated.
