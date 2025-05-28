# [Minecraft](https://www.minecraft.net/)
[Wikipedia](https://en.wikipedia.org/wiki/Minecraft)

[一篇萌新向的Minecraft入坑指南 - 青雨染蓑衣的个人小站](https://minetest.top/archives/1703557604183)

## Launchers
- Official

- [MultiMC](https://multimc.org/)
  - C++

  [强大的 Minecraft 启动器：MultiMC - 少数派](https://sspai.com/post/47690)

  - [Prism Launcher](https://prismlauncher.org/) ([GitHub](https://github.com/PrismLauncher/PrismLauncher))

    > Prism Launcher can download from both CurseForge and Modrinth, is free and open source, automatically installs everything needed including Java, and is very fast and lightweight. It’s objectively a very good, if not the best mod manager.

    [【心得】Prism Launcher - 輕量化、高性能的 Minecraft 啟動器 @Minecraft 我的世界（當個創世神） 哈啦板 - 巴哈姆特](https://forum.gamer.com.tw/C.php?bsn=18673&snA=197823)

    - `scoop install games/prismlauncher`
      - `~\scoop\persist\prismlauncher`
      - `accounts.json` and `java` are not persited
    - Licesning
      - [Diegiwg/PrismLauncher-Cracked: This project is a Fork of Prism Launcher, which aims to 'unblock' the use of Offline Accounts, disabling the restriction of having a functional Online Account. No other modifications were applied to the project's source code.](https://github.com/Diegiwg/PrismLauncher-Cracked)
      - [antunnitraj/Prism-Launcher-PolyMC-Offline-Bypass: Bypass check if user has a real Microsoft MSA account linked with the Minecraft Launchers PrismLauncher, Prism Launcher](https://github.com/antunnitraj/Prism-Launcher-PolyMC-Offline-Bypass)
        - `echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "MSA"}],"formatVersion": 3} > accounts.json`

      [Is prism launcher cracked safe? : r/MinecraftMod](https://www.reddit.com/r/MinecraftMod/comments/14cs1f7/is_prism_launcher_cracked_safe/)
    - Cannot create an instance with a mod and its compatible MC version and loader

- Modrinth App ([GitHub](https://github.com/modrinth/code))
  - Rust, Tauri

  [What is Modrinth and how does it compare to CurseForge? : r/feedthebeast](https://www.reddit.com/r/feedthebeast/comments/1belgwf/what_is_modrinth_and_how_does_it_compare_to/)
- [CurseForge App - Mods, Addons and CC Manager](https://www.curseforge.com/download/app)
  - C#, close source
- [Feed The Beast](https://www.feed-the-beast.com/) ([GitHub](https://github.com/FTBTeam/FTB-App))
  - Java, Electron, Vue
- [Technic Launcher](https://www.technicpack.net/) ([GitHub](https://github.com/TechnicPack/TechnicLauncher))
  - Java

- [HMCL-dev/HMCL: A Minecraft Launcher which is multi-functional, cross-platform and popular](https://github.com/HMCL-dev/HMCL)
  - Java, Chinese
- [Voxelum/x-minecraft-launcher: An Open Source Minecraft Launcher with Modern UX. Provides a Disk Efficient way to manage all your Mods!](https://github.com/Voxelum/x-minecraft-launcher) (XMCL)
  - TS, Vue, Chinese
- [Hex-Dragon/PCL2: Minecraft 启动器 Plain Craft Launcher（PCL）。](https://github.com/Hex-Dragon/PCL2)
  - VB.NET, 仅部分开源, Chinese

Discussions:
- 2019-09 [Best mod manager? : r/Minecraft](https://www.reddit.com/r/Minecraft/comments/dawzh5/best_mod_manager/)
- 2023-08 [Best Mod mannager? : r/Minecraft](https://www.reddit.com/r/Minecraft/comments/15whlt9/best_mod_mannager/)
- 2023-09 [Which Minecraft launcher do you use and why do you? : r/Minecraft2](https://www.reddit.com/r/Minecraft2/comments/16ry0wd/which_minecraft_launcher_do_you_use_and_why_do_you/)
- 2024-01 [Which MC Launcher for Modpacks? : r/feedthebeast](https://www.reddit.com/r/feedthebeast/comments/19chiif/which_mc_launcher_for_modpacks/)
- 2025-02 [What's the best MC mod manager? : r/Minecraft](https://www.reddit.com/r/Minecraft/comments/1ilfipr/whats_the_best_mc_mod_manager/)

[网上的各种Minecraft启动器的差别是什么? - 知乎](https://www.zhihu.com/question/308489359)

[你应该用什么启动器？ - What\_Damon的窝](https://damon233.js.org/whichMCLauncherYouNeed/)

[你们觉得哪个MC启动器好？ - 百科杂谈 - MC百科社群 - MC百科|最大的Minecraft中文MOD百科](https://bbs.mcmod.cn/thread-13910-1-1.html)
> 用过 PCL2, HMCL 和 Prism Launcher (MultiMC fork 之一)，PCL2 操作比较简易，但 Mod 下载之类的需要手操；HMCL 的自动安装兼容性最好（可以直接装 CleanroomMC），但同样 Mod 管理比较麻烦；Prism 的话 Mod 管理最简单，看日志和调试也方便，但是目录结构并不是典型的 Minecraft 版本隔离，导入非标准整合包需要一些手工操作

[Prism Launcher最好的整合包启动器 - 哔哩哔哩](https://www.bilibili.com/opus/986156213824651285)

[各种MC第三方启动器介绍！ - 哔哩哔哩](https://www.bilibili.com/opus/734631534571552773)

## Modding
[Wikipedia](https://en.wikipedia.org/wiki/Minecraft_modding), [维基百科](https://zh.wikipedia.org/zh-cn/%E6%88%91%E7%9A%84%E4%B8%96%E7%95%8C%E6%A8%A1%E7%B5%84)

Loaders:
- Forge
  - [NeoForge](https://neoforged.net/) ([GitHub](https://github.com/neoforged/NeoForge))

  [写在前面：这是什么？ - Harbinger](https://harbinger.covertdragon.team/)
- [Fabric](https://fabricmc.net/) ([GitHub](https://github.com/FabricMC/fabric))
  - Quilt
- LiteLoader

[What's the "best" mod loader? : r/feedthebeast](https://www.reddit.com/r/feedthebeast/comments/18lkbjn/whats_the_best_mod_loader/)

[What mod loader would be the BEST to you? - Mods Discussion - Minecraft Mods - Mapping and Modding: Java Edition - Minecraft Forum - Minecraft Forum](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/mods-discussion/3199694-what-mod-loader-would-be-the-best-to-you)

### Compatibility
Shit official.

[Is it possible to create a version of minecraft compatible with all mods, no matter what version? : r/feedthebeast](https://www.reddit.com/r/feedthebeast/comments/117vzw3/is_it_possible_to_create_a_version_of_minecraft/)
> Minecraft has developed a type of modding API that abstracts very little, and gives mods the ability to modify any part of the game's code. With that type of API, it's not possible to make a multi version compatible system.
> 
> There are projects like [Universal Mod Core](https://www.curseforge.com/minecraft/mc-mods/universal-mod-core) that support a single API from 1.7.10 through to 1.16, but that type of API is usually more restrictive.

[\[Forge\]Minecraft Forge - MC百科|最大的Minecraft中文MOD百科](https://www.mcmod.cn/class/30.html)
> Forge 允许版本较旧的模组兼容版本更新的 Minecraft 及 Forge ，但是，通常仅限于小版本，比如 1.8.8 与 1.8.9。

[Question About Mod Version Compatibility - Mods Discussion - Minecraft Mods - Mapping and Modding: Java Edition - Minecraft Forum - Minecraft Forum](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/mods-discussion/3034462-question-about-mod-version-compatibility)
> Forge has to be ported over so not all features are there in every version, but Fabric more so has mods work throughout the entire version or even across versions like say 1.14 to 1.16 (due to how Fabric is designed where it doesn't need to be rebuild all the time) in the case of say a Dark Mode mod which is much more small and uses the case code probably across 1.14 and 1.16. It still comes down to what Mojang does between these versions but usually they work it out so it is available across all "point" versions if possible.

[Compatibility between versions of mods : r/Minecraft](https://www.reddit.com/r/Minecraft/comments/11a6iur/compatibility_between_versions_of_mods/)

[为什么游戏《Minecraft》（我的世界）中，mod（模组）不能跨版本或跨端（加载器）兼容？ - 知乎](https://www.zhihu.com/question/619259336)
> 我想基岩版就做得很好，基岩版的模组(行为包)可以跨版本兼容，而且不会出现重要的模组兼容问题。 Java版的数据包也一样，做得很好。但为什么基岩版的模组能跨版本兼容Java版却不行呢？
> 
> 基岩版行为包那是Mojang官方提供的接口，官方自然会顾及版本兼容的问题，不像Java版的模组加载器都是社区的作品，官方并不提供支持。相反，Java版的底层代码每个大版本之间区别较大（最近的例子：1.20把Material删了，给我升级SPM到1.20增加了不少工作量），模组加载器只能经常性更新代码，Mod也不得不跟随更新。

> 为什么大部分模组都在1.12.2 1.7.10 1.10.2 1.14.4 1.16.5 1.18.2 1.19.4等版本？
>
> 因为这些版本都是某个大版本的最后一个小版本，游戏相对稳定（不会有太严重的bug）。并且它们的后一个版本往往对游戏底层代码更改较大，升级困难，或者后一个版本时间间隔较大，给Mod充足的发展时间。
> 
> 如1.12.2后一个版本1.13，进行了扁平化，全面取消数字ID，对游戏底层代码进行了一次大规模重写。大规模的改动使得Mod不易更新（甚至Forge也花了相当多的时间更新1.13，这也是Fabric崛起的因素之一），造成1.12.2 Mod非常多，至今仍是受欢迎的版本之一。

> 我无法理解，哪怕官方吸收一些mod，也好过隔三岔五做这些没啥用的更新。mc和p 是我印象里最差的mod管理者，他们都很擅长忽略玩家诉求。

[为什么Minecraft（我的世界）的模组很难跨版本？ - 知乎](https://www.zhihu.com/question/317047632)

## Mods
Websites:
- [Modrinth](https://modrinth.com/)
- [CurseForge](https://www.curseforge.com/minecraft)

  [Minecraft's Most Important Mod Is In DANGER](https://www.youtube.com/watch?v=Vhdwz5apiQQ)
  > greed ruins everything, sadly.
- [Minecraft Forum](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods)

[What's the best website to get mods for Minecraft Java? : r/feedthebeast](https://www.reddit.com/r/feedthebeast/comments/j05eee/whats_the_best_website_to_get_mods_for_minecraft/)
> Almost* all of the mods on modrinth are targeting fabric. Modrinth has the biggest Fabric Mod Librarie.

Modpacks:
- [Cobblemon](https://cobblemon.com/)
  - [Pokemon Elysium - Minecraft Modpack](https://modrinth.com/modpack/pokemon-elysium)

Mods:
- [Plants vs. Zombies: Cubed - Minecraft Mod](https://modrinth.com/mod/pvzcubed)
  - Quilt

[【情報】最佳化模組整合文【1.19 / 1.18.2 / 1.16.5】全新記憶體流失修復模組！6/12 更新 @Minecraft 我的世界（當個創世神） 哈啦板 - 巴哈姆特](https://forum.gamer.com.tw/C.php?bsn=18673&snA=188995&to=18)

[【情報】【1.17.1】模組整合文 連接材質、動態光源 應有盡有！9/26 小更新 @Minecraft 我的世界（當個創世神） 哈啦板 - 巴哈姆特](https://forum.gamer.com.tw/C.php?bsn=18673&snA=191506)

## Commands
[Commands -- Minecraft Wiki](https://minecraft.fandom.com/wiki/Commands)

[Argument types -- Minecraft Wiki](https://minecraft.fandom.com/wiki/Argument_types)
- [Coordinates -- Minecraft Wiki](https://minecraft.fandom.com/wiki/Coordinates#Commands)
  - > pressing `F3` can also replace the crosshair with a display of these three directions: +X in red, +Y in green, +Z in blue (eastward, upward, and southward, respectively).
  - Under feet: `~ ~-1 ~`
  - Local coordinate looks nice, but hard to use due to not orthogonal
- [Resource location -- Minecraft Wiki](https://minecraft.fandom.com/wiki/Resource_location)

  [How to give certain types of wood through commands. : r/MinecraftCommands](https://www.reddit.com/r/MinecraftCommands/comments/gcsdm9/how_to_give_certain_types_of_wood_through_commands/)

Commands:
- [/fill](https://minecraft.fandom.com/wiki/Commands/fill)
  - `/fill ~-3 ~-3 ~-3 ~3 ~-1 ~3 water`
  - `/fill ~ ~ ~ ^1 ^ ^10 water`

  [How do i use the /fill command? : r/Minecraft](https://www.reddit.com/r/Minecraft/comments/gtrj4m/how_do_i_use_the_fill_command/)
