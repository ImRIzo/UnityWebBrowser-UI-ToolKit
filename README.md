<img align="right" width="20%" src="media/UWB-Icon.svg">

# Unity Web Browser

[![License](https://img.shields.io/github/license/Voltstro-Studios/UnityWebBrowser.svg)](/LICENSE.md)
[![Build](https://github.com/Voltstro-Studios/UnityWebBrowser/actions/workflows/main.yml/badge.svg)](https://github.com/Voltstro-Studios/UnityWebBrowser/actions/workflows/main.yml)
[![Discord](https://img.shields.io/badge/Discord-Voltstro-7289da.svg?logo=discord)](https://discord.voltstro.dev) 
[![YouTube](https://img.shields.io/badge/Youtube-Voltstro-red.svg?logo=youtube)](https://www.youtube.com/Voltstro)

Unity Web Browser (UWB) is a Unity package that allows displaying and interacting with the web from within Unity.

This project is capable of using any desired web engine you want, however for now we only have an engine using [CEF](https://bitbucket.org/chromiumembedded/cef/).

## Features

- Easy Installation with UPM
- Great Performance
- Multi-Platform Desktop Support
- API to Interact with the Engine
- Extendable
- 100% Open-Source

## Getting Started

### Prerequisites

```
Unity 2021.3.x
```

### Install

1. Setup [VoltstroUPM](https://github.com/Voltstro/VoltstroUPM#setup)
2. Define the additional scopes `org.nuget` and `com.cysharp.unitask` with VoltstroUPM
3. Install the required packages!
    - UnityWebBrowser
4. Install an engine:
    - E.G.: UnityWebBrowser CEF Engine with Windows natives

For a more in-depth installation guide, check out the [setup article](https://projects.voltstro.dev/UnityWebBrowser/articles/user/setup/).

## Documentation

For further documentation, see [UWB's project site](https://projects.voltstro.dev/UnityWebBrowser/articles/).

The project site covers information such as Engines, Platform support, advance setup, plus more.

## Contributing

For learning how to setup UWB repo for development, use the [developer guide article](https://projects.voltstro.dev/UnityWebBrowser/articles/dev/dev-guide/).

## Screenshots

<details>
  <summary>Click to expand!</summary>

![Screenshot 1](media/Screenshot-Editor1.png)
![Screenshot 2](media/Screenshot-Editor2.png)
![Screenshot 3](media/Screenshot-Editor3.png)
![Screenshot 4](media/Screenshot-InPlayer.png)

</details>

## Authors

* **Voltstro** - *Initial work* - [Voltstro](https://github.com/Voltstro)

## License

This project is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details.

## Thanks

Thank you to many different projects and people that have made this project possible.

### CEF Engine

This projects were used as inspiration/how-to for the CEF Engine.

- [CEF](https://bitbucket.org/chromiumembedded/cef/src/master/) - Underlying web engine.
- [CefGlue](https://gitlab.com/xiliumhq/chromiumembedded/cefglue) - C# wrapper.
- [CefUnitySample](https://github.com/aleab/cef-unity-sample) - CEF directly in Unity. Has crashing problems tho.
- [unity_browser](https://github.com/tunerok/unity_browser) - (Orginally by Vitaly Chashin) CEF working in Unity using IPC, but the project is in a messy state.
- [ChromiumGtk](https://github.com/lunixo/ChromiumGtk) - Linux stuff with CEF