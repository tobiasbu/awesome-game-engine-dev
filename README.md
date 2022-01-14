<h1 align="center">
    <img width="1100" src="aged-title.png" alt="Awesome Game Engine Dev Logo"/>
</h1>

# Awesome Game Engine Development [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome assets, libraries, and tools for Game Engine Development. Specifically, this list is geared toward development of high-level, fully featured game engines (e.g., [Godot](https://godotengine.org) / [Unity](https://unity.com)). This would include things typically not found in low-level game engines, game frameworks, or graphics libraries (e.g., [MonoGame](https://www.monogame.net) / [SDL](https://www.libsdl.org)). Most importantly of which would be a visual scene editor, but also capabilities such as scipting support, physics integration, special effects, etc. 

This list currently favors (but is not limited to) programming the core engine in the following languages: C, C++, C#, Haxe, or Javascript.

<br>

### NOTE: This list is under development, it is still in draft state. Contributions will be welcome when the draft is complete, but are currently not accepted.

<br>

### License Legend
- Open Source Software
    - :star: - [Public Domain License](https://en.wikipedia.org/wiki/Public-domain-equivalent_license) ([CC0](https://creativecommons.org/publicdomain/zero/1.0/), [BOLA](https://blitiri.com.ar/p/bola/), [WTFPL](https://en.wikipedia.org/wiki/WTFPL), [Unlicense](https://en.wikipedia.org/wiki/Unlicense), etc.)
    - :tada: - [Permissive License](https://en.wikipedia.org/wiki/Permissive_software_license) ([MIT](https://en.wikipedia.org/wiki/MIT_License), [BSD](https://en.wikipedia.org/wiki/BSD_licenses), [ZLIB / LIBPNG](https://en.wikipedia.org/wiki/Zlib_License), [ISC](https://en.wikipedia.org/wiki/ISC_license), [Apache](https://en.wikipedia.org/wiki/Apache_License), etc.)
    - :lock: - [Copyleft License](https://en.wikipedia.org/wiki/Copyleft) ([CC](https://en.wikipedia.org/wiki/Creative_Commons_license), [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) / [LGPL](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License), [MPL](https://en.wikipedia.org/wiki/Mozilla_Public_License), etc.)
- Asset / Service / Tool
    - :free: - Free
    - :moneybag: - Paid
    - :money_with_wings: - Partially Free
- Other
    - :books: - Article
    - :earth_americas: - Website
- :octocat: - Link to repo, click on it to see the source code!
- :fire: - Hot! Amazing, must-see resource!
<br><br>

## Index
- [Game Development](#Game-Development)
    - [Collections](#Collections)
    - [Developer Portals](#Developer-Portals)
- [Game Engines](#Game-Engines)
    - [Popular](#Popular)
    - [AAA](#AAA)
    - [Commercial](#Commercial)
    - [Specialty](#Specialty)
- [How To](#How-To)
    - [AI](#AI)
    - [Animating](#Animating)
    - [Geometry](#Geometry)
    - [Lighting](#Lighting)
    - [Particles](#Particles)
    - [Physics](#Physics)
    - [Programming](#Programming)
    - [Scripting](#Scripting)
    - [Shaders](#Shaders)
    - [Speciality](#Speciality)
    - [Transparency](#Transparency)
    - [Water](#Water)
- [Learning](#Learning)
    - [Computer Graphics](#Computer-Graphics)
    - [Game Engine Development](#Game-Engine-Development)
    - [Programming](#Programming)
- [Libraries](#Libraries)
    - [C](#C)
    - [C++](#Cpp)
    - [C#](#CSharp)
    - [Haxe](#Haxe)
    - [Java](#Java)
    - [Javascript](#Javascript)
    - [Python](#Python)
- [Tools](#Tools)
    - [Animation](#Animation)
    - [Color](#Color)
    - [Drawing](#Drawing)
    - [Game Dev](#Game-Dev)
    - [Image Editors](#Image-Editors)
    - [Materials](#Materials)
    - [Modeling](#Modeling)
    - [Particles](#Particles)
    - [Pixel Art](#Pixel-Art)
    - [Sound](#Sound)
    - [Textures](#Textures)

<br>

## Game Development
_Helpful resources for game development_
- ### Collections
    - :books: [Awesome Gamedev](https://github.com/Calinou/awesome-gamedev#readme) : A collection of free software and free culture resources for making amazing games.
    - :books: [Awesome Graphics Libraries](https://github.com/jslee02/awesome-graphics-libraries#readme) : Awesome curated list of 3D graphics libraries and resources.
    - :books: [Magictools](https://github.com/ellisonleao/magictools#readme) : A list of Game Development resources to make magic happen.
- ### Developer Portals
    - :earth_americas: [GameDev.net](https://www.gamedev.net) : Huge resource for game development with forums, tutorials, blogs, projects, portfolios, news, and more.
    - :earth_americas: [GameFromScratch.com](https://gamefromscratch.com) : Game development news, tutorials and so much more.
    - :earth_americas: [itch.io](https://itch.io) : Platform to host, showcase, promote, buy and sell games and game development resources.

<br>

## Game Engines
_Production game engines to tinker with, explore, learn and inspire_
- ### Popular
    - :tada: [Godot](https://godotengine.org) [:octocat:](https://github.com/godotengine/godot#readme) : :fire: Feature-packed, open source engine. Excellent! [[Awesome Godot](https://github.com/godotengine/awesome-godot#readme)]
    - :money_with_wings: [Unity](https://unity.com) : Sets the bar for Game Engines. [[Awesome Unity](https://github.com/RyanNielson/awesome-unity)]
    - :money_with_wings: [Unreal Engine](https://www.unrealengine.com) : AAA game capable, photoreal visuals. [[Awesome UE4](https://github.com/insthync/awesome-ue4#readme)]
    - :books: [Wikipedia: List of Game Engines](https://en.wikipedia.org/wiki/List_of_game_engines) : Thorough list of game engines along with their platforms and licenses.
- ### AAA
    - :tada: [Amazon Lumberyard](https://aws.amazon.com/lumberyard/) [:octocat:](https://github.com/aws/lumberyard) : Free, open source AAA game engine deeply integrated with AWS and Twitch.
    - :moneybag: [C4 Engine](http://c4engine.com) : Modern console engine.
    - :money_with_wings: [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK/CRYENGINE) : Powerful real-time game development platform created by Crytek.
    - :free: [Evergine](https://evergine.com) : (previously known as Wave Engine) The graphics development engine for business and industry. Build high-quality 3D and 2D solutions and deploy to any platform. [[Projects/Samples](https://github.com/EvergineTeam/Samples)]
    - :money_with_wings: [Flax Engine](https://flaxengine.com) [:octocat:](https://github.com/FlaxEngine/FlaxEngine) : Modern 3D game engine written in C++ and C#. Stunning graphics, powerful scripts.
    - :moneybag: [FROSTBITE](https://www.ea.com/frostbite) : (by Electronic Arts) Cutting-Edge Games and Experiences.
    - :moneybag: [Gamebryo](http://www.gamebryo.com) : Complete toolset, flexible workflow, rapid prototyping.
    - :money_with_wings: [NeoAxis](https://www.neoaxis.com) [:octocat:](https://github.com/NeoAxis/NeoAxisEngine) : Versatile real-time platform for making 2D / 3D games and apps.
    - :tada: [O3DE](https://docs.o3de.org) [:octocat:](https://github.com/o3de/o3de/) : (Successor to Amazon Lumberyard) Multi-platform AAA-capable 3D engine to build cinema-quality 3D worlds, and high-fidelity simulations.
    - :moneybag: [Snowdrop Engine](https://www.massive.se/project/snowdrop-engine/) : (by Massive Entertainment) Enabling relatively small teams to create ambitious AAA games.
    - :money_with_wings: [Unigine](https://unigine.com) : Real-time 3D engine. Photorealistic graphics, large virtual worlds, C++ and C# API.
- ### Commercial
    - :moneybag: [AppGameKit Studio](https://www.appgamekit.com/studio) : Easy, quick and powerful programming.
    - :money_with_wings: [Buildbox](https://www.buildbox.com) : Create 3D & 2D video games without coding.
    - :money_with_wings: [Construct](https://www.construct.net/) : Browser based drag and drop game builder. [[Awesome Construct](https://github.com/ConstructCommunity/awesome-construct#readme)]
    - :money_with_wings: [Felgo](https://felgo.com/games) : Build Cross-Platform 2D Games in Days. Based on the Qt framework.
    - :money_with_wings: [GameMaker Studio](https://www.yoyogames.com/en/gamemaker) : (by YoYo Games) 2D Game Development Environment with large following.
    - :money_with_wings: [GameSalad](https://gamesalad.com) : Sophisticated visual programming interface.
    - :money_with_wings: [MANU](https://manu.co) : Unique animation system helps you create games without coding.
    - :money_with_wings: [PlayCanvas](https://playcanvas.com) [:octocat:](https://github.com/playcanvas/engine) (Repo for  runtime only) : Popular (Flappy Bird), fast and lightweight JavaScript game engine built on WebGL.
    - :money_with_wings: [ShiVa](https://shiva-engine.com) : 3D game and application development suite.
    - :money_with_wings: [Simulation Starter Kit](https://benmorris.itch.io/plugin-based-scene-editor) : Supports the creation of simple interactive 3D applications across a range of platforms and devices. [[Developer Website](http://fireflytech.org)]
    - :money_with_wings: [Stencyl](http://www.stencyl.com) [:octocat:](https://github.com/Stencyl/stencyl-engine) (Repo for  runtime only) : Quick and easy game making. Visual scripting similar to [Scratch](https://scratch.mit.edu).
- ### Specialty
    - :moneybag: [3dSen](https://geod.itch.io/3dnes) : Unique NES emulator that converts NES games into full 3D experiences and let you play them in realtime. [Developer Website](http://www.geodstudio.net)
    - :money_with_wings: [DopeFish](https://subpixel-studios.itch.io/dopefish) : Full GML Doom/Heretic map loading system for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :tada: [GB Studio](https://www.gbstudio.dev) [:octocat:](https://github.com/chrismaltby/gb-studio) : Retro adventure game creator for Game Boy available for Mac, Linux and Windows.
    - :moneybag: [Platforming Engine](https://robvansaaze.itch.io/platforming-engine) : Everything you need to create your very own platforming game for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :moneybag: [RPG Maker](https://www.rpgmakerweb.com) : Lets you create an original role-playing game without any specialized knowledge or training.

<br>

## How To
_Exploring specific functionality of a game engine_
- ### AI
- ### Animating
- ### Geometry
    - ### Mesh
        - :books: [Mesh Transforms](https://ciechanow.ski/mesh-transforms/) [:octocat:](https://github.com/olegtyshcneko/CAMeshTransform) : Interesting info on Apple's private API that allows manipulation of the mesh of any UIView.
- ### Lighting
    - ### Lighting 2D
    - ### Lighting 3D
    - ### Shadows 2D
    - ### Shadows 3D
        - :books: [Screen Space Shadows](https://panoskarabelas.com/posts/screen_space_shadows/) : Great exploration of screen space shadows.
- ### Particles
- ### Physics
- ### Scripting
- ### Shaders
    - ### Articles
    - ### Bloom
    - ### Fire
    - ### Noise
    - ### Outlines
    - ### Smoke
- ### Speciality
    - ### Blob Tiles
    - ### Portals
    - ### Ropes
- ### Transparency
- ### Water

<br>

## Learning
_Info on topics necessary for designing and developing game engines_
- ### Computer Graphics
    - ### DirectX
        - :earth_americas: [DirectXTutorial.com](http://www.directxtutorial.com/default.aspx) : Older resource with lots of tutorials on DirectX versions 9 & 11.
    - ### Metal
    - ### OpenGL
        - :earth_americas: [Learn OpenGL](https://learnopengl.com) : :fire: Incredible resource! Teaches you everything you need to do modern graphics programming!
        - :earth_americas: [opengl-tutorial](https://www.opengl-tutorial.org) : Excellent collection of OpenGL tutorials with full source covering lots of topics.
    - ### Vulkan
    - ### WebGL
- ### Game Engine Development
    - :earth_americas: [3D Game Engine Programming](https://www.3dgep.com) : Helping you build your dream game engine.
    - :books: [How to become a game engine developer](https://www.haroldserrano.com/blog/how-to-become-a-game-engine-developer) : Short and simple starting point on Game Engine Development
- ### Programming
    - :books: [Games of Coding](https://github.com/michelpereira/awesome-games-of-coding#readme) : Awesome list of games that teach you a programming language.
    - :books: [Learn to Program](https://github.com/karlhorky/learn-to-program#readme) : Educational resources to learn to program.

<br>

## Libraries
_Language specific game engine development libraries / frameworks / code_
- ### C
    - ### - Language -
        - :books: [Learn C Programming](https://www.programiz.com/c-programming) : Excellent C tutorials that will guide you to learn C programming one step at a time.
    - ### - Language: Collections -
        - :star: [Cute Headers](https://github.com/RandyGaul/cute_headers) : Collection of cross-platform one-file C/C++ libraries with no dependencies, primarily used for games
        - :star: [Pico Headers](https://github.com/empyreanx/pico_headers) : Single-header, cross-platform libraries for game development, written in C
        - :books: [Single File Libs](https://github.com/nothings/single_file_libs) : Amazing collection of single file C/C++ libraries
        - :star: [stb](https://github.com/nothings/stb) : :fire: The original and amazing stb single-file public domain libraries for C/C++
    - ### App Frameworks
        - :tada: [SDL](https://libsdl.org) [:octocat:](https://github.com/libsdl-org/SDL) : :fire: Classic, cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D and Metal.
        - :tada: [Sokol](https://floooh.github.io/sokol-html5/) [:octocat:](https://github.com/floooh/sokol) : :fire: Top notch single file header libraries that include cross platform a phenomenal graphics abstraction api, windowing, file handling, audio and more. Excellent!! [[Learn OpenGL Examples, ported to Sokol](https://www.geertarien.com/learnopengl-examples-html5/)]
    - ### Audio

    - ### Entity Component Systems

    - ### File Loading

    - ### Fonts

    - ### Game Engine

    - ### Geometry

    - ### Graphics
        - :tada: [Sokol Graphics Painter](https://github.com/edubart/sokol_gp) : Minimal modern efficient cross platform 2D graphics painter (api) in C implemented using [Sokol](https://floooh.github.io/sokol-html5/) as the backend.
    - ### Gui

    - ### Input
        - :tada: [Sokol Gamepad](https://github.com/floooh/sokol/pull/393/commits/26a9da9dafd4adb22a1ace0de0d2569da31ae427) : Branch with add on support for game pads in [Sokol](https://github.com/floooh/sokol).
    - ### Math

    - ### Physics

    - ### Scripting

    - ### Utility

    - ### Vector Graphics

    - ### Windowing

- ### C++ <a name="Cpp"></a>
    - ### - Language: Collections -
        - :books: [Awesome C++](https://github.com/fffaraz/awesome-cpp#readme) : A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. 
        - :books: [Awesome C++ Game Dev](https://github.com/Caerind/AwesomeCppGameDev#readme) : A curated list of awesome C++ (mainly) things for Game Development.
    - ### Game Engine
        - :tada: [Cocos2d-x](https://www.cocos.com/en/cocos2dx) [:octocat:](https://github.com/cocos2d/cocos2d-x) : Provides rendering, gui, audio, network, physics, user input, etc. Widely used in game development and application construction.
        - :tada: [Defold](https://defold.com) [:octocat:](https://github.com/defold/defold) : Open sourced by King. Free to use game engine for development of desktop, mobile and web games.
        - :tada: [LOVE](https://love2d.org) [:octocat:](https://github.com/love2d/love) : LÖVE is an awesome 2D game framework for writing game code with Lua.
        - :tada: [ORX](http://orx-project.org) [:octocat:](https://github.com/orx/orx) : Orx is a 2.5D data-driven game development engine.
        - :tada: [Panda3D](https://www.panda3d.org) [:octocat:](https://github.com/panda3d/panda3d) : Powerful, mature cross-platform game engine for Python and C++, developed by Disney and CMU.
        - :tada: [Solar2D](https://solar2d.com) [:octocat:](https://github.com/coronalabs/corona) : (Previously known as Corona) Focus on ease of iterations and usage.
    - ### Game Engine w/Editor
        - :tada: [Esenthel](https://esenthel.com/) [:octocat:](https://github.com/Esenthel/EsenthelEngine) : Cross-platform feature-packed open source engine. Easy to use. In development since the year 2000.
        - :tada: [Irrlicht](https://irrlicht.sourceforge.io) [:octocat:](https://sourceforge.net/projects/irrlicht/) : Cross-platform 3D engine written in C++ worked on for nearly 2 decades.
        - :tada: [Polycode](http://polycode.org/features/) [:octocat:](https://github.com/ivansafrin/Polycode) : Cross-platform framework for creative code. Nice editor.
        - :tada: [Torque 3D](https://torque3d.org/torque3d/) [:octocat:](https://github.com/GarageGames/Torque3D) : High performance 3D engine.
        - :lock: [UPBGE](https://upbge.org) [:octocat:](https://github.com/UPBGE/upbge) : Blender game engine. Forked from [Blender](https://www.blender.org).
    - ### Graphics
        - :tada: [Ogre](https://www.ogre3d.org) [:octocat:](https://github.com/OGRECave/ogre) : Scene-oriented, flexible 3D engine.
    - ### Graphics w/Editor
        - :tada: [Horde3D](http://www.horde3d.org) [:octocat:](https://github.com/horde3d/Horde3D) : 3D rendering and animation engine. [Scene Editor Info](http://horde3d.org/wiki/index.php?title=Horde3D_Scene_Editor).
- ### C# <a name="CSharp"></a>
    - ### - Language -
    - ### Game Engine
        - :tada: [MonoGame](https://www.monogame.net) [:octocat:](https://github.com/MonoGame/MonoGame) : Framework for creating powerful cross-platform games in C#.
    - ### Game Engine w/Editor
        - :tada: [Stride](https://stride3d.net) [:octocat:](https://github.com/stride3d/stride) : (formerly Xenko) C# game engine for realistic rendering and VR.
- ### Haxe
    - ### - Language -
        - :tada: [Haxe](https://haxe.org) [:octocat:](https://github.com/HaxeFoundation/haxe) : Official site. Very cool programming language used to produce cross-platform native code.
        - :books: [Haxelibs](https://lib.haxe.org/all) : A list of every library uploaded to Haxe's website.
        - :books: [haxetink](https://github.com/haxetink) : Various add-on libraries for Haxe.
        - :books: [Snowkit](http://snowkit.org) [:octocat:](https://github.com/snowkit) : A collective of Haxe developers.
    - ### - Language: Articles -
        - :books: [Flash is dead, long live OpenFL](https://web.archive.org/web/20201112021925/https://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
        - :books: [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
    - ### - Language: Collections -
        - :books: [Awesome Haxe](https://github.com/nadako/awesome-haxe#readme) : Awesome curated list of useful Haxe links.
        - :books: [Awesome Haxe Game Dev](https://github.com/Dvergar/awesome-haxe-gamedev#readme) : Awesome list of game dev resources for Haxe.
    - ### Animation
        - :tada: [Actuate](https://github.com/jgranick/actuate) : Flexible, fast "tween" library.
        - :tada: [openfl/DragonBones](https://github.com/openfl/dragonbones) : Runtime support for [DragonBones](https://www.dragonbones.com) skeletal animation.
        - :tada: [spine-hx](https://github.com/jeremyfa/spine-hx) : [Spine](https://esotericsoftware.com) runtime for Haxe.
    - ### Application
        - :tada: [HashLink](https://hashlink.haxe.org) [:octocat:](https://github.com/HaxeFoundation/hashlink/) : Virtual machine for Haxe.
        - :tada: [hexMachina](http://hexmachina.org) [:octocat:](https://github.com/DoclerLabs/hexCore) : Powerful modular MVC framework written in Haxe.
        - :tada: [Lime](https://lime.software) [:octocat:](https://github.com/haxelime/lime) : A flexible, lightweight layer for Haxe cross-platform developers.
        - :tada: [nme](https://github.com/haxenme/nme) : Cross-platform native backend for Haxe projects.
    - ### Entity Component System
        - :tada: [ecx](https://github.com/eliasku/ecx) : Entity Component System framework for Haxe.
        - :tada: [GASM](https://github.com/HacksawStudios/GASM) : Framework agnostic Entity Component System for Haxe.
    - ### Game Engine
        - :tada: [Citrus](http://citrusengine.com) [:octocat:](https://github.com/DaVikingCode/Citrus-Engine) : 2D and 3D ActionScript 3 based engine.
        - :tada: [Clay](https://github.com/clay2d/clay) : Cross-platform 2d game framework.
        - :tada: [HaxeFlixel](https://haxeflixel.com) [:octocat:](https://github.com/HaxeFlixel/flixel) : Cross-platform 2D game engine powered by Haxe and OpenFL.
        - :tada: [OpenFL](https://www.openfl.org) [:octocat:](https://github.com/openfl/openfl) : For creative expression on the web, desktop, mobile and consoles.
    - ### Game Engine w/Editor
        - :tada: [Armory](https://armory3d.org) [:octocat:](https://github.com/armory3d/armory) : 3D game engine with full Blender integration.
        - :tada: [Away3D](https://www.away3d.com) [:octocat:](https://github.com/openfl/away3d) : Real-time 3D engine for OpenFL.
        - :tada: [flixel-studio](https://github.com/Dovyski/flixel-studio) : Embeddable, in-game editor for [HaxeFlixel](https://haxeflixel.com).
        - :tada: [Hide](https://github.com/heapsio/hide) : Extensible IDE for [Heaps](https://heaps.io).
        - :tada: [LDtk](https://ldtk.io) [:octocat:](https://github.com/deepnight/ldtk) : Very cool modern, lightweight and efficient 2D level editor.
        - :tada: [Starling](https://gamua.com/starling/) [:octocat:](https://github.com/openfl/starling) : Popular Stage3D framework.
    - ### Graphics
        - :tada: [Heaps](https://heaps.io) [:octocat:](https://github.com/HeapsIO/heaps) : High-performance cross-platform graphics engine by the creators of [Haxe](https://haxe.org).
        - :tada: [Kha](https://kha.tech) [:octocat:](https://github.com/Kode/Kha) : Ultra-portable, high performance, open source multimedia framework.
        - :tada: [Sparkler](https://github.com/AndreiRudenko/sparkler) : Modular Macro-powered Particle System.
    - ### Gui
        - :tada: [HaxeUI](http://haxeui.org) [:octocat:](https://github.com/haxeui/haxeui-core) : Cross-platform set of styleable application centric, rich UI components.
    - ### Physics
        - :tada: [Haxe Bullet](https://github.com/armory3d/haxebullet) : Bullet 3D Physics bindings for Haxe.
        - :tada: [HeapsIO/bullet](https://github.com/HeapsIO/bullet) : Bullet 3D Physics for Heaps (Haxe's native low-level game framework).
        - :tada: [Jelly Physics](https://github.com/michaelapfelbeck/jellyPhysics) : Soft body physics engine.
        - :tada: [Nape](https://joecreates.github.io/napephys/) [:octocat:](https://github.com/HaxeFlixel/nape-haxe4) : Very impressive powerful, fast, and friendly 2D Rigid Body physics engine.
    - ### Serialization / Storage
        - :tada: [CastleDB](https://github.com/ncannasse/castle) : Structured database with a local web service to edit it.
        - :tada: [Format](https://github.com/HaxeFoundation/format) : Various files formats support for Haxe.
        - :tada: [HxBit](https://github.com/HeapsIO/hxbit) : Binary serialization and network synchronization library.
    - ### Utility
        - :tada: [hxColorToolkit](https://github.com/andyli/hxColorToolkit) : Library for color conversion and color scheme generation.
        - :tada: [HxMath](https://github.com/tbrosman/hxmath) : Game-oriented math library for the Haxe language.
        - :tada: [nxColor](https://github.com/oscarcs/nxColor) : Color manipulation library.
        - :tada: [SteamWrap](https://github.com/larsiusprime/SteamWrap) : Haxe native extension for the Steam API.
    - ### Visual Scripting
        - :tada: [haxe-blockly](https://github.com/nickmain/haxe-blockly) : Haxe wrapper for [Blockly](https://developers.google.com/blockly)
- ### Java
    - ### Game Engine, Low-Level
        - :tada: [libGDX](https://libgdx.com) [:octocat:](https://github.com/libgdx/libgdx) : Cross-platform Java game development framework. [[Awesome libGDX](https://github.com/rafaskb/awesome-libgdx#readme)]   
- ### Javascript
    - ### Game Engine
        - :tada: [GDevelop](https://gdevelop-app.com) [:octocat:](https://github.com/4ian/GDevelop) : A 2D full-featured, open-source game development software platform.
        - :tada: [Phaser](https://phaser.io) [:octocat:](https://github.com/photonstorm/phaser) : Fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supports Canvas and WebGL.
        - :tada: [Turbulenz](http://biz.turbulenz.com/developers) [:octocat:](https://github.com/turbulenz/turbulenz_engine) : Modular 2D / 3D game framework for making HTML5 powered games for browsers, desktops and mobile devices.
    - ### Game Engine w/Editor
        - :tada: [A-Frame](https://aframe.io) [:octocat:](https://github.com/aframevr/aframe/) : Web framework for building 3D virtual reality (VR) experiences.
        - :tada: [Cocos Creator](https://www.cocos.com/en/creator) [:octocat:](https://github.com/cocos-creator/engine) : A Cross-Platform 2D / 3D Game Creation Tool
        - :tada: [Pixelbox.js](https://pixwlk.itch.io/pixelbox) [:octocat:](https://github.com/cstoquer/pixelbox) : Sandbox framework to fast-prototype 2D tile-based games in HTML5 and JavaScript. [Editor](https://pixwlk.itch.io/pixelbox)
    - ### Graphics
        - :tada: [LUME](https://lume.io) [:octocat:](https://github.com/lume/lume) : Toolkit that simplifies the creation of interactive 2D / 3D experiences for any device from mobile to desktop to AR/VR.
    - ### Graphics w/Editor
        - :tada: [Babylon.js](https://www.babylonjs.com) [:octocat:](https://github.com/BabylonJS/Babylon.js) : One of the most powerful, beautiful, and simple Web rendering engines in the world.
        - :tada: [CopperLicht](http://ambiera.com/copperlicht/) : Commercial grade open source 3D JavaScript library for WebGL. [[CopperCube Editor](http://ambiera.com/coppercube/index.html)]
        - :tada: [Three.js](https://threejs.org) [:octocat:](https://github.com/mrdoob/three.js/) : :fire: Easy to use, lightweight, cross-browser, general purpose 3D library. [[Scene Editor](https://threejs.org/editor/) | [Examples](https://threejs.org/examples/)]
        - ### Three.js Reference
            - :books: [SBcode Three.js Tutorials](https://sbcode.net/threejs/) - Fantastic examples with code and explanations of topics from beginner to advanced.
            - :tada: [Stemkoski Three.js Examples](http://stemkoski.github.io/Three.js/) - Excellent set of instructive examples with well commented source code.
            - :books: [Three.js Bookshelf](https://discourse.threejs.org/t/three-js-bookshelf/2468) - Great collection of resources for [Three.js](https://threejs.org).
            - :books: [Three.js Discourse Examples](https://hofk.de/main/discourse.threejs/) - Yearly collection of all examples with source posted on the [Three.js](https://threejs.org) forum
            - :books: [Three.js Manual](https://threejs.org/manual/#en/fundamentals) - (formerly threejsfundamentals) Great info on [Three.js](https://threejs.org) and 3D engines and how they work in general.
- ### Python
    - ### Gui
        - :tada: [Kivy](https://kivy.org/) [:octocat:](https://github.com/kivy/kivy) : Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS.

<br>

## Tools
- ### Animation
- ### Color
- ### Drawing
- ### Game Dev
- ### Image Editors
- ### Materials
- ### Modeling
- ### Particles
- ### Pixel Art
- ### Sound
- ### Textures

<br>

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
