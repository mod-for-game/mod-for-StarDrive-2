# mod-for-StarDrive-2
# 游戏最新消息
2021年游戏组似乎想起来了游戏，重新开始更新补丁，而且几天一个，让人感动。

另外游戏的原画册实际上很漂亮。
# 游戏读取机制

游戏第一次运行后会复制基本文件进appdata里面，所以存档中的读取都是C:\Users\wwwfe\AppData\LocalLow\Zero Sum Games\StarDrive 2里面的内容。所以我们如果运行过游戏，修改的时候都是再C:\Users\wwwfe\AppData\LocalLow\Zero Sum Games\StarDrive 2里面内容。推荐安装everything软件进行搜索。

everything软件下载链接https://www.voidtools.com/

**小技巧**：everything除了搜索文件名称，可以搜索png等格式，还可以根据时间找出网页缓存和游戏地图缓存。

# 游戏问题
因为全科技之后，ai会建造一些糟糕的建筑，所以无法托管。

后期过回合没有事情，但是事件弹窗会卡死游戏（游戏近期恢复维护已经把弹窗放入事件窗，只显示数量，但是还是没法看过去点掉的事件，有时候不小心点了还没看事件的内容）

后期大舰队交战很卡，不要太多舰队超过250点，如果里面都是航母战群就更卡了。

这并不能怪游戏开发商，毕竟不像群星和无尽空间限制了玩家舰队和星系数量。建议开非常富饶和中等星际大小就可以了。

有时候会有一些bug直接过回合或者读自动保存就行。一般是gui未关闭，还有就是陆战弹窗有时候会被其他弹窗打断，导致bug，之后就没法过回合了，只能读档重来。


# 游戏文件介绍

Techs里面是科技可以解锁自制的科技。

CustomRaces里面可以自定义一些都是优点的种族。可以先游戏里面自定义一个种族，再在这里删除种族的缺点。

Buildings里面可以自定义建筑。

leader里面可以自定义一些领导人。

Modules里面是舰船模块的贴图。里面的Module Headers是每个模块的数值；Module Sets是每种模块的显示，因为有些模块可以有多种格子的变种；Textures是舰船模块贴图，有一些没有被使用的贴图（或者可能是任务里面使用的舰船）（任务我没玩，太难了）（好像是1代废弃的舰船模块贴图）可以使用作为新mod模块，或者自己PS图片也可以。

# 关于舰船模型的修改

需要使用unity3d打开，可以从steam创意工坊订阅星球大战那些mod并修改研究。未尝试过。
