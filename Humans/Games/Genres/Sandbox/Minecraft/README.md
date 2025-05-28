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
