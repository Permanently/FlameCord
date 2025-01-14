## Why is this forked?

Originally, this was forked due to 2LStudios removing permanent links for downloads. However, recently they've also removed the free downloads and put the download links behind a BuiltByBit paywall. [linsaftw talks more about this here.](https://github.com/Permanently/FlameCord/commit/9f61fee97f1de2ed44965e6092bb9bf3dd117646#commitcomment-101015673) I've added them back for those who (unfortunately) are not able to support 2LStudios financially, as their licensing allows this. 

If you would like to support 2LStudios (I recommend it) then you may use the links on the original readme.md below this section.

You can find them below:

|  **[nightly.link permalinks](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master)**   |
|---|
| **[JDK 8 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK8.zip)**  |
| **[JDK 11 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK11.zip)** | 
| **[JDK 17 Build](https://nightly.link/Permanently/FlameCord/workflows/flamecord-build/master/FlameCord-JDK17.zip)** | 

**Edit:** Seems [FlameCord Jenkins](https://ci.2lstudios.dev/job/FlameCord/) is back, although I'm not sure when that came around again. At the time of writing this the last build on their Jenkins was in July (v1.0.5), whilst these builds are the latest (v1.1.3). I'd recommend going with the latter and downloading the latest from here, but it's up to you.

---

# FlameCord

FlameCord is a Waterfall fork or modification that adds antibot features, exploit prevention systems, performance improvements, removal of unused features, library updates and application layer ddos mitigation.

## Links

<a href="https://builtbybit.com/resources/13492/"><img src="https://archive.org/download/download-button-png/download-button-png.png" width=25% height=25%><img/><a/> <a href="https://discord.gg/gF36AT3"><img src="https://i.imgur.com/NyGBnuJ.png" width=25% height=25%><img/><a/>

## Features

FlameCord being a fork of Waterfall, has all its features, and some of its own, such as:

* **Exploit Fixes**: FlameCord specializes in providing better server security by fixing major exploits, performance flaws and bugs that Bungeecord already has, and that have not yet been fixed in WaterfallMC.
  
* **Antibot Features**: FlameCord brings swift bot protection for your Minecraft server to avoid extra CPU usage and crashes in your machines.

* **Performance Improvements**: FlameCord tries to improve performance by removing unused features and disabling exception logs.

## Why fork Waterfall?

FlameCord was forked out of a desire for greater protection to be afforded to a Bungeecord-based proxy, which Waterfall currently cannot offer.

FlameCord will track upstream Waterfall and merge changes as needed.

## How to (Server Admins)

Just drag an drop FlameCord.jar into your server folder and run it.

You can customize many FlameCord features in the flamecord.yml file.

## How To (Compiling from source)

To compile FlameCord, you need JDK8 or above, git, bash, maven, and an internet connection.

Clone this repo, run `./flamecord b` from *bash*, get jar from `FlameCord-Proxy/bootstrap/target`

FlameCord is compiled like Waterfall does; Please follow the [CONTRIBUTING.md](https://github.com/2lstudios-mc/FlameCord/blob/master/CONTRIBUTING.md) file. If you need help you can always contact us on Discord.

## Contribute

* Feel free to open a PR! We accept contributions.
