# HISPlayer Unreal IOS SDK
The most advanced video streaming player for Unreal Engine supporting VOD and Live contents. It enables premium HLS video streaming inside your Unreal games and metaverses on IOS. It is fully customizable. If you require specific or advanced features, please don't hesitate to contact us at contact@hisplayer.com.

## Compatibility
### Supported Unreal Versions: 
* 4.27
* 5.0
* 5.1
* 5.2
* 5.3

Only official Unreal versions from Epic Games Store are supported. Custom source code version is not supported.

### Supported Stream Protocols: 
* HLS
* Local Playback

### Video Codecs:
* H.264 (AVC)
  * Container Format must be fragmented MP4 (fMP4) files or MPEG transport streams
  * Profile and Level must be less than or equal to High Profile, Level 5.2. Do not use Main or Baseline Profile.
* H.265 (HEVC)
  * Container Format must be fragmented MP4 (fMP4) files
  * Profile, Level, and Tier must be less than or equal to Main 10 Profile, Level 5.1, High Tier.

### Audio Codecs:
* AAC
* MP3

### Supported Local Formats
* WMV
* RM
* MP3
* ACC
* AVI
* MP4
* OGG
* WAV
* MKV
* XVID
* FLV
* RMVB
* 3GP
* MPG

### Supported Unreal’s Rendering Mode: 
* Texture
* UMG UI

### Supported Graphics API:
* Metal
  
### HISPlayer Unreal SDK is available to be built using Windows platform, so you will need to build remotely for IOS from a Windows device. For more information on how to do it, check the [official Unreal guide](https://docs.unrealengine.com/5.2/en-US/building-ios-projects-on-windows-in-unreal-engine/).

### Multistream is not supported for IOS platform.

## Unreal for IOS Minimum IOS Version:
* 15

## Unreal 5 for Windows Requirements:
* Visual Studio 2022

## XCode Supported version:
* 14.2
