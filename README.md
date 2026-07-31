# WoWMap-UE5

**WoWMapUE5** is an Unreal Engine 5.7 project focused on importing and rendering the complete **World of Warcraft 12.0.7 world map** inside Unreal Engine.

The goal of the project is to recreate the World of Warcraft world as a large, explorable Unreal Engine level while taking advantage of Unreal Engine’s modern rendering, lighting, performance, and scalability systems.

> **Project Status:** Early development

<img width="3840" height="2081" alt="1" src="https://github.com/user-attachments/assets/4d6dc2f4-2362-411d-8136-635bedc8a34a" />

<img width="3840" height="2075" alt="Mainn" src="https://github.com/user-attachments/assets/f15569ce-76ff-49cc-b3b5-db4f3af30c25" />

<img width="3840" height="2075" alt="swimablewater" src="https://github.com/user-attachments/assets/265c4927-a48e-4435-b780-618c50a875cf" />

<img width="3840" height="2081" alt="2" src="https://github.com/user-attachments/assets/51ebf5eb-9d6e-46a5-b9e3-d65311ec3012" />

## Features

* Importing the full World of Warcraft 12.0.7 world map
* Large-scale world support in Unreal Engine 5.7
* World of Warcraft terrain and map asset integration
* Configurable graphics and performance settings
* NVIDIA DLSS support
* In-game video settings menu
* Support for different hardware configurations
* Expandable foundation for exploration, testing, and development

## Video Settings Menu

WoWMapUE5 includes an in-game video settings menu for configuring graphical quality and performance.

Available settings include:

* Resolution scale
* Frame-rate limit/unlock
* Vertical synchronization
* NVIDIA DLSS
* DLSS quality mode
* Shadow quality
* Effects quality
* Foliage quality
* Anti-aliasing quality
* Post-processing quality

Additional settings may be added as development continues.

## Requirements

The following software and plugins are required:

* **Unreal Engine 5.7**
* **NVIDIA DLSS 4.5 Plugin**
* A development environment capable of opening and compiling Unreal Engine 5.7 projects

An NVIDIA RTX graphics card is required to use DLSS. The project may still operate without DLSS on supported non-RTX hardware when another anti-aliasing or upscaling method is selected.

Before opening the project, ensure that the correct DLSS plugin version has been installed for Unreal Engine 5.7.

The primary goals of WoWMapUE5 are:

1. Import the World of Warcraft 12.0.7 world into Unreal Engine.
2. Preserve the original world scale and map layout as accurately as possible.
3. Organize the imported world into manageable Unreal Engine levels or World Partition cells.
4. Provide scalable graphics settings for a wide range of hardware.
5. Use DLSS to improve performance when rendering the large imported world.
6. Create a stable foundation for future exploration and development features.

Planned development areas include:

* Full terrain import (16K Version)

<img width="3840" height="2076" alt="16k" src="https://github.com/user-attachments/assets/33204886-953a-4876-bb2e-045b2f8c710f" />

## Development Roadmap

* streamed sub levels loading/unloading integration
* Static mesh placement
* Texture and material conversion
* Water and ocean support - Swimable Water Blueprints.
* Foliage placement
* Lighting and atmosphere
* Collision generation (Complex Collision)
* Navigation support - Open World Level Navmesh Bound Volume
* Level-of-detail improvements

The roadmap may change as the import pipeline and project requirements evolve.

## Repository Notes

Unreal Engine projects can contain extremely large files. Contributors should avoid committing unnecessary generated data.

The following directories should normally not be committed:

```text
Binaries/
DerivedDataCache/
Intermediate/
Saved/
.vs/
```

The following files and directories should be included:

```text
Config/
Content/
Plugins/
Source/
WoWMapUE5.uproject
```

## Contributing

Contributions, testing, fixes, and improvements are welcome.

## Disclaimer

WoWMapUE5 is an independent, unofficial development and research project.

This project is not affiliated with, endorsed by, sponsored by, or approved by Blizzard Entertainment.

**World of Warcraft**, **Warcraft**, Blizzard Entertainment, and all associated names, characters, locations, artwork, models, textures, audio, trademarks, and copyrighted materials are the property of their respective owners.

Users are responsible for ensuring that they have the legal right to access, extract, convert, use, and distribute any game assets used with this project.

World of Warcraft game assets should not be included in public releases of this repository unless their distribution is explicitly permitted by the applicable rights holder.

## License

The source code created specifically for WoWMapUE5 may be distributed under the license included with this repository.

The project license does not grant permission to use or redistribute:

* World of Warcraft assets
* Blizzard Entertainment intellectual property
* Unreal Engine proprietary components
* NVIDIA DLSS binaries or proprietary components

Third-party software and plugins remain subject to their own licenses and distribution terms.
