# Editor

This is a proof of concept plugin editor for Endless Sky. It is still in alpha. Current features:

- Create, load and save plugins
- Doesn't mess up your plugin structure (if system X is in X.txt and system Y in Y.txt it will respect that).
- Have a look at the list below to see what you can edit.

You can build this editor like the main game or use the CD generated artifacts for your OS.

Checklist:

- [x] Systems can be fully edited
	- [x] Better visual editing in the map panel
- [x] Planets can be fully edited
- [x] Outfits can be fully edited
- [ ] Ships can be fully edited
- [ ] Governments can be fully edited
- [ ] Hazards can be fully edited
- [ ] Fleets can be fully edited
- [ ] Outfitter can be fully edited
- [ ] Shipyards can be fully edited
- [ ] ...

------

# Endless Sky

Explore other star systems. Earn money by trading, carrying passengers, or completing missions. Use your earnings to buy a better ship or to upgrade the weapons and engines on your current one. Blow up pirates. Take sides in a civil war. Or leave human space behind and hope to find some friendly aliens whose culture is more civilized than your own...

------

Endless Sky is a sandbox-style space exploration game similar to Elite, Escape Velocity, or Star Control. You start out as the captain of a tiny space ship and can choose what to do from there. The game includes a major plot line and many minor missions, but you can choose whether you want to play through the plot or strike out on your own as a merchant or bounty hunter or explorer.

See the [player's manual](https://github.com/endless-sky/endless-sky/wiki/PlayersManual) for more information, or the [home page](https://endless-sky.github.io/) for screenshots and the occasional blog post.

# Installing the game
Official releases of Endless Sky are available on [Steam](https://store.steampowered.com/app/404410/Endless_Sky/) and as direct downloads from [GitHub](https://github.com/endless-sky/endless-sky/releases). A PPA is available for [Ubuntu](https://launchpad.net/~mzahniser/+archive/ubuntu/endless-sky) and for [Debian](https://packages.debian.org/source/sid/endless-sky). Other package managers may also include the game, though the specific version provided may not be up-to-date.

### System Requirements
Endless Sky has very minimal system requirements, meaning most systems should be able to run the game. The most restrictive requirement is likely that your device must support at least OpenGL 3.

|| Minimum | Recommended |
|---|----:|----:|
|RAM | 350 MB | 750 MB |
|Graphics | OpenGL 3.0 | OpenGL 3.3 |
|Storage Free | 120 MB | 300 MB |

### Building from source
Most development is done on Linux and Windows, using the [SCons](https://scons.org/) build tool to compile the project. For those wishing to use an IDE, project files are provided for [XCode](https://developer.apple.com/xcode/) and [Code::Blocks](https://www.codeblocks.org/) to simplify the project setup. It is possible to use other IDEs or build systems to compile the game, but support is not provided.  
For full installation instructions, consult the [Build Instructions](https://github.com/endless-sky/endless-sky/wiki/BuildInstructions) wiki page. Some additional information may be found in the "readme-developer" text file.

# Contributing
As a free and open source game, Endless Sky is the product of many peoples' work. Contributions of artwork, storylines, and other writing are most in-demand, though there is a loosely defined [roadmap](https://github.com/endless-sky/endless-sky/wiki/DevelopmentRoadmap). Those who wish to contribute are encouraged to review the [wiki](https://github.com/endless-sky/endless-sky/wiki), and to post in the [community-run discord](https://discord.gg/ZeuASSx). Those who prefer to use Steam can use its [discussion rooms](https://steamcommunity.com/app/404410/discussions/) as well.

Endless Sky's main discussion and development area was once [Google Groups](https://groups.google.com/g/endless-sky), but due to factors outside our control, it is now inaccessible to new users.

# Licensing
Endless Sky is a free, open source game. The [source code](https://github.com/endless-sky/endless-sky/) is available under the GPL v3 license, and all the artwork is either public domain or released under a variety of Creative Commons licenses. (To determine the copyright status of any of the artwork, consult the [copyright file](https://github.com/endless-sky/endless-sky/blob/master/copyright).)
