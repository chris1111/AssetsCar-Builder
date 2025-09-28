# AssetsCar Builder

[![pages-build-deployment](https://github.com/chris1111/AssetsCar-Builder/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/chris1111/AssetsCar-Builder/actions/workflows/pages/pages-build-deployment) [![License: MIT](https://github.com/chris1111/AssetsCar-Builder/blob/main/SourcesApp/MIT.svg)](https://github.com/chris1111/AssetsCar-Builder/blob/main/LICENSE)

## Utility to create Assets.car from a PNG icon file in macOS
#### This is a very useful application, given that in macOS Tahoe 26, AppleScript applications now contain Assets.car files. If you have a display dialog with icon note this will allow you to have your personal icon displayed.

#### So you'll have the Assets.car file created and also an applet.icns file.
So, change both files in the Resources of your new application, Zip the App then Unzip and Voila.
#### Assets.car file can be use on any other App with the file AppIcon.icns create.

- Working from 10.8 to macOS Tahoe 26
- You need Xcode and the commandLine xcrun. Type: `xcrun  --show-sdk-version` to verify
- You need an Icon (.png) 512x512px
- Credit: [Apple](https://developer.apple.com/documentation/Xcode/managing-assets-with-asset-catalogs), [Platypus](https://github.com/sveinbjornt/Platypus)
- View and Edit Assets.car files [Samra.zip](https://github.com/chris1111/AssetsCar-Builder/raw/refs/heads/main/SourcesApp/Samra/Samra.zip)

Download ➥ [AssetsCar Builder](https://github.com/chris1111/AssetsCar-Builder/releases/tag/v1)

## Usage: Drop the (512x512px .png Icon) to the window of the App

<img width="521" height="521" alt="Screenshot" src="https://github.com/chris1111/AssetsCar-Builder/blob/main/SourcesApp/Screenshot.png?raw=true">

<img width="1032" height="548" alt="Screenshot1" src="https://github.com/chris1111/AssetsCar-Builder/blob/main/SourcesApp/Screenshot1.png?raw=true">



