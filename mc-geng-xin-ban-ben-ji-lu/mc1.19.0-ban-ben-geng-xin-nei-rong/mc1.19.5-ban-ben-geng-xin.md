# MC1.19.5版本更新

{% hint style="warning" %}
## 更新要点

**【更新】1.19.5版本补丁更新公告：BC1.19.5**

更新补丁版本：1.19.5

更新时间：2027-9-17

更新内容：
{% endhint %}

<details>

<summary><strong>新内容</strong></summary>

生物

[玩家](https://zh.minecraft.wiki/w/%E7%8E%A9%E5%AE%B6)

* 加入了7种新的默认[皮肤](https://zh.minecraft.wiki/w/%E7%9A%AE%E8%82%A4)：Makena、Efe、Noor、Kai、Ari、Sunny和Zuri。

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)

* 加入了“下一个主要更新”子选项。
  * 用于启用下一次主要更新的特性。

[选项](https://zh.minecraft.wiki/w/%E9%80%89%E9%A1%B9)

* 在轻触设置中加入了“选择控制模式”按钮，取代了之前版本的“启用新的触控方案”和“交互模型”选项。
  * 用于进入“控制模式”菜单，可修改所使用的触控设计：
    * “摇杆并点击进行互动”
    * “方向键并点击进行互动”
    * “摇杆并瞄准十字线”

[server.properties](https://zh.minecraft.wiki/w/Server.properties)

* 加入了enable-lan-visibility​服务器属性。
  * 用于启用与禁用服务器的显式局域网发现。

用户界面

* 加入了玩家将要丢失在[创建新的世界](https://zh.minecraft.wiki/w/%E5%88%9B%E5%BB%BA%E6%96%B0%E7%9A%84%E4%B8%96%E7%95%8C)界面做出的更改时出现的警告。

</details>

{% hint style="info" %}
服务器ID已经修复NJJK错误问题！
{% endhint %}

<details>

<summary><strong>更改</strong></summary>

方块

[泥巴](https://zh.minecraft.wiki/w/%E6%B3%A5%E5%B7%B4)和[灵魂沙](https://zh.minecraft.wiki/w/%E7%81%B5%E9%AD%82%E6%B2%99)

* 将方块高度降低至0.875格。

[结构方块](https://zh.minecraft.wiki/w/%E7%BB%93%E6%9E%84%E6%96%B9%E5%9D%97)

* 现在能够在Windows平台上导入.mcstructure​文件中的结构。

#### 生物 <a href="#sheng-wu" id="sheng-wu"></a>

[末影人](https://zh.minecraft.wiki/w/%E6%9C%AB%E5%BD%B1%E4%BA%BA)

* 将跟随范围由32格更改至64格。

[玩家](https://zh.minecraft.wiki/w/%E7%8E%A9%E5%AE%B6)

* 更改了Steve和Alex的默认皮肤。

[史莱姆](https://zh.minecraft.wiki/w/%E5%8F%B2%E8%8E%B1%E5%A7%86)和[岩浆怪](https://zh.minecraft.wiki/w/%E5%B2%A9%E6%B5%86%E6%80%AA)

* 现在能够攻击多个目标。
* 现在能够对[铁傀儡](https://zh.minecraft.wiki/w/%E9%93%81%E5%82%80%E5%84%A1)和[雪傀儡](https://zh.minecraft.wiki/w/%E9%9B%AA%E5%82%80%E5%84%A1)造成伤害。
* 现在每攻击一次会有0.5秒的冷却时间。

[恼鬼](https://zh.minecraft.wiki/w/%E6%81%BC%E9%AC%BC)

* 更改了模型和纹理。
  * 仍保留了比模型稍大一些的[判定箱](https://zh.minecraft.wiki/w/%E5%88%A4%E5%AE%9A%E7%AE%B1)，以便于其战斗。

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

[角色创建器](https://zh.minecraft.wiki/w/%E8%A7%92%E8%89%B2%E5%88%9B%E5%BB%BA%E5%99%A8)

* 加入了一个介绍新的Minecraft初始角色和使用这些角色作为外观的方式的新流程。

[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)

* 移除了“旁观模式”子选项。

[旁观模式](https://zh.minecraft.wiki/w/%E6%97%81%E8%A7%82%E6%A8%A1%E5%BC%8F)

* 现在开启作弊后，玩家可以在游戏设置中将个人游戏模式切换为旁观模式。
* 不再属于[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)。

[触摸控制](https://zh.minecraft.wiki/w/%E8%A7%A6%E6%91%B8%E6%8E%A7%E5%88%B6)

* 现在触控设备默认启用新的触摸控制。
* 优化了触摸控制下长按一组物品来将物品拆分的体验。
* 将拖拽物品前按住物品的停顿时长由120毫秒增加至180毫秒，以更轻松地滚动物品栏界面。
* 改进了新的触控模式下同时按下按钮并移动视角的方式。
* 移除了攻击和交互的操作延时。
* 将摇杆未被锁定时的可拖动范围更改为与摇杆被锁定时相同的可拖动范围。
  * 若已开启“自动冲刺”选项，将摇杆略微拖动到摇杆背景区域上方时会开始疾跑；将摇杆拖动回摇杆背景区域时则会停止疾跑。

键鼠控制

* 现在点击部分功能型方块（如[铁砧](https://zh.minecraft.wiki/w/%E9%93%81%E7%A0%A7)）使用界面的输出框时，输出的物品会直接进入玩家的物品栏。

用户界面

* 更改了复制世界的错误处理流程，现在会显示一个错误弹窗而不是弹出警告。
* 更改了“启用移动数据玩线上游戏”选项的文字颜色，以提升阅读体验。

#### 命令格式 <a href="#ming-ling-ge-shi" id="ming-ling-ge-shi"></a>

​/execute​

* 所有新的子命令不再属于[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

组件

* 为minecraft:variable\_max\_auto\_step​组件加入了新属性controlled\_value​。
  * 当拥有minecraft:input\_ground\_controlled​的生物被玩家控制时，该属性会覆写base\_value​属性。
  * 该属性的优先级低于jump\_prevented\_value​。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

常规

* 活动对象（实体）属性（包括Molang查询和属性过滤器，不包括置换）不再是实验性内容。
* 修复了刷怪蛋的texture\_index​超限时发生的崩溃。现在出现这种情况时会出现内容日志错误。
* 现在音效事件中设定的最大/最小衰减距离只会影响该事件，而不会影响其他使用该音效的事件。（[MCPE-154376](https://bugs.mojang.com/browse/MCPE-154376)）
* 向server.properties中加入了client-side-chunk-generation-enabled​布尔值设置。
* 修复了更改拥有子包的资源包的子包在重启游戏前不会应用更改的问题。（[MCPE-162002](https://bugs.mojang.com/browse/MCPE-162002)）
* 现在拥有相同输入材料和不同输出物品的配方会被标记为内容日志错误（合成配方和切石机配方除外）。

命令

* 使用/enchant​命令来为物品施加相同等级的魔咒不再会将增加魔咒等级。（[MCPE-153204](https://bugs.mojang.com/browse/MCPE-153204)）
* 修复了hasItem​过滤器在未提供数据值时无法正确侦测到带有相应数据值的物品的问题。（[MCPE-162460](https://bugs.mojang.com/browse/MCPE-162460)）
* 修复了延迟时间大于0时不会激活连锁型命令方块的漏洞。
* 现在执行/execute align xyz entity​命令时会产生错误信息，而不是导致崩溃。（[MCPE-162733](https://bugs.mojang.com/browse/MCPE-162733)）

数据驱动方块

* 开放了1.19.50及以上版本的实验性JSON格式中的BlockCollisionBoxComponent​。
* 开放了1.19.50及以上版本的实验性JSON格式中的BlockCraftingTableComponent​。
* 现在使用minecraft:crafting\_table​方块组件更改排列方式时，工作台UI会进行更新。
* 移除了minecraft:breathability​组件。该组件不会对已定义的自定义方块产生影响。

数据驱动物品

* 现在使用minecraft:placement\_filter​组件的方块会在因无法放置而被破坏时产生粒子效果、音效和振动事件。

网络

* 加入了服务器属性enable-lan-visibility​，用于启用与禁用服务器的显式局域网发现。禁用此项可以防止在同一主机上运行多个专用服务器时可能出现的端口冲突。明晰处理了端口在服务器日志中的使用情况，并使错误信息变得更加清晰。（[BDS-1094](https://bugs.mojang.com/browse/BDS-1094)）

AI意向

* 为minecraft:offer\_flower​AI行为公开了新的数据参数， 以指定生物献花的时间、开启意向的时间，以及用于搜寻被献花的生物的AABB​的维度。
* ​minecraft:offer\_flower​AI行为现在能够被任何生物使用，而非只能被铁傀儡使用。
* ​minecraft:offer\_flower​AI行为现在会搜寻指定范围内的所有生物，而不只是最近的生物，这意味着该意向可能会比以前更加始终如一地使用。
* 为minecraft:take\_flower​AI行为公开了新的数据参数，以指定开启意向所需满足的条件、拿走花前的最小和最大等待时间，以及用于搜寻被拿走花的生物的AABB​的维度。
* ​minecraft:take\_flower​AI行为现在能够被任何生物使用，而非只能被幼年村民使用。

生物

* 被玩家控制的input\_ground\_controlled​不再会增加自动步数。
  * 可改用variable\_max\_auto\_step​组件。使用"base\_value": 1.0625​和"jump\_prevented\_value": 0.5625​可与之前版本保持一致。

[Molang](https://zh.minecraft.wiki/w/Molang)

* 修复了has\_property​在属性存在时返回1，不存在时返回0，而不是在相反情况返回对应值的问题。

API

* 发布了@minecraft/server​1.0.0版本API，使用下列API时不需要再启用“测试版 API”选项。
  * ​System​
    * ​run()​
      * 用于在下一刻运行一个函数。
  * ​World​
    * ​getDimension()​
    * ​getAllPlayers()​
  * ​MinecraftDimensionTypes​
    * ​nether​
    * ​overworld​
    * ​theEnd​
  * ​Dimension​
    * ​id​
    * ​runCommandAsync()​
  * ​CommandResult​
    * ​commandresult​
  * ​Entity​
    * ​id​
    * ​typeId​
    * ​dimension​
    * ​runCommandAsync()​
  * ​Player​
    * ​name​

</details>

<details>

<summary><strong>实验性</strong></summary>

<mark style="color:green;">**本段落的内容需要开启**</mark>[<mark style="color:green;">**实验性玩法**</mark>](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)<mark style="color:green;">**中的“下一个主要更新”、“即将推出的创作者功能”和“测试版 API”子选项后才可使用。**</mark>

#### 方块 <a href="#fang-kuai" id="fang-kuai"></a>

[竹板](https://zh.minecraft.wiki/w/%E7%AB%B9%E6%9D%BF)

* 可由2×2的[竹子](https://zh.minecraft.wiki/w/%E7%AB%B9%E5%AD%90)合成。
* 功能与木板一致。
* 可用于合成对应的[楼梯](https://zh.minecraft.wiki/w/%E6%A5%BC%E6%A2%AF)、[台阶](https://zh.minecraft.wiki/w/%E5%8F%B0%E9%98%B6)、[按钮](https://zh.minecraft.wiki/w/%E6%8C%89%E9%92%AE)、[门](https://zh.minecraft.wiki/w/%E9%97%A8)、[栅栏](https://zh.minecraft.wiki/w/%E6%A0%85%E6%A0%8F)、[栅栏门](https://zh.minecraft.wiki/w/%E6%A0%85%E6%A0%8F%E9%97%A8)、[压力板](https://zh.minecraft.wiki/w/%E5%8E%8B%E5%8A%9B%E6%9D%BF)、[告示牌](https://zh.minecraft.wiki/w/%E5%91%8A%E7%A4%BA%E7%89%8C)和[活板门](https://zh.minecraft.wiki/w/%E6%B4%BB%E6%9D%BF%E9%97%A8)变种。

[竹马赛克](https://zh.minecraft.wiki/w/%E7%AB%B9%E9%A9%AC%E8%B5%9B%E5%85%8B)

* 可由纵向排列的1×2竹台阶合成。
* 可用于合成对应的[楼梯](https://zh.minecraft.wiki/w/%E6%A5%BC%E6%A2%AF)和[台阶](https://zh.minecraft.wiki/w/%E5%8F%B0%E9%98%B6)变种。

[雕纹书架](https://zh.minecraft.wiki/w/%E9%9B%95%E7%BA%B9%E4%B9%A6%E6%9E%B6)

* 最多可以存储6本书，可以是[书](https://zh.minecraft.wiki/w/%E4%B9%A6)、[书与笔](https://zh.minecraft.wiki/w/%E4%B9%A6%E4%B8%8E%E7%AC%94)、[成书](https://zh.minecraft.wiki/w/%E6%88%90%E4%B9%A6)或[附魔书](https://zh.minecraft.wiki/w/%E9%99%84%E9%AD%94%E4%B9%A6)。
* 可由6个木板和3个木台阶合成。
* 可以与[红石比较器](https://zh.minecraft.wiki/w/%E7%BA%A2%E7%9F%B3%E6%AF%94%E8%BE%83%E5%99%A8)交互，输出的红石信号强度为最后一次访问书的槽位位置。

[悬挂式告示牌](https://zh.minecraft.wiki/w/%E6%82%AC%E6%8C%82%E5%BC%8F%E5%91%8A%E7%A4%BA%E7%89%8C)

* 告示牌的变种，合成所需的材料更多。
  * 可由2个[锁链](https://zh.minecraft.wiki/w/%E9%94%81%E9%93%BE)和6个[去皮原木](https://zh.minecraft.wiki/w/%E5%8E%BB%E7%9A%AE%E5%8E%9F%E6%9C%A8)合成出6个悬挂式木告示牌，或由2个锁链和6个[竹板](https://zh.minecraft.wiki/w/%E7%AB%B9%E6%9D%BF)合成出2个悬挂式竹告示牌。
* 不能附在方块顶面，但可由以下方式悬挂起来：
  * 附着在可在中心处提供支撑点的方块底面，例如完整方块或栅栏。
  * 附着在方块的固体侧面，模型上会展现出一根横杆。
    * 放置后可不依赖于该固体侧面而独立存在。
  * 附着在其他悬挂式告示牌的侧面或底面。
* 可作为[熔炉](https://zh.minecraft.wiki/w/%E7%86%94%E7%82%89)燃料，每个能烧炼4个物品。

#### 物品 <a href="#wu-pin" id="wu-pin"></a>

[刷怪蛋](https://zh.minecraft.wiki/w/%E5%88%B7%E6%80%AA%E8%9B%8B)

* 加入了[骆驼](https://zh.minecraft.wiki/w/%E9%AA%86%E9%A9%BC)刷怪蛋。

#### 生物 <a href="#sheng-wu" id="sheng-wu"></a>

[骆驼](https://zh.minecraft.wiki/w/%E9%AA%86%E9%A9%BC)

* 每个[沙漠村庄](https://zh.minecraft.wiki/w/%E6%9D%91%E5%BA%84)中会自然生成一只。
* 有时会原地坐下。
* 可以通过[仙人掌](https://zh.minecraft.wiki/w/%E4%BB%99%E4%BA%BA%E6%8E%8C)繁殖。
* 可以装备[鞍](https://zh.minecraft.wiki/w/%E9%9E%8D)，供2名玩家骑乘。
  * 被骑乘时可以慢走和疾跑。也可以冲刺，但耐力会被消耗一段时间。
  * 在玩家骑乘时，身体高度不高于玩家身体高度的敌对生物无法近战攻击到玩家。

#### 非生物实体 <a href="#fei-sheng-wu-shi-ti" id="fei-sheng-wu-shi-ti"></a>

[船](https://zh.minecraft.wiki/w/%E8%88%B9)和[运输船](https://zh.minecraft.wiki/w/%E8%BF%90%E8%BE%93%E8%88%B9)

* 加入了竹筏和运输竹筏。
  * 合成时用竹板替代。
  * 与其他的木质变种功能一致，仅外观上有区别。

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

[声音](https://zh.minecraft.wiki/w/%E5%A3%B0%E9%9F%B3)

* 现在，各木种会在其被放置、破坏或在其上行走时有独特的音效。
  * 目前分为主世界木质、下界木质和竹质。
* 更改了下列音效以匹配[Java版](https://zh.minecraft.wiki/w/Java%E7%89%88)：
  * 木质[按钮](https://zh.minecraft.wiki/w/%E6%8C%89%E9%92%AE)的激活和取消激活音效
  * [门](https://zh.minecraft.wiki/w/%E9%97%A8)、[活板门](https://zh.minecraft.wiki/w/%E6%B4%BB%E6%9D%BF%E9%97%A8)和[栅栏门](https://zh.minecraft.wiki/w/%E6%A0%85%E6%A0%8F%E9%97%A8)的开关音效
  * 木质[压力板](https://zh.minecraft.wiki/w/%E5%8E%8B%E5%8A%9B%E6%9D%BF)的激活音效和取消激活音效
* 更改了测重压力板的激活和取消激活音效。
* 更改了[拉杆](https://zh.minecraft.wiki/w/%E6%8B%89%E6%9D%86)的开关音效。

控制器工具提示

* 加入了“放置书”控制器工具提示。
  * 当手持[书](https://zh.minecraft.wiki/w/%E4%B9%A6)、[书与笔](https://zh.minecraft.wiki/w/%E4%B9%A6%E4%B8%8E%E7%AC%94)、[成书](https://zh.minecraft.wiki/w/%E6%88%90%E4%B9%A6)或[附魔书](https://zh.minecraft.wiki/w/%E9%99%84%E9%AD%94%E4%B9%A6)的玩家看向未装满书本的[雕纹书架](https://zh.minecraft.wiki/w/%E9%9B%95%E7%BA%B9%E4%B9%A6%E6%9E%B6)时出现。
* 加入了“移除书”控制器工具提示。
  * 当玩家看向装有书本的雕纹书架时出现。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

脚本、API和GameTest框架

* 修复了velocity​属性在部分情况下会返回错误值的问题。（[MCPE-152715](https://bugs.mojang.com/browse/MCPE-152715)）
* 加入了canPlace​函数。
  * 用于返回在指定位置放置指定类型的方块或方块排列的有效性。
* 加入了trySetPermutation​函数。
  * 用于尝试在指定位置放置指定方块排列并根据canPlace​函数给出其结果。
* ​Entity​
  * 移除了runCommand​函数，可以使用runCommandAsync​达到相同功能。
* ​Dimension​
  * 移除了runCommand​函数，可以使用runCommandAsync​达到相同功能。
* 将BlockRaycastOptions​更改为接口。
* 将EntityEventOptions​更改为接口。
* 将ScoreboardObjectiveDisplayOptions​更改为接口。
  * 位置类型更改为IVec3
* ​Vector​
  * ​add​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​cross​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​distance​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​divide​
    * 更改了a​参数以接受IVec3接口类型。
  * ​lerp​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​max​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​min​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​multiply​
    * 更改了a​参数以接受IVec3接口类型。
  * ​slerp​
    * 更改了a​和b​参数以接受IVec3接口类型。
  * ​subtract​
    * 更改了a​和b​参数以接受IVec3接口类型

</details>

<details>

<summary><strong>修复</strong></summary>

原版趋同

* 生物
  * 现在幼年村民在玩耍时会以与Java版相匹配的速度更快地移动。
* 方块
  * 现在木门、铁门、木活板门、铁活板门和栅栏门使用与Java版一致的开关音效。
  * 更新了会根据行为发出不同音调的压力板以匹配Java版。
  * 为木质按钮加入了独有的激活音效以匹配Java版。
  * 现在绯红类和诡异类方块拥有独有的音效组。
  * 雕纹和切制红砂岩现在拥有平滑的底面。（[MCPE-20006](https://bugs.mojang.com/browse/MCPE-20006)）
  * 落在泥巴上的弹射物不再会反复抖动。（[MCPE-153744](https://bugs.mojang.com/browse/MCPE-153744)）
  * 泥巴旁的两栖生物不再会出现寻路问题。（[MCPE-153961](https://bugs.mojang.com/browse/MCPE-153961)）
  * 现在玩家放置出的泥巴和灵魂沙的边界框与视觉上的边界框相匹配。（[MCPE-162252](https://bugs.mojang.com/browse/MCPE-162252)）
  * 现在睡莲被船撞到时会发出音效和粒子效果。（[MCPE-65138](https://bugs.mojang.com/browse/MCPE-65138)）
  * 现在大多数因为没有支撑而被破坏的方块拥有视觉粒子、音频效果和引发振动的事件。
  * 珊瑚扇不再能够放置在台阶的侧面。（[MCPE-116986](https://bugs.mojang.com/browse/MCPE-116986)）
  * 珊瑚扇现在能够在玻璃之类的透明固体方块上存活。（[MCPE-112407](https://bugs.mojang.com/browse/MCPE-112407)）
  * 修复了即使选中光源方块时放置出的光源方块仍会不可见的漏洞。
* 旁观模式
  * 现在当玩家进入旁观模式时，容器、命令方块或结构方块界面会被正常关闭。
  * 旁观模式现在会在设置菜单中的个人游戏模式列表中显示。（[MCPE-156688](https://bugs.mojang.com/browse/MCPE-156688)）
  * 悦灵不再会向旁观模式玩家投掷物品。（[MCPE-162873](https://bugs.mojang.com/browse/MCPE-162873)）

性能与稳定性

* 修复了一些游戏过程中可能发生的崩溃。
* 修复了使用键盘滚动村民交易界面时可能发生的崩溃。
* 修复了末影龙的龙息攻击没能接触方块或落入虚空时发生的崩溃。（[MCPE-161204](https://bugs.mojang.com/browse/MCPE-161204)）
* 玩家物品栏中存在包含生物的物品（如装有蜜蜂的蜂箱）时，打开配方书不再会导致游戏性能显著下降。（[MCPE-146462](https://bugs.mojang.com/browse/MCPE-146462)）
* 修复了鼠标悬停在创造模式物品栏中的物品槽上时，游戏帧率会下降的问题。（[MCPE-162277](https://bugs.mojang.com/browse/MCPE-162277)）
* 修复了在没有开启教育版选项的情况下渲染教育版物品时发生的崩溃。（[MCPE-161587](https://bugs.mojang.com/browse/MCPE-161587)）
* 修复了不被玩家拥有的活动对象进入末地传送门时可能发生的崩溃。
* 修复了低内存设备上加载部分市场世界时可能导致游戏崩溃的问题。（[MCPE-161866](https://bugs.mojang.com/browse/MCPE-161866)）

游戏内容

* 地图上的黑色像素现在可以通过经过对应区域来修复。在之前的版本中出现此漏洞的地图现在可以通过将其拿在主手或副手上来修复此漏洞。（[MCPE-162421](https://bugs.mojang.com/browse/MCPE-162421)）
* 修复了玩家离开传送门后还会被传送回去的问题。（[MCPE-157494](https://bugs.mojang.com/browse/MCPE-157494)）
* 修复了切换维度时可能会使玩家卡在“生成地形中”界面，强制重启游戏后会将玩家传送到错误坐标的漏洞。（[MCPE-158215](https://bugs.mojang.com/browse/MCPE-158215)）
* 修复了升级1.18前的世界时存档区块会不正确混合的问题。（[MCPE-162480](https://bugs.mojang.com/browse/MCPE-162480)）
* 修复了Xbox控制器的摇杆盲区和灵敏度问题。（[MCPE-162847](https://bugs.mojang.com/browse/MCPE-162847)）

生物

* 将末影人的跟随范围由32格提高至64格。（[MCPE-35306](https://bugs.mojang.com/browse/MCPE-35306)）
* 跳跃提升现在会持续对玩家骑乘的生物产生影响。（[MCPE-45823](https://bugs.mojang.com/browse/MCPE-45823)）
* 缓降现在会持续对玩家骑乘的生物产生影响。（[MCPE-126604](https://bugs.mojang.com/browse/MCPE-126604)）
* 修复了世界高度为负数时蝙蝠休息位置错误的问题。
* 被摧毁的盔甲架现在会掉落其副手上的物品。（[MCPE-158228](https://bugs.mojang.com/browse/MCPE-158228)）
* 修复了在末影龙存活的情况下保存并加载世界时，末影龙会无法加载的漏洞。（[MCPE-156528](https://bugs.mojang.com/browse/MCPE-156528)）

方块

* 土径和耕地的方块碰撞现在下调了1个像素。（[MCPE-12109](https://bugs.mojang.com/browse/MCPE-12109)）
* 玩家现在会在灵魂沙和泥巴上下陷。（[MCPE-87458](https://bugs.mojang.com/browse/MCPE-87458)、[MCPE-154973](https://bugs.mojang.com/browse/MCPE-154973)）
* 甘蔗现在会在周围水源被移除后的下一随机刻中被破坏。（[MCPE-162351](https://bugs.mojang.com/browse/MCPE-162351)）
* 菌岩上长出的巨型下界菌不再会替换掉不完整方块。（[MCPE-65661](https://bugs.mojang.com/browse/MCPE-65661)）
* 修复了当坐标0 0 0​有实体时无法在其周围放置压力板的问题。（[MCPE-161377](https://bugs.mojang.com/browse/MCPE-161377)）
* 现在活塞头的伸缩动画更加流畅了。（[MCPE-155987](https://bugs.mojang.com/browse/MCPE-155987)）
* 现在活塞推动的方块的移动动画更加流畅了。（[MCPE-146597](https://bugs.mojang.com/browse/MCPE-146597)）
* 修复了放置告示牌时缺失音效的问题。
* 现在水下的岩浆块上的气泡柱可以正常生成。
* 玩家在泥巴上方游泳时不再会使屏幕被覆盖住。（[MCPE-153737](https://bugs.mojang.com/browse/MCPE-153737)）

物品

* 现在新合成的工具和盔甲在首次使用时可以正常工作。（[MCPE-161151](https://bugs.mojang.com/browse/MCPE-161151)）
* 现在武器、工具和盔甲可以在第一次被重命名后被玩家丢弃。（[MCPE-162132](https://bugs.mojang.com/browse/MCPE-162132)）
* 修复了书与笔无法署名或关闭的问题。（[MCPE-163325](https://bugs.mojang.com/browse/MCPE-163325)）
* 修复了蓄力完毕的物品会在玩家进入传送门后消失的漏洞。（[MCPE-55279](https://bugs.mojang.com/browse/MCPE-55279)）
* 使用铁砧附魔或修复物品时不再会意外地重命名物品。（[MCPE-154453](https://bugs.mojang.com/browse/MCPE-154453)）
* 修复了史莱姆和岩浆怪在每一随机刻都能消耗盾牌耐久度的漏洞。（[MCPE-119451](https://bugs.mojang.com/browse/MCPE-119451)）
* 修复了河豚在每一随机刻能消耗盾牌耐久度的漏洞。（[MCPE-143689](https://bugs.mojang.com/browse/MCPE-143689)）

触摸控制

* 重新加入了新的拆分物品功能。
* “分离控制”选项现在仅会在经典控制方案下出现，且仅影响经典控制方案。
* 修复了启用十字准星和触摸控制方案时，某些情况下会无法触摸快捷栏槽位的问题。
* 将拖拽物品前按住物品的停顿时长由120毫秒增加至180毫秒，以更轻松地滚动物品栏界面。
* 解除了“锁定摇杆”、“摇杆始终可见”和“未使用时摇杆可见”选项之间的联系。
* 修复了在高刷新率屏幕上难以双击触摸控制按钮的问题。（[MCPE-156351](https://bugs.mojang.com/browse/MCPE-156351)）
* 改进了新的触控模式下同时按下按钮并移动视角的方式。
* 现在使用十字准星控制来乘船时，操作按钮会正确显示出来。（[MCPE-159376](https://bugs.mojang.com/browse/MCPE-159376)）
* 修复了新的触摸控制方案下的取消骑乘按钮看起来很模糊的问题。（[MCPE-156722](https://bugs.mojang.com/browse/MCPE-156722)）
* 修复了将物品放在创造模式物品栏中的另一物品上时，该物品不会被丢弃的问题。（[MCPE-162124](https://bugs.mojang.com/browse/MCPE-162124)）
* 修复了不能使用新的触摸控制与部分资源包下的快捷栏交互的问题。（[MCPE-157748](https://bugs.mojang.com/browse/MCPE-157748)）
* 修复了在新的触摸控制下快速点击向上飞行和向下飞行按钮会取消飞行状态的问题。现在起，双击向下飞行按钮会取消飞行状态。（[MCPE-162240](https://bugs.mojang.com/browse/MCPE-162240)）
* 现在状态效果图标会在触控模式下适应安全区域。
* 调整了状态效果图标，现在会在屏幕宽度上排成一行，以在触控模式下适应新的触摸控制。
* 移除了攻击和交互的操作延时。（[MCPE-158143](https://bugs.mojang.com/browse/MCPE-158143)）
* 将摇杆未被锁定时的可拖动范围更改为与摇杆被锁定时相同的可拖动范围。若已开启“自动冲刺”选项，将摇杆略微拖动到摇杆背景区域上方时会开始疾跑；将摇杆拖动回摇杆背景区域时则会停止疾跑。
* 轻击手势现在会使已装填的弩发射。之前版本必须在发射前保持该手势400ms。
* 修复了玩家不能在铁砧界面拖拽或丢弃物品的问题。

图形

* 现在被活塞移动的方块也会拥有环境光照。（[MCPE-136928](https://bugs.mojang.com/browse/MCPE-136928)）
* 现在使用某些GPU的Android设备上的生物阴影会正确渲染。（[MCPE-155354](https://bugs.mojang.com/browse/MCPE-155354)）
* 为兼容的驱动程序加入了对英特尔集成或独立显卡的D3D12支持。

Realms

* 缩小了上传世界和附加包时的文本以适应对话框。
* 玩家加入已经空了若干分钟的Realms时不再会收到错误消息。

用户界面

* 为Android/iOS设备加入了移动数据可用但在游戏中被禁用时出现的移动数据被阻止的屏幕。
* 玩家现在可以在全键盘玩法和“启用复制坐标 UI”选项均开启的情况下重新绑定复制坐标的按键。（[MCPE-163082](https://bugs.mojang.com/browse/MCPE-163082)）
* 修复了Boss栏在Boss被重命名后不会在玩家重新加载Boss栏之前更新的问题。
* 修复了在携带版UI下的物品栏界面中，“可合成/所有”选项只能在搜索选项卡中更改，而不能在其他选项卡中更改的问题。
* 在Xbox上重新打开菜单屏幕时，使用鼠标进行的镜头移动不再会改变鼠标位置。（[MCPE-162890](https://bugs.mojang.com/browse/MCPE-162890)）
* 现在选中物品的堆叠计数的文本颜色是白色而不是黄色。
* 加入了玩家将要丢失在创建新的世界界面做出的更改时出现的警告。
* 更改了复制世界的错误处理流程，现在会显示一个错误弹窗而不是弹出警告。
* 修复了在VR模式下乘船时HUD无法跟随玩家朝向旋转的漏洞。
* 更改了“启用移动数据玩线上游戏”选项的文字颜色，以提升阅读体验。（[MCPE-162459](https://bugs.mojang.com/browse/MCPE-162459)）
* 修复了聊天设置中下拉框箭头、开关和滑条的对比问题

- 修复了游戏过程中可能发生的崩溃。
- 方块在被活塞推动时被破坏后不再会重新出现。
- 被推动的马不再能跨过上方放有地毯的栅栏。（[MCPE-164717](https://bugs.mojang.com/browse/MCPE-164717)）
- Nintendo Switch平台上不再会显示触摸控制选择屏幕。
- 修复了结构方块的UI屏幕中Y值字段无法通过键盘选择的问题。（[MCPE-164148](https://bugs.mojang.com/browse/MCPE-164148)）

</details>
