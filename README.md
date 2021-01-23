# HPTK [![](https://img.shields.io/badge/unity-2019.4%20or%20later-green.svg)](https://unity3d.com/es/get-unity/download/archive) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/jorgejgnz/HPTK/blob/master/LICENSE.md) [![version](https://img.shields.io/badge/version-0.4.0-blue)](https://github.com/jorgejgnz/HPTK/releases) [![](https://img.shields.io/twitter/follow/jorgejgnz.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=jorgejgnz)

Hand Physics Toolkit (HPTK) is a toolkit to build physical hand-driven interactions in a modular and scalable way. Platform-independent. Input-independent. This toolkit can be combined with [MRTK-Quest](https://github.com/provencher/MRTK-Quest) for UI interactions.

## Main features
- Data model to access hand parts, components or calculated values with very little code.
- Code architecture based on MVC-like modules. ([Wiki](https://github.com/jorgejgnz/HPTK/wiki/Modules-overview)). Support to custom modules. ([Wiki](https://github.com/jorgejgnz/HPTK/wiki/Custom-modules)).
- State-of-the-art hand physics. Configurable in detail through configuration assets.
- Platform-independent. Tested on VR/AR/non-XR applications
- Input-independent. Use handtracking or controllers.
- Scale-independent. Valid for any hand size.
- Define strategies to deal with loss of tracking.
- Physics-based touch/grab detection.
- Tracking noise smoothing.

## Example project
- You can clone a ready-to-go project at [HPTK-Sample](https://github.com/jorgejgnz/HPTK-Sample).

[![Demo video](./Documentation/Media/hptk.gif)](https://twitter.com/jorgejgnz/status/1285514990619942912)

# Supported versions
- Unity 2019.4.4f1 LTS, 2019.3.15f1

# Supported input
## Hand tracking
* [Oculus Quest 1/2 - Android](https://github.com/jorgejgnz/HPTK-Sample/tree/master/Assets/HPTK-Sample/Scripts/Input)
* Hololens 2 - UWP

## Controllers
* [UnityXR-compatible controllers](https://docs.unity3d.com/Manual/xr_input.html) with:
     * Index trigger
	 * Grip trigger
	 * Primary 2D axis

# Supported render pipelines
- Universal Render Pipeline (URP)
- Standard RP

# Getting started with HPTK (Oculus Quest)

1. Obtain *HPTK*.
1. Import *Oculus Integration*.
1. Configure *Build Settings* (Oculus Quest).
1. Configure *Project Settings* (!).
1. Setup a scene with *hand tracking support* (Oculus Quest).
1. Setup *HPTK specific components*.
1. Setup *platform specific HPTK components* (Oculus Quest).
1. Modify/Create *HPTK Configuration Assets* (if needed).

Checkout the [Wiki](https://github.com/jorgejgnz/HPTK/wiki/Getting-started) for a detailed **step-by-step guide**.

# Wiki
The [Wiki](https://github.com/jorgejgnz/HPTK/wiki) also includes more details about:
- Modules overview.
- Getting started with HPTK.
- How to build new HPTK modules.

# Author
**Jorge Juan González** - *HCI Researcher at I3A (University of Castilla-La Mancha)*

[LinkedIn](https://www.linkedin.com/in/jorgejgnz/) - [Twitter](https://twitter.com/jorgejgnz) - [GitHub](https://github.com/jorgejgnz)

## Acknowledgements

**Oxters Wyzgowski** - [GitHub](https://github.com/oxters168) - [Twitter](https://twitter.com/OxGamesCo)

**Michael Stevenson** - [GitHub](https://github.com/mstevenson)

Nasim, K, Kim, YJ. Physics-based assistive grasping for robust object manipulation in virtual reality. Comput Anim Virtual Worlds. 2018; 29:e1820. [https://doi.org/10.1002/cav.1820](https://doi.org/10.1002/cav.1820)

Linn, Allison. Talking with your hands: How Microsoft researchers are moving beyond keyboard and mouse. The AI Blog. Microsoft. 2016
[https://blogs.microsoft.com/](https://blogs.microsoft.com/ai/talking-hands-microsoft-researchers-moving-beyond-keyboard-mouse/)

# License
[MIT](./LICENSE.md)
