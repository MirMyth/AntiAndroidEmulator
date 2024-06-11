# Anti Android Emulator
Advanced Android Emulator Detection Plugin for Unreal Engine

## How to use
### Settings
![Settings](https://github.com/MirMyth/AntiAndroidEmulator/assets/7219958/fadf6f55-dcde-4350-86a9-568a0ce843fc)

### Customize Action in Blueprint
![InBlueprint](https://github.com/MirMyth/AntiAndroidEmulator/assets/7219958/db425e36-68bc-4765-83f6-9c53b58524ea)


## Compatible Engine Version
Anti Android Emulator is fully compatible with all versions of Unreal Engine. However, since the Unreal Marketplace can only publish content compatible with the latest 3 versions of the engine, if you want to use it in older versions of Unreal Engine, you need to modify the following content of AntiAndroidEmulator.uplugin by yourself:

Example for 4.72

```json
"EngineVersion": "5.4.0",   ===> "EngineVersion": "4.72",

"PlatformAllowList": ["Win64", "Mac", "Linux", "Android"] ===> "WhitelistPlatforms": ["Win32", "Win64", "Mac", "Linux", "Android"]
```
