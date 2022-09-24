## Why is this forked?

Well, simply because 2LStudios removed permanent links. I've added them back temporarily (until 2LS re-add the permalinks themselves) using nightly.link and Github Workflows.

You can find them below:

|     |
|---|
| **[JDK 8 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK8.zip)**  |
| **[JDK 11 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK11.zip)** | 
| **[JDK 17 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK17.zip)** | 

**Edit:** Seems [FlameCord Jenkins](https://ci.2lstudios.dev/job/FlameCord/) is back, although I'm not sure when that came around again. At the time of writing this the last build on their Jenkins was in July (v1.0.5), whilst these builds are the latest (v1.1.3). I'd recommend going with the latter and downloading the latest from here, but it's up to you.

---

FlameCord
=======

FlameCord is a Waterfall modification to fix exploits, improve performance and protect against bot attacks. Waterfall is a fork of the well-known [BungeeCord](https://github.com/SpigotMC/BungeeCord) server teleportation suite.

FlameCord is compiled like Waterfall does; Please follow the [CONTRIBUTING.md](https://github.com/2lstudios-mc/FlameCord/blob/master/CONTRIBUTING.md) file. If you need help you can always contact us on Discord.

<a href="https://discord.gg/gF36AT3"><img src="https://i.imgur.com/NyGBnuJ.png" width=10% height=10%><img/><a/> <a href="https://www.mc-market.org/resources/13492/"><img src="https://i.imgur.com/KLOpbAF.png" width=10% height=10%><img/><a/> <a href="https://ci.2lstudios.dev/job/FlameCord"><img src="https://i.imgur.com/lOUkJji.png" width=10% height=10%><img/><a/>

## Features

FlameCord being a fork of Waterfall, has all its features, and some of its own, such as:

* **Exploit Fixes**: FlameCord specializes in providing better server security by fixing major exploits, performance flaws and bugs that Bungeecord already has, and that have not yet been fixed in WaterfallMC.
* **Bot Protection**: FlameCord brings swift bot protection for your Minecraft server to avoid extra CPU usage and crashes in your machines.

## Why fork Waterfall?

FlameCord was forked out of a desire for greater protection to be afforded to a Bungeecord-based proxy, which Waterfall currently cannot offer.

FlameCord will track upstream Waterfall and merge changes as needed.

## How to (Server Admins)

You can support the development of FlameCord by purchasing it at [MC-Market](https://www.mc-market.org/resources/13492/).

FlameCord requires **Java 8** or above.

## How To (Compiling from source)

To compile FlameCord, you need JDK8 or above, git, bash, maven, and an internet connection.

Clone this repo, run `./flamecord b` from *bash*, get jar from `FlameCord-Proxy/bootstrap/target`

## Join us

* Feel free to open a PR! We accept contributions.
* Join to our [Discord Server](https://discord.gg/gF36AT3).
