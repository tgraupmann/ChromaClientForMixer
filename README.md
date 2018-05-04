# ChromaClientForMixer
Broadcast Chroma lighting from a Mixer game client

## Table of Contents

* [See Also](#see-also)
* [Releases](#releases)
* [Dependencies](#dependencies)
* [Overview](#Overview)

## See Also

**Apps:**

- [ChromaClientForDiscord](https://github.com/tgraupmann/ChromaDiscordApp) - Add Chroma lighting to the Discord App events

- [ChromaClientForMixer](https://github.com/tgraupmann/ChromaClientForMixer) - Add Chroma lighting to the Mixer streaming experience

- [ChromaClientForTwitch](https://github.com/tgraupmann/ChromaTwitchExtension) - Add Chroma lighting to the Twitch streaming experience

**Plugins:**

- [CChromaEditor](https://github.com/RazerOfficial/CChromaEditor) - C++ native MFC library for playing and editing Chroma animations

- [GameMakerChromaExtension](https://github.com/RazerOfficial/GameMakerChromaExtension) - GameMaker extension to control lighting for Razer Chroma

- [HTML5ChromaSDK](https://github.com/RazerOfficial/HTML5ChromaSDK) - JavaScript library for playing Chroma animations

- [UE4ChromaSDKRT](https://github.com/RazerOfficial/UE4ChromaSDKRT) - UE4 runtime module with Blueprint library for the ChromaSDK

- [UnityNativeChromaSDK](https://github.com/RazerOfficial/UnityNativeChromaSDK) - Unity native library for the ChromaSDK

## Releases

* [Chroma Client for Mixer Installer](https://github.com/tgraupmann/ChromaClientForMixer/releases) for Windows

## Dependencies

* [Razer Synapse](https://www.razerzone.com/synapse) - Control `Chroma` application priority

* [Razer Chroma SDK](http://developer.razerzone.com/works-with-chroma/download/) - Allow applications to control `Chroma` lighting. The `ChromaSDK` is automatically installed by `Synapse` when a `Chroma` device is connected.

## Overview

The `Mixer` game client broadcasts Chroma lighting for viewers of your live stream. The game client also displays an interactive Chroma widget in your live stream.

**Installer**

First install the `ChromaClientForMixer` found in the [Releases](#releases) section.

The installer creates an application shortcut on the desktop.

![image_5](images/image_5.png)

**Application**

Launch the `Chroma Game Client for Mixer`.

![image_4](images/image_4.png)

Click the `Authorize Mixer` button to allow the game client to broadcast to `Mixer`.

![image_2](images/image_2.png)

The `APPROVE` button will authorize the game client.

![image_3](images/image_3.png)

When the `Broadcast on Mixer` checkbox is checked, Chroma will broadcast to `Mixer`. The checkbox can be checked at any time. Broadcast is intended to be enabled simultaneously with other software like `OBS`.

![image_1](images/image_1.png)

**Custom Widget**

* The `Chroma` circle is a draggable widget that can be placed anywhere on top of the live video.

* The `eye` will toggle visibility for the group of virtual `Chroma` devices.

* The `device` icons will toggle display of the virtual device grids.

![image_6](images/image_6.png)
