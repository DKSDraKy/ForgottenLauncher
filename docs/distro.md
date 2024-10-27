# Distribution Index

You can use [Nebula](https://github.com/dscalzi/Nebula) to automate the generation of a distribution index.

The most up to date and accurate descriptions of the distribution spec can be viewed in [helios-distribution-types](https://github.com/dscalzi/helios-distribution-types).

The distribution index is written in JSON. The general format of the index is as posted below.

```json
{
  "version": "1.0.0",
  "rss": "<LINK TO RSS FEED>",
  "discord": {
    "clientId": "<FILL IN OR REMOVE DISCORD OBJECT>",
    "smallImageText": "<FILL IN OR REMOVE DISCORD OBJECT>",
    "smallImageKey": "<FILL IN OR REMOVE DISCORD OBJECT>"
  },
  "servers": [
    {
      "id": "DEDsafio-1.16.5",
      "name": "DEDsafio (Minecraft 1.16.5)",
      "description": "DEDsafio Running Minecraft 1.16.5 (Forge v36.2.34)",
      "icon": https://cdn.discordapp.com/attachments/847293692209004585/1300238270063579188/LoadingSeal.png?ex=67201cc0&is=671ecb40&hm=7c5457d129ba0a661594d296d6a3d8029bc481c61c094e66947081dd334d04d6&,
      "version": "1.0.0",
      "address": "23.230.3.50:25570",
      "minecraftVersion": "1.16.5",
      "discord": {
        "shortId": "<FILL IN OR REMOVE DISCORD OBJECT>",
        "largeImageText": "<FILL IN OR REMOVE DISCORD OBJECT>",
        "largeImageKey": "<FILL IN OR REMOVE DISCORD OBJECT>"
      },
      "mainServer": true,
      "autoconnect": false,
      "modules": [
        {
          "id": "net.minecraftforge:forge:1.16.5-36.2.34",
          "name": "Minecraft Forge (base jar)",
          "type": "ForgeHosted",
          "classpath": true,
          "artifact": {
            "size": 212608,
            "MD5": "e8de93b1e25fcb60d847b2565d35369c",
            "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/forge/1.16.5-36.2.34/forge-1.16.5-36.2.34.jar"
          },
          "subModules": [
            {
              "id": "1.16.5-36.2.34",
              "name": "Minecraft Forge (version.json)",
              "type": "VersionManifest",
              "artifact": {
                "size": 13577,
                "MD5": "9cc72898a14a7d162d6813443761d30a",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/versions/1.16.5-forge-36.2.34/1.16.5-forge-36.2.34.json"
              }
            },
            {
              "id": "net.minecraftforge:forge:1.16.5-36.2.34:universal",
              "name": "Minecraft Forge (universal jar)",
              "type": "Library",
              "classpath": true,
              "artifact": {
                "size": 2773337,
                "MD5": "521b6d8bfa23e4e00da77f4a07f01f8f",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/forge/1.16.5-36.2.34/forge-1.16.5-36.2.34-universal.jar"
              },
              "subModules": []
            },
            {
              "id": "net.minecraftforge:forge:1.16.5-36.2.34:client",
              "name": "Minecraft Forge (client jar)",
              "type": "Library",
              "classpath": true,
              "artifact": {
                "size": 4214137,
                "MD5": "8d8990d72f63d109f68fedf74182a3ea",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/forge/1.16.5-36.2.34/forge-1.16.5-36.2.34-client.jar"
              },
              "subModules": []
            },
            {
              "id": "net.minecraft:client:1.16.5-20210115.111550:srg",
              "name": "Minecraft Forge (client srg)",
              "type": "Library",
              "classpath": true,
              "artifact": {
                "size": 11352644,
                "MD5": "b39b7c78820054901cdaf61b8e6f7433",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraft/client/1.16.5-20210115.111550/client-1.16.5-20210115.111550-srg.jar"
              },
              "subModules": []
            },
            {
              "id": "net.minecraft:client:1.16.5-20210115.111550:slim",
              "name": "Minecraft Forge (client slim)",
              "type": "Library",
              "classpath": true,
              "artifact": {
                "size": 9118806,
                "MD5": "df78297c0b6526e16f2bb7a685fd6b96",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraft/client/1.16.5-20210115.111550/client-1.16.5-20210115.111550-slim.jar"
              },
              "subModules": []
            },
            {
              "id": "net.minecraft:client:1.16.5-20210115.111550:extra",
              "name": "Minecraft Forge (client extra)",
              "type": "Library",
              "classpath": true,
              "artifact": {
                "size": 8428369,
                "MD5": "dbed747390f81e10cee40500b726431a",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraft/client/1.16.5-20210115.111550/client-1.16.5-20210115.111550-extra.jar"
              },
              "subModules": []
            },
            {
              "id": "org.ow2.asm:asm:9.1",
              "name": "Minecraft Forge (asm)",
              "type": "Library",
              "artifact": {
                "size": 121790,
                "MD5": "54b9f5d15e4877a4ea4cf9ec48e07afa",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/ow2/asm/asm/9.1/asm-9.1.jar"
              }
            },
            {
              "id": "org.ow2.asm:asm-commons:9.1",
              "name": "Minecraft Forge (asm-commons)",
              "type": "Library",
              "artifact": {
                "size": 72641,
                "MD5": "81cc6b8f5ce8f2767d39fbd4b6c37a6a",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/ow2/asm/asm-commons/9.1/asm-commons-9.1.jar"
              }
            },
            {
              "id": "org.ow2.asm:asm-tree:9.1",
              "name": "Minecraft Forge (asm-tree)",
              "type": "Library",
              "artifact": {
                "size": 52662,
                "MD5": "c2536add9ebcfa8066fcfb0dbe865879",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/ow2/asm/asm-tree/9.1/asm-tree-9.1.jar"
              }
            },
            {
              "id": "org.ow2.asm:asm-util:9.1",
              "name": "Minecraft Forge (asm-util)",
              "type": "Library",
              "artifact": {
                "size": 84679,
                "MD5": "2f1a28f6b0f3e02b17d38a0f657a1527",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/ow2/asm/asm-util/9.1/asm-util-9.1.jar"
              }
            },
            {
              "id": "org.ow2.asm:asm-analysis:9.1",
              "name": "Minecraft Forge (asm-analysis)",
              "type": "Library",
              "artifact": {
                "size": 34257,
                "MD5": "f0e82941173b6049c03e8214ace70ecd",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/ow2/asm/asm-analysis/9.1/asm-analysis-9.1.jar"
              }
            },
            {
              "id": "cpw.mods:modlauncher:8.1.3",
              "name": "Minecraft Forge (modlauncher)",
              "type": "Library",
              "artifact": {
                "size": 126747,
                "MD5": "b6ba74224a6a68e6fb3e9cf3d72b9344",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/cpw/mods/modlauncher/8.1.3/modlauncher-8.1.3.jar"
              }
            },
            {
              "id": "cpw.mods:grossjava9hacks:1.3.3",
              "name": "Minecraft Forge (grossjava9hacks)",
              "type": "Library",
              "artifact": {
                "size": 2113,
                "MD5": "d19b487241008d8e6111137a289ea1d7",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/cpw/mods/grossjava9hacks/1.3.3/grossjava9hacks-1.3.3.jar"
              }
            },
            {
              "id": "net.minecraftforge:accesstransformers:3.0.1",
              "name": "Minecraft Forge (accesstransformers)",
              "type": "Library",
              "artifact": {
                "size": 76586,
                "MD5": "ada4c365c3d0de73c05a94010432b547",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/accesstransformers/3.0.1/accesstransformers-3.0.1.jar"
              }
            },
            {
              "id": "org.antlr:antlr4-runtime:4.9.1",
              "name": "Minecraft Forge (antlr4-runtime)",
              "type": "Library",
              "artifact": {
                "size": 337868,
                "MD5": "0dcc4b860d5d8d2852ab94d58c56ca2d",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/antlr/antlr4-runtime/4.9.1/antlr4-runtime-4.9.1.jar"
              }
            },
            {
              "id": "net.minecraftforge:eventbus:4.0.0",
              "name": "Minecraft Forge (eventbus)",
              "type": "Library",
              "artifact": {
                "size": 42873,
                "MD5": "84c4758e6139b70146104be5bb1300b5",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/eventbus/4.0.0/eventbus-4.0.0.jar"
              }
            },
            {
              "id": "net.minecraftforge:forgespi:3.2.0",
              "name": "Minecraft Forge (forgespi)",
              "type": "Library",
              "artifact": {
                "size": 20172,
                "MD5": "8f1f6942d17d88d704324e8000666a1a",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/forgespi/3.2.0/forgespi-3.2.0.jar"
              }
            },
            {
              "id": "net.minecraftforge:coremods:4.0.6",
              "name": "Minecraft Forge (coremods)",
              "type": "Library",
              "artifact": {
                "size": 25453,
                "MD5": "e56551f2586d3ff08beb24f5ea44a7d3",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/coremods/4.0.6/coremods-4.0.6.jar"
              }
            },
            {
              "id": "net.minecraftforge:unsafe:0.2.0",
              "name": "Minecraft Forge (unsafe)",
              "type": "Library",
              "artifact": {
                "size": 2834,
                "MD5": "2d1016ebe4c1a63dd50a59d26bd12db1",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/unsafe/0.2.0/unsafe-0.2.0.jar"
              }
            },
            {
              "id": "com.electronwill.night-config:core:3.6.3",
              "name": "Minecraft Forge (core)",
              "type": "Library",
              "artifact": {
                "size": 199091,
                "MD5": "093b0ca357d3f8b922170b8d7f43948c",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/com/electronwill/night-config/core/3.6.3/core-3.6.3.jar"
              }
            },
            {
              "id": "com.electronwill.night-config:toml:3.6.3",
              "name": "Minecraft Forge (toml)",
              "type": "Library",
              "artifact": {
                "size": 31288,
                "MD5": "615b8e62371c536f876764591990118d",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/com/electronwill/night-config/toml/3.6.3/toml-3.6.3.jar"
              }
            },
            {
              "id": "org.jline:jline:3.12.1",
              "name": "Minecraft Forge (jline)",
              "type": "Library",
              "artifact": {
                "size": 732926,
                "MD5": "ffd8c9d6eb8a8456ef505c8ef9fc777d",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/jline/jline/3.12.1/jline-3.12.1.jar"
              }
            },
            {
              "id": "org.apache.maven:maven-artifact:3.6.3",
              "name": "Minecraft Forge (maven-artifact)",
              "type": "Library",
              "artifact": {
                "size": 57824,
                "MD5": "b83c1943a0783f3f81d4cd4c83c363e1",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/apache/maven/maven-artifact/3.6.3/maven-artifact-3.6.3.jar"
              }
            },
            {
              "id": "net.jodah:typetools:0.8.3",
              "name": "Minecraft Forge (typetools)",
              "type": "Library",
              "artifact": {
                "size": 15425,
                "MD5": "ee4596e1413cc1a5e080c971d6064753",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/jodah/typetools/0.8.3/typetools-0.8.3.jar"
              }
            },
            {
              "id": "org.apache.logging.log4j:log4j-api:2.15.0",
              "name": "Minecraft Forge (log4j-api)",
              "type": "Library",
              "artifact": {
                "size": 301804,
                "MD5": "a9ccfa7e3382dd2b9e0647a43d8286d7",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/apache/logging/log4j/log4j-api/2.15.0/log4j-api-2.15.0.jar"
              }
            },
            {
              "id": "org.apache.logging.log4j:log4j-core:2.15.0",
              "name": "Minecraft Forge (log4j-core)",
              "type": "Library",
              "artifact": {
                "size": 1789769,
                "MD5": "81e0433ae00602c0e4d00424d213b0ab",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/apache/logging/log4j/log4j-core/2.15.0/log4j-core-2.15.0.jar"
              }
            },
            {
              "id": "org.apache.logging.log4j:log4j-slf4j18-impl:2.15.0",
              "name": "Minecraft Forge (log4j-slf4j18-impl)",
              "type": "Library",
              "artifact": {
                "size": 21223,
                "MD5": "196442f1bdde4dbb0f576eed616e21b0",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/apache/logging/log4j/log4j-slf4j18-impl/2.15.0/log4j-slf4j18-impl-2.15.0.jar"
              }
            },
            {
              "id": "net.minecrell:terminalconsoleappender:1.2.0",
              "name": "Minecraft Forge (terminalconsoleappender)",
              "type": "Library",
              "artifact": {
                "size": 15977,
                "MD5": "679363fa893293791e55a21f81342f87",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecrell/terminalconsoleappender/1.2.0/terminalconsoleappender-1.2.0.jar"
              }
            },
            {
              "id": "net.sf.jopt-simple:jopt-simple:5.0.4",
              "name": "Minecraft Forge (jopt-simple)",
              "type": "Library",
              "artifact": {
                "size": 78146,
                "MD5": "eb0d9dffe9b0eddead68fe678be76c49",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/sf/jopt-simple/jopt-simple/5.0.4/jopt-simple-5.0.4.jar"
              }
            },
            {
              "id": "org.spongepowered:mixin:0.8.4",
              "name": "Minecraft Forge (mixin)",
              "type": "Library",
              "artifact": {
                "size": 1069391,
                "MD5": "25fbb8ff965e88cc2252c99be0cf5cbb",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/org/spongepowered/mixin/0.8.4/mixin-0.8.4.jar"
              }
            },
            {
              "id": "net.minecraftforge:nashorn-core-compat:15.1.1.1",
              "name": "Minecraft Forge (nashorn-core-compat)",
              "type": "Library",
              "artifact": {
                "size": 2194057,
                "MD5": "ae37ed8407982eefc9f85fdb1c95a3a0",
                "url": "http://dedsafiotesting.rf.gd/nebula/repo/lib/net/minecraftforge/nashorn-core-compat/15.1.1.1/nashorn-core-compat-15.1.1.1.jar"
              }
            }
          ]
        },
        {
          "id": "net.optifine:optifine:1.16.5_HD_U_G7@jar",
          "name": "OptiFine",
          "type": "ForgeMod",
          "artifact": {
            "size": 5924305,
            "url": "http://dedsafiotesting.rf.gd/nebula/servers/DEDsafio-1.16.5/forgemods/required/OptiFine_1.16.5_HD_U_G7.jar",
            "MD5": "9d323219bdebf4e22a1d90f99f839cc0"
          }
        },
        {
          "id": "su.plo.voice:plasmo_voice:1.2.19@jar",
          "name": "Plasmo Voice",
          "type": "ForgeMod",
          "artifact": {
            "size": 4974313,
            "url": "http://dedsafiotesting.rf.gd/nebula/servers/DEDsafio-1.16.5/forgemods/required/plasmovoice-forge-1.16-1.2.19.jar",
            "MD5": "e111cb48088fafd24c524ccd95e05ddf"
          }
        },
        {
          "id": "NOOBSTERS_5.json",
          "name": "NOOBSTERS_5.json",
          "type": "File",
          "artifact": {
            "size": 294206,
            "url": "http://dedsafiotesting.rf.gd/nebula/servers/DEDsafio-1.16.5/files/resourcepacks/DEDSAFIO_IDIOMAS_V1/assets/minecraft/lang/NOOBSTERS_5.json",
            "MD5": "ed4f80f6e1ae8c465fdc8ca4ebbb0bca",
            "path": "resourcepacks/DEDSAFIO_IDIOMAS_V1/assets/minecraft/lang/NOOBSTERS_5.json"
          }
        },
        {
          "id": "pack.mcmeta",
          "name": "pack.mcmeta",
          "type": "File",
          "artifact": {
            "size": 240,
            "url": "http://dedsafiotesting.rf.gd/nebula/servers/DEDsafio-1.16.5/files/resourcepacks/DEDSAFIO_IDIOMAS_V1/pack.mcmeta",
            "MD5": "84da124defd49d0d83c03daa41c16363",
            "path": "resourcepacks/DEDSAFIO_IDIOMAS_V1/pack.mcmeta"
          }
        }
      ]
    }
  ]
}
```

## Distro Index Object

#### Example
```JSON
{
    "version": "1.0.0",
    "discord": {
        "clientId": "12334567890123456789",
        "smallImageText": "WesterosCraft",
        "smallImageKey": "seal-circle"
    },
    "rss": "https://westeroscraft.com/articles/index.rss",
    "servers": []
}
```

### `DistroIndex.version: string/semver`

The version of the index format. Will be used in the future to gracefully push updates.

### `DistroIndex.discord: object`

Global settings for [Discord Rich Presence](https://discordapp.com/developers/docs/rich-presence/how-to).

**Properties**

* `discord.clientId: string` - Client ID for th Application registered with Discord.
* `discord.smallImageText: string` - Tootltip for the `smallImageKey`.
* `discord.smallImageKey: string` - Name of the uploaded image for the small profile artwork.


### `DistroIndex.rss: string/url`

A URL to a RSS feed. Used for loading news.

---

## Server Object

#### Example
```JSON
{
    "id": "Example_Server",
    "name": "WesterosCraft Example Client",
    "description": "Example WesterosCraft server. Connect for fun!",
    "icon": "http://mc.westeroscraft.com/WesterosCraftLauncher/files/example_icon.png",
    "version": "0.0.1",
    "address": "mc.westeroscraft.com:1337",
    "minecraftVersion": "1.11.2",
    "discord": {
        "shortId": "Example",
        "largeImageText": "WesterosCraft Example Server",
        "largeImageKey": "server-example"
    },
    "mainServer": true,
    "autoconnect": true,
    "modules": []
}
```

### `Server.id: string`

The ID of the server. The launcher saves mod configurations and selected servers by ID. If the ID changes, all data related to the old ID **will be wiped**.

### `Server.name: string`

The name of the server. This is what users see on the UI.

### `Server.description: string`

A brief description of the server. Displayed on the UI to provide users more information.

### `Server.icon: string/url`

A URL to the server's icon. Will be displayed on the UI.

### `Server.version: string/semver`

The version of the server configuration.

### `Server.address: string/url`

The server's IP address.

### `Server.minecraftVersion: string`

The version of minecraft that the server is running.

### `Server.discord: object`

Server specific settings used for [Discord Rich Presence](https://discordapp.com/developers/docs/rich-presence/how-to).

**Properties**

* `discord.shortId: string` - Short ID for the server. Displayed on the second status line as `Server: shortId`
* `discord.largeImageText: string` - Ttooltip for the `largeImageKey`.
* `discord.largeImageKey: string` - Name of the uploaded image for the large profile artwork.

### `Server.mainServer: boolean`

Only one server in the array should have the `mainServer` property enabled. This will tell the launcher that this is the default server to select if either the previously selected server is invalid, or there is no previously selected server. If this field is not defined by any server (avoid this), the first server will be selected as the default. If multiple servers have `mainServer` enabled, the first one the launcher finds will be the effective value. Servers which are not the default may omit this property rather than explicitly setting it to false.

### `Server.autoconnect: boolean`

Whether or not the server can be autoconnected to. If false, the server will not be autoconnected to even when the user has the autoconnect setting enabled.

### `Server.javaOptions: JavaOptions`

**OPTIONAL**

Sever-specific Java options. If not provided, defaults are used by the client.

### `Server.modules: Module[]`

An array of module objects.

---

## JavaOptions Object

Server-specific Java options.

#### Example
```JSON
{
    "supported": ">=17",
    "suggestedMajor": 17,
    "platformOptions": [
      {
        "platform": "darwin",
        "architecture": "arm64",
        "distribution": "CORRETTO"
      }
    ],
    "ram": {
      "recommended": 3072,
      "minimum": 2048
    }
}
```

### `JavaOptions.platformOptions: JavaPlatformOptions[]`

**OPTIONAL**

Platform-specific java rules for this server configuration. Validation rules will be delegated to the client for any undefined properties. Java validation can be configured for specific platforms and architectures. The most specific ruleset will be applied.

Maxtrix Precedence (Highest - Lowest)
  - Current platform, current architecture (ex. win32 x64).
  - Current platform, any architecture (ex. win32).
  - Java Options base properties.
  - Client logic (default logic in the client).

Properties:

  - `platformOptions.platform: string` - The platform that this validation matrix applies to.
  - `platformOptions.architecture: string` - Optional. The architecture that this validation matrix applies to. If omitted, applies to all architectures.
  - `platformOptions.distribution: string` - Optional. See `JavaOptions.distribution`.
  - `platformOptions.supported: string` - Optional. See `JavaOptions.supported`.
  - `platformOptions.suggestedMajor: number` - Optional. See `JavaOptions.suggestedMajor`.

### `JavaOptions.ram: object`

**OPTIONAL**

This allows you to require a minimum and recommended amount of RAM per server instance. The minimum is the smallest value the user can select in the settings slider. The recommended value will be the default value selected for that server. These values are specified in megabytes and must be an interval of 512. This allows configuration in intervals of half gigabytes. In the above example, the recommended ram value is 3 GB (3072 MB) and the minimum is 2 GB (2048 MB).

  - `ram.recommended: number` - The recommended amount of RAM in megabytes. Must be an interval of 512.
  - `ram.minimum: number` - The absolute minimum amount of RAM in megabytes. Must be an interval of 512.

### `JavaOptions.distribution: string`

**OPTIONAL**

Preferred JDK distribution to download if no applicable installation could be found. If omitted, the client will decide (decision may be platform-specific).

### `JavaOptions.supported: string`

**OPTIONAL**

A semver range of supported JDK versions.

Java version syntax is platform dependent.

JDK 8 and prior
```
1.{major}.{minor}_{patch}-b{build}
Ex. 1.8.0_152-b16
```

JDK 9+
```
{major}.{minor}.{patch}+{build}
Ex. 11.0.12+7
```

For processing, all versions will be translated into a semver compliant string. JDK 9+ is already semver. For versions 8 and below, `1.{major}.{minor}_{patch}-b{build}` will be translated to `{major}.{minor}.{patch}+{build}`.

If specified, you must also specify suggestedMajor.

If omitted, the client will decide based on the game version.

### `JavaOptions.suggestedMajor: number`

**OPTIONAL**

The suggested major Java version. The suggested major should comply with the version range specified by supported, if defined. This will be used in messages displayed to the end user, and to automatically fetch a Java version.

NOTE If supported is specified, suggestedMajor must be set. The launcher's default value may not comply with your custom major supported range.

Common use case:
  - supported: '>=17.x'
  - suggestedMajor: 17

More involved:
  - supported: '>=16 <20'
  - suggestedMajor: 17

Given a wider support range, it becomes necessary to specify which major version in the range is the suggested.

---

## Module Object

A module is a generic representation of a file required to run the minecraft client.

#### Example
```JSON
{
    "id": "com.example:artifact:1.0.0@jar.pack.xz",
    "name": "Artifact 1.0.0",
    "type": "Library",
    "artifact": {
        "size": 4231234,
        "MD5": "7f30eefe5c51e1ae0939dab2051db75f",
        "url": "http://files.site.com/maven/com/example/artifact/1.0.0/artifact-1.0.0.jar.pack.xz"
    },
    "subModules": [
        {
            "id": "examplefile",
            "name": "Example File",
            "type": "File",
            "artifact": {
                "size": 23423,
                "MD5": "169a5e6cf30c2cc8649755cdc5d7bad7",
                "path": "examplefile.txt",
                "url": "http://files.site.com/examplefile.txt"
            }
        }
    ]
}
```

The parent module will be stored maven style, it's destination path will be resolved by its id. The sub module has a declared `path`, so that value will be used.

### `Module.id: string`

The ID of the module. All modules that are not of type `File` **MUST** use a maven identifier. Version information and other metadata is pulled from the identifier. Modules which are stored maven style use the identifier to resolve the destination path. If the `extension` is not provided, it defaults to `jar`.

**Template**

`my.group:arifact:version@extension`

`my/group/artifact/version/artifact-version.extension`

**Example**

`net.minecraft:launchwrapper:1.12` OR `net.minecraft:launchwrapper:1.12@jar`

`net/minecraft/launchwrapper/1.12/launchwrapper-1.12.jar`

If the module's artifact does not declare the `path` property, its path will be resolved from the ID.

### `Module.name: string`

The name of the module. Used on the UI.

### `Module.type: string`

The type of the module.

### `Module.classpath: boolean`

**OPTIONAL**

If the module is of type `Library`, whether the library should be added to the classpath. Defaults to true.

### `Module.required: Required`

**OPTIONAL**

Defines whether or not the module is required. If omitted, then the module will be required. 

Only applicable for modules of type:
* `ForgeMod`
* `LiteMod`
* `LiteLoader`


### `Module.artifact: Artifact`

The download artifact for the module.

### `Module.subModules: Module[]`

**OPTIONAL**

An array of sub modules declared by this module. Typically, files which require other files are declared as submodules. A quick example would be a mod, and the configuration file for that mod. Submodules can also declare submodules of their own. The file is parsed recursively, so there is no limit.


## Artifact Object

The format of the module's artifact depends on several things. The most important factor is where the file will be stored. If you are providing a simple file to be placed in the root directory of the client files, you may decided to format the module as the `examplefile` module declared above. This module provides a `path` option, allowing you to directly set where the file will be saved to. Only the `path` will affect the final downloaded file.

Other times, you may want to store the files maven-style, such as with libraries and mods. In this case you must declare the module as the example artifact above. The module `id` will be used to resolve the final path, effectively replacing the `path` property. It must be provided in maven format. More information on this is provided in the documentation for the `id` property.

The resolved/provided paths are appended to a base path depending on the module's declared type.

| Type | Path |
| ---- | ---- |
| `ForgeHosted` | ({`commonDirectory`}/libraries/{`path` OR resolved}) |
| `Fabric` | ({`commonDirectory`}/libraries/{`path` OR resolved}) |
| `LiteLoader` | ({`commonDirectory`}/libraries/{`path` OR resolved}) |
| `Library` | ({`commonDirectory`}/libraries/{`path` OR resolved}) |
| `ForgeMod` | ({`commonDirectory`}/modstore/{`path` OR resolved}) |
| `LiteMod` | ({`commonDirectory`}/modstore/{`path` OR resolved}) |
| `FabricMod` | ({`commonDirectory`}/mods/fabric/{`path` OR resolved}) |
| `File` | ({`instanceDirectory`}/{`Server.id`}/{`path` OR resolved}) |

The `commonDirectory` and `instanceDirectory` values are stored in the launcher's config.json.

### `Artifact.size: number`

The size of the artifact.

### `Artifact.MD5: string`

The MD5 hash of the artifact. This will be used to validate local artifacts.

### `Artifact.path: string`

**OPTIONAL**

A relative path to where the file will be saved. This is appended to the base path for the module's declared type.

If this is not specified, the path will be resolved based on the module's ID.

### `Artifact.url: string/url`

The artifact's download url.

## Required Object

### `Required.value: boolean`

**OPTIONAL**

If the module is required. Defaults to true if this property is omited. 

### `Required.def: boolean`

**OPTIONAL**

If the module is enabled by default. Has no effect unless `Required.value` is false. Defaults to true if this property is omited. 

---

## Module Types

### ForgeHosted

The module type `ForgeHosted` represents forge itself. Currently, the launcher only supports modded servers, as vanilla servers can be connected to via the mojang launcher. The `Hosted` part is key, this means that the forge module must declare its required libraries as submodules.

Ex.

```json
{
    "id": "net.minecraftforge:forge:1.11.2-13.20.1.2429",
    "name": "Minecraft Forge 1.11.2-13.20.1.2429",
    "type": "ForgeHosted",
    "artifact": {
        "size": 4450992,
        "MD5": "3fcc9b0104f0261397d3cc897e55a1c5",
        "url": "http://files.minecraftforge.net/maven/net/minecraftforge/forge/1.11.2-13.20.1.2429/forge-1.11.2-13.20.1.2429-universal.jar"
    },
    "subModules": [
        {
            "id": "net.minecraft:launchwrapper:1.12",
            "name": "Mojang (LaunchWrapper)",
            "type": "Library",
            "artifact": {
                "size": 32999,
                "MD5": "934b2d91c7c5be4a49577c9e6b40e8da",
                "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/files/1.11.2/launchwrapper-1.12.jar"
            }
        }
    ]
}
```

All of forge's required libraries are declared in the `version.json` file found in the root of the forge jar file. These libraries MUST be hosted and declared a submodules or forge will not work.

There were plans to add a `Forge` type, in which the required libraries would be resolved by the launcher and downloaded from forge's servers. The forge servers are down at times, however, so this plan was stopped half-implemented.

---

### Fabric

The module type `Fabric` represents the fabric mod loader. Currently, the launcher only supports modded servers, as vanilla servers can be connected to via the mojang launcher.

Ex.

```json
{
    "id": "net.fabricmc:fabric-loader:0.15.0",
    "name": "Fabric (fabric-loader)",
    "type": "Fabric",
    "artifact": {
    "size": 1196222,
    "MD5": "a43d5a142246801343b6cedef1c102c4",
    "url": "http://localhost:8080/repo/lib/net/fabricmc/fabric-loader/0.15.0/fabric-loader-0.15.0.jar"
    },
    "subModules": [
    {
        "id": "1.20.1-fabric-0.15.0",
        "name": "Fabric (version.json)",
        "type": "VersionManifest",
        "artifact": {
        "size": 2847,
        "MD5": "69a2bd43452325ba1bc882fa0904e054",
        "url": "http://localhost:8080/repo/versions/1.20.1-fabric-0.15.0/1.20.1-fabric-0.15.0.json"
        }
    }
}
```

Fabric works similarly to Forge 1.13+.

---

### LiteLoader

The module type `LiteLoader` represents liteloader. It is handled as a library and added to the classpath at runtime. Special launch conditions are executed when liteloader is present and enabled. This module can be optional and toggled similarly to `ForgeMod` and `Litemod` modules.

Ex.
```json
{
    "id": "com.mumfrey:liteloader:1.11.2",
    "name": "Liteloader (1.11.2)",
    "type": "LiteLoader",
    "required": {
        "value": false,
        "def": false
    },
    "artifact": {
        "size": 1685422,
        "MD5": "3a98b5ed95810bf164e71c1a53be568d",
        "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/files/1.11.2/liteloader-1.11.2.jar"
    },
    "subModules": [
        "All LiteMods go here"
    ]
}
```

---

### Library

The module type `Library` represents a library file which will be required to start the minecraft process. Each library module will be dynamically added to the `-cp` (classpath) argument while building the game process.

Ex.

```json
{
    "id": "net.sf.jopt-simple:jopt-simple:4.6",
    "name": "Jopt-simple 4.6",
    "type": "Library",
    "artifact": {
        "size": 62477,
        "MD5": "13560a58a79b46b82057686543e8d727",
        "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/files/1.11.2/jopt-simple-4.6.jar"
    }
}
```

---

### ForgeMod

The module type `ForgeMod` represents a mod loaded by the Forge Mod Loader (FML). These files are stored maven-style and passed to FML using forge's [Modlist format](https://github.com/MinecraftForge/FML/wiki/New-JSON-Modlist-format).

Ex.
```json
{
    "id": "com.westeroscraft:westerosblocks:3.0.0-beta-6-133",
    "name": "WesterosBlocks (3.0.0-beta-6-133)",
    "type": "ForgeMod",
    "artifact": {
        "size": 16321712,
        "MD5": "5a89e2ab18916c18965fc93a0766cc6e",
        "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/prod-1.11.2/mods/WesterosBlocks.jar"
    }
}
```

---

### LiteMod

The module type `LiteMod` represents a mod loaded by liteloader. These files are stored maven-style and passed to liteloader using forge's [Modlist format](https://github.com/MinecraftForge/FML/wiki/New-JSON-Modlist-format). Documentation for liteloader's implementation of this can be found on [this issue](http://develop.liteloader.com/liteloader/LiteLoader/issues/34).

Ex.
```json
{
    "id": "com.mumfrey:macrokeybindmod:0.14.4-1.11.2@litemod",
    "name": "Macro/Keybind Mod (0.14.4-1.11.2)",
    "type": "LiteMod",
    "required": {
        "value": false,
        "def": false
    },
    "artifact": {
        "size": 1670811,
        "MD5": "16080785577b391d426c62c8d3138558",
        "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/prod-1.11.2/mods/macrokeybindmod.litemod"
    }
}
```

---

### File

The module type `file` represents a generic file required by the client, another module, etc. These files are stored in the server's instance directory.

Ex.

```json
{
    "id": "com.westeroscraft:westeroscraftrp:2017-08-16",
    "name": "WesterosCraft Resource Pack (2017-08-16)",
    "type": "file",
     "artifact": {
        "size": 45241339,
        "MD5": "ec2d9fdb14d5c2eafe5975a240202f1a",
        "path": "resourcepacks/WesterosCraft.zip",
        "url": "http://mc.westeroscraft.com/WesterosCraftLauncher/prod-1.11.2/resourcepacks/WesterosCraft.zip"
    }
}
```
