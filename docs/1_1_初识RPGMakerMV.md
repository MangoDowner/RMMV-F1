#初识 RPG Maker MV

## 主要功能

### 支持格式
用户期盼已久的RPG制作大师Mac版终于推出！软件的整体界面也针对Mac做出了调整，用户将能在熟悉的界面上制作游戏
![](../inc/img/01_01_01_01_img01.png)
#### 支持多种输出格式
本作的游戏将输出为 HTML5 格式，使用这一格式，完成的游戏将可以发布在 Windows、Mac OS X、安卓、iOS平台，甚至作为网页游戏在线发布。
更多信息请参考 [输出格式] 部分。
![](../inc/img/01_11_04_img01.png)

### 地图
#### 更丰富的世界
游戏分辨率从 544x416 扩展到了 816x624。
#### 区域编辑功能强化
您可以使用地图着色工具进入区域编辑模式。区域的最大数量则从63增加至了255，
现在，您将可以编辑区域的更多细节。
#### 地图保存成图片
在地图列表中右键选择[Save as Image]将能够把您的地图保存成图片。
![](../inc/img/01_01_01_02_img04.png)

### 插件脚本
传统的脚本编辑器已经移除，取而代之的将是一个更简单的脚本管理工具。

在新工程中已经预置了一部分官方脚本，您可以直接使用。

更多的内容请参考 [开启脚本] 以及 [使用官方脚本] 
![](../inc/img/01_01_01_03_img01.png)

> 另外， [脚本规格] 部分包含了脚本相关规格的说明。

### 数据库
包括游戏角色、物品、技能与魔法在内游戏主要的数据都能在数据库中编辑和管理。
#### 增加数据库最大值
数据库内容的最大值已经增加。现在，技能、物品、武器、防具、敌人和敌群数据最多都将达到``2000``条。
#### 简单而又强大的功能
+ 数据库的复制功能支持多选。
![](../inc/img/01_01_01_04_img01.png)
+ 之前只能通过脚本修改的提示文字也能通过 [用语] 部分修改。
![](../inc/img/01_01_01_04_img02.png)
+ 装备类型（手部装备，脚部装备等）现在可以通过 [属性] 部分进行增删。
![](../inc/img/01_01_01_04_img03.png)
+ 游戏中菜单部分显示的选项可以通过 [系统] 部分进行修改。
[物品] 部分可以设置 [物品类型] 为 [隐藏物品 A, B] 。

### 横版战斗
在保留了前作纵版战斗的基础上，现在还可以使用横版战斗模式。
![](../inc/img/01_01_01_05_img01.png)
#### 横版战斗需要设置的内容
需要使用横版战斗模式时，您需要额外进行以下的设置来定制角色以及画面的外观。

+ 系统: Use Side-view Battle
该选项打勾时，游戏中的战斗将使用横版战斗模式。
请查看数据库一节的: [系统设置] 部分来获取更多信息。
+ 系统: Magic Skills
在这里设置技能的类型以设置战斗时角色的咏唱动作。
请查看数据库一节的: [系统设置] 部分来获取更多信息
+ 系统: Attack Motions
设置各个属性技能攻击时播放的动画。
请查看数据库一节的: [系统设置] 部分来获取更多信息
+ 角色: Battler
设置角色在战斗时显示的图片。
请查看数据库一节的: [角色设置] 部分来获取更多信息。
+ 状态: Motion
设置角色在特定状态时显示的图片。
请查看数据库一节的: [状态设置] 部分来获取更多信息。
+ 状态: Overlay
设置角色在特定状态时显示在角色上方的图片。
请查看数据库一节的: [状态设置] 部分来获取更多信息。

### 事件
例如，当玩家与NPC对话或者打开一个宝箱时，一个事件便发生了。
![](../inc/img/01_01_01_06_img01.png)
#### 事件测试功能
不运行游戏即可方便地测试图片的显示、移动以及旋转。
![](../inc/img/01_01_01_06_img02.png)
![](../inc/img/01_01_01_06_img03.png)
#### 事件指令增加
事件指令增加了以下几条：
+ Actor: [Change Profile（更改角色说明）]
+ Actor: [Change TP（更改TP）]
+ System Settings: [Change Vehicle BGM（更改交通工具BGM）]
+ System Settings: [Change Defeat ME（更改战败ME）]
+ Battle: [Change Enemy TP（更改敌人TP）]
+ Advanced: [Plugin Commands（插件脚本指令）]
#### 显示选项功能强化
选项的最大个数从4个增加到了6个，你还可以设置选项窗口的位置和不透明度。
![](../inc/img/01_01_01_06_img04.png)

### 其他
#### 事件搜索
新增了事件搜索功能。 请参考 [使用辅助工具] 部分来获取更多的内容。
#### 声音设置部分新增声场设置
声音设置部分可以设置背景音乐（BGM）、背景声音（BGS）、音效（SE）的声场位置。

通过改变声场，您将能调整声音在扬声器左右声道的音量大小。
![](../inc/img/01_10_11_img01.png)

### 运行游戏
使用RMMV制作出来的游戏同样得到了增强
#### 主要特点
+ 您将可以通过拉伸窗口调整游戏画面的大小。
+ 按住确定键将能快速跳过事件。
+ 游戏菜单中新增了 [Option（设置）] 指令。
![](../inc/img/01_01_01_08_img01.png)
+ 相比前作，本作的战斗节奏加快。
+ 战斗过程中，选择指定角色时该角色的图像将会变亮。
+ 受到的伤害值将会直接显示在战斗画面中。
![](../inc/img/01_01_01_08_img02.png)
+ 敌人的状态图标将直接显示在其图像的上方。
![](../inc/img/01_01_01_08_img03.png)
+ 上一次使用的技能将被记忆。
+ 如果地图和战斗界面背景音乐相同时，背景音乐将会继续播放。
+ 游戏标题将保存在存档中，你可以根据游戏的进行在标题栏显示不同的标题。
+ 最大存档数目从16个增加至20个。
+ 编辑游戏目录下的CSS文件(/fonts/gamefont.css)即可**更换游戏的字体**。
> 要更换字体还需把字体文件复制到该目录下。
![](../inc/img/01_01_01_08_img04.png)
+ 在测试模式下，按F8可以打开开发者工具。
> 请参考 [如何使用开发者工具] 部分来获取更多信息。
![](../inc/img/01_01_01_08_img05.png)
+ 将游戏目录上传到服务器后您可以在线进行游戏。
> 请参考 [运行游戏所需的系统要求] 部分来获取更多信息。


## 系统要求
本作的配置需求如下：
### 操作系统
+ Windows 7/8/8.1/10 (32 位/64 位)
+ Mac OS X 10.10 及其更高版本
+ Debian 8 及其更高版本 (2017 年 3 月 21 日更新)
### CPU
Intel Core 2 双核或以上
### 内存
至少2GB
### 硬盘
至少 2GB 的空余硬盘空间
### 显卡
需要支持 OpenGL
### 显示器
1280×768 分辨率或更高
### 其他
+ 产品验证需要通过网络进行。
+ 顺畅游玩所需要的配置因作品内容而异。
+ Linux 系统请通过 Debian8 而非 SteamOS 来运行 RPG Maker MV。
	
