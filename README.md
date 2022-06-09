# Fix for Legacy versions of Minecraft
## How to install ?
Go to your `.minecraft` -> `versions`\
Duplicate the folder `b1.7.3`, replace `b1.7.3` with any Legacy version of Minecraft you want to fix\
Rename the duplicated folder `b1.7.3-fix_skin`\
Inside the folder, also rename the files\
Open the json file, replace `"id": "b1.7.3",` with `"id": "b1.7.3-fix_skin",`\
And replace this
```
		{
			"downloads": {
				"artifact": {
					"path": "net/minecraft/launchwrapper/1.5/launchwrapper-1.5.jar",
					"sha1": "5150b9c2951f0fde987ce9c33496e26add1de224",
					"size": 27787,
					"url": "https://libraries.minecraft.net/net/minecraft/launchwrapper/1.5/launchwrapper-1.5.jar"
				}
			},
			"name": "net.minecraft:launchwrapper:1.5"
		},
```
with this
```
		{
			"downloads": {
				"artifact": {
					"path": "net/minecraft/launchwrapper/1.12/launchwrapper-1.12.jar",
					"sha1": "f10673e02551918883e1e05e1f21b1f580970b9e",
					"size": 37580,
					"url": "https://github.com/DelofJ/LegacyLauncher/releases/download/v1.12.2/launchwrapper-1.12.jar"
				}
			},
			"name": "net.minecraft:launchwrapper:1.12"
		},
		{
			"downloads": {
				"artifact": {
					"path": "org/apache/logging/log4j/log4j-api/2.8.1/log4j-api-2.8.1.jar",
					"sha1": "e801d13612e22cad62a3f4f3fe7fdbe6334a8e72",
					"size": 228859,
					"url": "https://libraries.minecraft.net/org/apache/logging/log4j/log4j-api/2.8.1/log4j-api-2.8.1.jar"
				}
			},
			"name": "org.apache.logging.log4j:log4j-api:2.8.1"
		},
		{
			"downloads": {
				"artifact": {
					"path": "org/apache/logging/log4j/log4j-core/2.8.1/log4j-core-2.8.1.jar",
					"sha1": "4ac28ff2f1ddf05dae3043a190451e8c46b73c31",
					"size": 1402925,
					"url": "https://libraries.minecraft.net/org/apache/logging/log4j/log4j-core/2.8.1/log4j-core-2.8.1.jar"
				}
			},
			"name": "org.apache.logging.log4j:log4j-core:2.8.1"
		},
		{
			"downloads": {
				"artifact": {
					"path": "com/mojang/authlib/2.3.31/authlib-2.3.31.jar",
					"sha1": "bbd00ca33b052f73a6312254780fc580d2da3535",
					"size": 87662,
					"url": "https://libraries.minecraft.net/com/mojang/authlib/2.3.31/authlib-2.3.31.jar"
				}
			},
			"name": "com.mojang:authlib:2.3.31"
		},
		{
			"downloads": {
				"artifact": {
					"path": "com/google/code/gson/gson/2.8.0/gson-2.8.0.jar",
					"sha1": "c4ba5371a29ac9b2ad6129b1d39ea38750043eff",
					"size": 231952,
					"url": "https://libraries.minecraft.net/com/google/code/gson/gson/2.8.0/gson-2.8.0.jar"
				}
			},
			"name": "com.google.code.gson:gson:2.8.0"
		},
		{
			"downloads": {
				"artifact": {
					"path": "org/apache/commons/commons-lang3/3.5/commons-lang3-3.5.jar",
					"sha1": "6c6c702c89bfff3cd9e80b04d668c5e190d588c6",
					"size": 479881,
					"url": "https://libraries.minecraft.net/org/apache/commons/commons-lang3/3.5/commons-lang3-3.5.jar"
				}
			},
			"name": "org.apache.commons:commons-lang3:3.5"
		},
		{
			"downloads": {
				"artifact": {
					"path": "com/google/guava/guava/21.0/guava-21.0.jar",
					"sha1": "3a3d111be1be1b745edfa7d91678a12d7ed38709",
					"size": 2521113,
					"url": "https://libraries.minecraft.net/com/google/guava/guava/21.0/guava-21.0.jar"
				}
			},
			"name": "com.google.guava:guava:21.0"
		},
		{
			"downloads": {
				"artifact": {
					"path": "commons-io/commons-io/2.5/commons-io-2.5.jar",
					"sha1": "2852e6e05fbb95076fc091f6d1780f1f8fe35e0f",
					"size": 208700,
					"url": "https://libraries.minecraft.net/commons-io/commons-io/2.5/commons-io-2.5.jar"
				}
			},
			"name": "commons-io:commons-io:2.5"
		},
		{
			"downloads": {
				"artifact": {
					"path": "commons-codec/commons-codec/1.10/commons-codec-1.10.jar",
					"sha1": "4b95f4897fa13f2cd904aee711aeafc0c5295cd8",
					"size": 284184,
					"url": "https://libraries.minecraft.net/commons-codec/commons-codec/1.10/commons-codec-1.10.jar"
				}
			},
			"name": "commons-codec:commons-codec:1.10"
		},
```
(Yeah it looong)\
You're done, go select Minecraft b1.7.3-fix_skin in your launcher