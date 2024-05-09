# Trenchbroom Demo

## About
This document is a quick demo with Godot 4.2 and Trenchbroom. It's for Daniel's mentee within the ATVI mentorship program.

The purpose is to show brush-based level design, and how it might be usable in a contemporary game engine to make interesting spaces.

## Set-up
In order to load and run this project, you'll need to download the following:
- [Godot 4.2.2](https://godotengine.org/download/archive/) (This hasn't been tested with 4.3 or newer versions, but _should_ work as of writing!)
- The [Trenchbroom](https://trenchbroom.github.io/) level editor (2024.1 or later)

You likely won't immediately see textures when loading the maps in Trenchbroom. This is because the "game directory" has to be set per-machine in the options menu. To fix this, try the following:
1. Open the Preferences menu via `View -> Preferences`
2. In the **Games** section, click **Generic**
3. Set the **Game Path** property to the `maps` folder in this (wherever you've downloaded it)
4. If done correctly, textures should load
![Preferences panel for trenchbroom](https://github.com/danbolt/trenchbroom-demo/assets/1205433/2d395703-b454-44ab-a4a2-ed2411a0dcdf)
