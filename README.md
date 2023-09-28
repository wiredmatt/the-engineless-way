# The Engineless Way

## Preface

There are many Game Engines out there that get the job done, quite well... depending on your use case, [patience](https://www.reddit.com/r/Unity3D/comments/vwfe1x/unity_compile_time_too_long/) and [trust](https://kotaku.com/unity-john-riccitiello-monetization-mobile-ironsource-1849179898) on them... and the [people driving them](https://web.archive.org/web/20230713111727/https://godotforums.org/d/35412-sadly-i-think-godot-is-a-scam-im-not-sure-i-can-do-this), and their [stability](https://forums.unrealengine.com/search?q=crash), and their [overnight TOS & policy changes](https://www.gamerbraves.com/unity-silently-deletes-github-repo-that-tracks-terms-of-service-changes-and-updated-its-license/).

If you want to be able to make your games in peace, having full control over everything, you've come to the right place

## Who is this for?

- Beginners: for both programmers and game developers / designers.
- Hobbyists: for making your side projects and game jams
- Pros: for those that would like full control and low level access.
- Computer Science students: I believe making games is the best way to learn programming and fully apply all of the stuff you learn in college. Low level frameworks and libraries will force you to make your own algorithms for most things.
- People tired of all the problems that come with a mainstream Engine: I'm first in that list. I haven't had a single good experience with any of them.

## Engines that are actually decent

Before diving in, I encourage you to take a look at these, the people making them are brilliant, and so are the engines.

- [Defold](https://defold.com/) - The game engine for high-performance cross-platform games
- [pyxel](https://github.com/kitao/pyxel) - A retro game engine for Python
- [GDevelop](https://github.com/4ian/GDevelop) - Open-source, cross-platform game engine designed to be used by everyone
- [Ct.js](https://github.com/ct-js/ct-js) - An easy to use yet powerful 2D game maker
- [PlayCanvas](https://github.com/playcanvas/engine) - Fast and lightweight JavaScript game engine built on WebGL and glTF
- [Cocos Engine](https://github.com/cocos/cocos-engine) - Empowering millions of developers to create high-performance, engaging 2D/3D games and instant web entertainment
- [O3DE](https://o3de.org/) - The open source, real-time 3D engine
- [FlaxEngine](https://github.com/FlaxEngine/FlaxEngine) - Multi-platform 3D game engine
- [WickedEngine](https://github.com/turanszkij/WickedEngine) - 3D engine with modern graphics 
- [stride](https://github.com/stride3d/stride) - Open Source C# game engine for realistic rendering and VR
- [LumixEngine](https://github.com/nem0/LumixEngine) - 3D C++ Game Engine, yet another open source game engine
- [Fyrox](https://github.com/FyroxEngine/Fyrox) - 3D and 2D game engine written in Rust 
- [Crown](https://github.com/crownengine/crown) - The flexible game engine
- [Armory](https://github.com/armory3d/armory) - 3D Engine with Blender Integration 

## Windowing

The most important thing to make a game is to be able to display things. For that, you'll need a rendering or windowing API. Some of these only take care of rendering, but others also allow for audio and asset management, and OS access.

- [SDL](https://github.com/libsdl-org/SDL) - The very best, huge community.
- [SFML](https://www.sfml-dev.org/) - Maybe better than SDL, but smaller community, and no mobile support for now. 
- [Sokol](https://github.com/floooh/sokol) - Very clean API
- [bgfx](https://github.com/bkaradzic/bgfx) - Lots of stuff made with this one, pretty powerful.
- [LWJGL](https://www.lwjgl.org/) - Personal favorite, supports every single platform without an issue.
- [The Forge](https://github.com/ConfettiFX/The-Forge) - Cross-Platform Rendering Framework PC Windows, Linux, Ray Tracing, macOS / iOS, Android, XBOX, PS4, PS5, Switch, Quest 2 
- [openFrameworks](https://github.com/openframeworks/openFrameworks) - no Android, but everything else.
- [raylib](https://www.raylib.com/) - Personal recommendation for beginners. Good starting point.

## Frameworks

Libraries that are almost engines, they just don't have a fancy editor. But trust me, they are as powerful as a fully-featured engine.

- [lib-gdx](libgdx.com/) - You'll likely end up using this one. Cross-platform support, amazing abstractions, first class support for everything you'll ever need when making a game. Personal favorite.
- [ktx](https://github.com/libktx/ktx) - lib-gdx but with Kotlin. If you don't like Java or/and are concerned about performance, but still like the lib-gdx API, this one is for you
- [korge](https://github.com/korlibs/korge) - Much like ktx. Clean API.
- [raylib](https://www.raylib.com/) - Mentioned in the previous section. RayLib is very powerful, it allows for the same things most of the entries in this list do. However, this is a less opinionated framework, you are expected to code things up your way, there's are no general guidelines for it, it's up to you.
- [Monogame](https://www.monogame.net/) - I would use this one if it wasn't for the fact that it's C#. Pretty good still, I haven't entirely discarded it yet.
- [FNA](https://github.com/FNA-XNA/FNA) - Same as above. Solid.
- [Phaser](https://github.com/photonstorm/phaser) - Good for web games.
- [HaxeFlixel](https://github.com/HaxeFlixel/flixel) - A personal favorite. HaxeFlixel is just great, you'll find everything you need for your 2D games.
- [Heaps](https://github.com/HeapsIO/heaps) - Good, not a lot of concrete full examples though.
- [Ceramic](https://github.com/ceramic-engine/ceramic) - Very clean API, many features, great for prototyping.
- [ebiten](https://github.com/hajimehoshi/ebiten) - A dead simple 2D game framework for Go
- [engo](https://github.com/EngoEngine/engo) - Clean API, easy to use, ecs-based.
- [flame](https://github.com/flame-engine/flame) - Dart framework for 2D games, pretty good, but Dart syntax which not many people like... Still worth giving it a shot.
- [orx](https://github.com/orx/orx) - interesting approach with config files for basically everything, you will either love it or hate it. It's probably good if you like code distributed among files rather than a lot of code in few files.
- [RPG-JS](https://github.com/RSamaium/RPG-JS) - incredibly clean web rpg framework. Very opinionated though.