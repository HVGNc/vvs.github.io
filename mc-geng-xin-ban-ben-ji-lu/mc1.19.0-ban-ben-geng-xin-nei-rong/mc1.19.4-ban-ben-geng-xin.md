# MC1.19.4版本更新

{% hint style="warning" %}
## 更新要点

**【更新】1.19.4版本补丁更新公告：BC1.19.4**

更新补丁版本：1.19.4&#x20;

更新时间：2027-7-29

更新内容：
{% endhint %}

{% stepper %}
{% step %}
## 新内容

### 游戏内容 <a href="#you-xi-nei-rong" id="you-xi-nei-rong"></a>

[死亡消息](https://zh.minecraft.wiki/w/%E6%AD%BB%E4%BA%A1%E6%B6%88%E6%81%AF)

* 加入了被重命名后的物品杀死时出现的死亡消息：
  * “<玩家> 被 <玩家/生物> 用 <物品> 杀死了”

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

[选项](https://zh.minecraft.wiki/w/%E9%80%89%E9%A1%B9)

* 在视频设置中加入了“最大帧率”选项。
  * 用于控制游戏可到达的最大帧率。
* 在所有平台上的存储设置中加入了“清除市场缓存”按钮。
  * 用于清除[市场](https://zh.minecraft.wiki/w/%E5%B8%82%E5%9C%BA)文件夹中的内容。
{% endstep %}

{% step %}
## 更改

方块

[甜浆果丛](https://zh.minecraft.wiki/w/%E7%94%9C%E6%B5%86%E6%9E%9C%E4%B8%9B)

* 现在可以种植在[耕地](https://zh.minecraft.wiki/w/%E8%80%95%E5%9C%B0)上。

[脚手架](https://zh.minecraft.wiki/w/%E8%84%9A%E6%89%8B%E6%9E%B6)

* 现在每个脚手架只能烧炼0.25个物品。

#### 生物 <a href="#sheng-wu" id="sheng-wu"></a>

[劫掠兽](https://zh.minecraft.wiki/w/%E5%8A%AB%E6%8E%A0%E5%85%BD)

* 不再属于[灾厄村民](https://zh.minecraft.wiki/w/%E7%81%BE%E5%8E%84%E6%9D%91%E6%B0%91)。
  * 因此现在会受到[唤魔者尖牙](https://zh.minecraft.wiki/w/%E5%94%A4%E9%AD%94%E8%80%85%E5%B0%96%E7%89%99)造成的伤害，且[“Johnny”卫道士](https://zh.minecraft.wiki/w/%E5%8D%AB%E9%81%93%E5%A3%AB#%E2%80%9CJohnny%E2%80%9D%E5%8D%AB%E9%81%93%E5%A3%AB)现在会主动攻击劫掠兽。
* 增大了碰撞箱以匹配[Java版](https://zh.minecraft.wiki/w/Java%E7%89%88)。

[凋灵骷髅](https://zh.minecraft.wiki/w/%E5%87%8B%E7%81%B5%E9%AA%B7%E9%AB%85)

* 现在能够在[凋灵玫瑰](https://zh.minecraft.wiki/w/%E5%87%8B%E7%81%B5%E7%8E%AB%E7%91%B0)中生成。

[村民](https://zh.minecraft.wiki/w/%E6%9D%91%E6%B0%91)

* 图书管理员村民现在能够出售[消失诅咒](https://zh.minecraft.wiki/w/%E6%B6%88%E5%A4%B1%E8%AF%85%E5%92%92)和[绑定诅咒](https://zh.minecraft.wiki/w/%E7%BB%91%E5%AE%9A%E8%AF%85%E5%92%92)附魔书。

#### 游戏内容 <a href="#you-xi-nei-rong" id="you-xi-nei-rong"></a>

[双持](https://zh.minecraft.wiki/w/%E5%8F%8C%E6%8C%81)

* 现在可以使用/replaceitem​命令将任意物品放进副手槽里，且部分物品可以像在主手时那样正常交互。

[配方](https://zh.minecraft.wiki/w/%E9%85%8D%E6%96%B9)

* 现在合成配方中的同类合成材料可以任意混合（如使用[圆石](https://zh.minecraft.wiki/w/%E5%9C%86%E7%9F%B3)和[黑石](https://zh.minecraft.wiki/w/%E9%BB%91%E7%9F%B3)合成[石剑](https://zh.minecraft.wiki/w/%E7%9F%B3%E5%89%91)）。

#### 命令格式 <a href="#ming-ling-ge-shi" id="ming-ling-ge-shi"></a>

​/gametest​

* 不再属于[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)。

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)

* 将“应用测试框架”子选项重命名为“测试版 API”。

[触摸控制](https://zh.minecraft.wiki/w/%E8%A7%A6%E6%91%B8%E6%8E%A7%E5%88%B6)

* 现在当启用自动跳跃时，玩家在水中朝着陆地上的一格方块移动时会自动跳出水面。
* 将创造模式下关闭操作按钮并使用触控操作时破坏第一个方块的延时提高到800ms，以减少方块的误破坏。
* 现在使用触控也可以在物品栏中拖拽来放置物品。
* 现在可以在新触控模式下双击下降按钮以取消飞行状态。
* 优化了携带版UI下[状态效果](https://zh.minecraft.wiki/w/%E7%8A%B6%E6%80%81%E6%95%88%E6%9E%9C)的显示位置。

[选项](https://zh.minecraft.wiki/w/%E9%80%89%E9%A1%B9)

* 更改了轻触设置中的一些选项名称：
  * “冲刺移动”重命名为“自动冲刺”。
  * “移动摇杆可见”重命名为“摇杆始终可见”。
  * “不使用时移动摇杆始终可见”重命名为“未使用时摇杆可见”。
  * “静态摇杆”重命名为“锁定摇杆”。
  * “切换蹲下”重命名为“潜行切换”。
* 将“摧毁方块（震动）”选项拆分为两个选项：
  * “破坏方块时振动”
  * “拆分物品时振动”
* 将档案设置拆分为两个新设置：“通用”和“帐户”。
* 移除了非Nintendo Switch平台上的“清除账户登录数据”按钮。
* 将“文件存储位置”选项移动至存储设置中。
* 将“使用移动数据”选项重命名为“启用移动数据玩线上游戏”。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

自定义方块几何结构

* 现在能够使用自定义几何结构和纹理来制作自定义方块，无需在设置中开启“假日创造者功能”实验性选项。

常规

* 修复了使用hasItem​选择器并为物品数据指定负数值时可能发生的崩溃。（[MCPE-152314](https://bugs.mojang.com/browse/MCPE-152314)）
* 实现了has\_property​、int\_property​、bool\_property​、float\_property​和enum\_property​活动对象过滤器。
* 在menu\_category​中加入了旗标is\_hidden\_in\_commands​以控制方块是否可以在命令中使用。
* 开放了1.19.40及以上版本的实验性JSON格式中的BlockGeometryComponent​。
* 开放了1.19.40及以上版本的实验性JSON格式中的BlockMaterialInstancesComponent​。
* 将minecraft:block\_light\_filter​组件重命名为minecraft:light\_dampening​。
* 将实验性GameTest框架重命名为Beta API。
* 现已重命名的Beta API实验性内容仍然需要访问包括核心Minecraft API和GameTest API在内的所有测试版API。
* 修复了EntityHurtEvent​在玩家死亡时不会触发的漏洞。
* ​Entity​
  * 将target​属性更新为只读属性。
  * 修复了UI表单无法正确标记其canceled​字段的问题。
* 将EntityQueryScoreOptions​转换为接口。
* 将EntityRaycastOptions​转换为接口。
* 将ExplosionOptions​转换为接口。
* 将MusicOptions​转换为接口。
* 将SoundOptions​转换为接口。
* 移除了内置的GameTest行为包。

命令

* 修复了传送会使目标看起来像飞到新的位置而不是瞬间到达的问题。
* 为/loot​命令加入了replace block​重载。
* 为/setblock​命令加入了用特定的自定义方块属性设置自定义方块的能力。
* 使用/clone​命令复制气泡柱不再会导致产生隐形的水。（[MCPE-153903](https://bugs.mojang.com/browse/MCPE-153903)）

数据驱动方块

* ​minecraft:direction​不再公开为数据驱动方块的Property​。方块会在使用minecraft​命名空间时抛出内容日志错误。

数据驱动物品

* 加入了对配方直接使用物品标签而不是物品名称的支持。
  * 加入了一些新的物品标签：
    * ​minecraft:coals​、minecraft:logs​、minecraft:logs\_that\_burn​、minecraft:planks​、minecraft:soul\_fire\_base\_blocks​、minecraft:stone\_crafting\_materials​、minecraft:stone\_tool\_materials​、minecraft:wooden\_slabs​和minecraft:wool​。
  * 将部分配方由代码转换为自己的配方文件。
  * 加入了一些使用新标签的配方以覆盖大量的旧版、物品特定配方（这些配方仍然存在，以支持后向兼容）：
    * ​barrel​、beehive​、bookshelf​、bowl​、brewing\_stand​、campfire​、cartography\_table​、chest​、composter​、crafting\_table​、daylight\_detector​、fire\_charge​、fletching\_table​、furnace​、grindstone​、jukebox​、lectern​、loom​、noteblock​、painting​、piston​、shield​、smithing\_table​、smoker​、soul\_campfire​、soul\_torch​、stick​、stone\_axe​、stone\_hoe​、stone\_pickaxe​、stone\_shovel​、stone\_sword​、torch​、tripwire\_hook​、wooden\_axe​、wooden\_hoe​、wooden\_pickaxe​、wooden\_shovel​和wooden\_sword​。
* 带有minecraft:digger​组件的自定义物品、标签和方块标签现在会正常生效。（[MCPE-155786](https://bugs.mojang.com/browse/MCPE-155786)）

活动对象

* 实现了新的is\_baby​活动对象行为过滤器，当主实体是幼年状态时返回true。
* 修复了bool\_property​过滤器不能指定value​的问题。

AI意向

* 修复了铁傀儡会阻止带有minecraft:take\_flower​AI行为的生物使用该意向的漏洞。
* 公开了minecraft:play​AI行为的新数据参数，可以指定意向保持活跃的持续时间、开启意向的概率、寻找友方的范围，以及与友方一起玩耍时的跟随距离。

实体文档

* 移除了荒野更新实体行为和组件的实验性标志。
* 加入了minecraft:heartbeat​文档。
* 修复并更新了实体事件文档。
{% endstep %}

{% step %}
## 实验性

### <mark style="color:orange;">本段落的内容需要开启</mark>[<mark style="color:orange;">实验性玩法</mark>](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)<mark style="color:orange;">中的“即将推出的创作者功能”和“测试版 API”子选项后才可使用。</mark>

#### 命令格式 <a href="#ming-ling-ge-shi" id="ming-ling-ge-shi"></a>

​/execute​

* 加入了一些新的修饰子命令：
  * ​rotated​
  * ​rotated as​
  * ​facing​
  * ​facing entity​
  * ​align​
  * ​in​
  * ​anchored \<eyes|feet>​

​/script​

* 现在需要加载脚本才可使用。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

命令

* 修复了命令方块执行/execute facing​和/execute rotated​时的方向错误问题。（[MCPE-162256](https://bugs.mojang.com/browse/MCPE-162256)）

API

* ​Events​
  * 移除了在每一刻内调用的tick​事件。
* ​System​
  * 加入了函数run()​。
    * 用于在队列中加入在下一随机刻中运行的回调，并重新对随机刻进行排列。
* ​Block​
  * 将id​属性重命名为typeId​。
* ​BlockComponent​
  * 将id​属性重命名为typeId​。
* ​Entity​
  * 将id​属性重命名为typeId​。
  * 加入了只读属性id: string​。
    * 用于返回该实体在世界加载范围内独特且保持不变的标识符。
* ​EntityComponent​
  * 将id​属性重命名为typeId​。
* ​ItemComponent​
  * 将id​属性重命名为typeId​。
* ​ItemStack​
  * 将id​属性重命名为typeId​。

GameTest框架

* 根据新规则重命名了所有脚本模块。
  * ​mojang-gametest​ → @minecraft/server-gametest​
  * ​mojang-minecraft​ → @minecraft/server​
  * ​mojang-minecraft-ui​ → @minecraft/server-ui​
  * ​mojang-minecraft-server-admin​ → @minecraft/server-admin​
  * ​mojang-net​ → @minecraft/server-net​
* 现在eval()​和Funtion()​脚本在使用前必须先在json文件中以"capabilities": \["script\_eval"]​的方法启用。
* 更改了导入功能的根路径，不再允许使用scripts/​前缀。
* 弃用了scripts/source.js​导入。
{% endstep %}

{% step %}
## 修复

原版趋同

* 常规
  * 现在被重命名后的武器杀死时会出现带着该武器名称的死亡消息。
  * 现在被手持重命名后的武器的生物杀死时会出现带着该武器名称的死亡消息。（[MCPE-162055](https://bugs.mojang.com/browse/MCPE-162055)）
  * 现在黑森林、风袭热带草原和桦木森林会使用正确的草地颜色。（[MCPE-34936](https://bugs.mojang.com/browse/MCPE-34936)）
  * 远古城市范围内不再生成生物。（[MCPE-153524](https://bugs.mojang.com/browse/MCPE-153524)）
  * 甜浆果丛现在可以种植在耕地上。（[MCPE-99632](https://bugs.mojang.com/browse/MCPE-99632)）
  * 更改了气泡柱的推拉强度以匹配Java版。（[MCPE-158858](https://bugs.mojang.com/browse/MCPE-158858)）
  * 脚手架现在会以正确的燃烧时间作为熔炉燃料，即烧炼1⁄4个物品。（[MCPE-42949](https://bugs.mojang.com/browse/MCPE-42949)）
  * 凋灵骷髅现在能够在凋灵玫瑰中生成。（[MCPE-110127](https://bugs.mojang.com/browse/MCPE-110127)）
  * 降低了游泳时消耗的饥饿值以匹配Java版。（[MCPE-154452](https://bugs.mojang.com/browse/MCPE-154452)）
* 生物
  * 劫掠兽现在会受到唤魔者尖牙造成的伤害。
  * 增大了劫掠兽的碰撞箱以匹配Java版。（[MCPE-142171](https://bugs.mojang.com/browse/MCPE-142171)、[MCPE-45531](https://bugs.mojang.com/browse/MCPE-45531)）
  * 提高了劫掠兽的移动速度以匹配Java版。（[MCPE-48145](https://bugs.mojang.com/browse/MCPE-48145)）
  * 图书管理员村民现在能够出售消失诅咒和绑定诅咒附魔书。（[MCPE-84906](https://bugs.mojang.com/browse/MCPE-84906)）
* 方块
  * 玩家在泥巴上方游泳时不再会使屏幕被覆盖住。（[MCPE-153737](https://bugs.mojang.com/browse/MCPE-153737)）
  * 落在泥巴上的弹射物不再会反复抖动。（[MCPE-153744](https://bugs.mojang.com/browse/MCPE-153744)）
  * 泥巴旁的两栖生物不再会出现寻路问题。（[MCPE-153961](https://bugs.mojang.com/browse/MCPE-153961)）
* 旁观模式（实验性）
  * 旁观模式玩家死亡时不再掉落经验球。（[MCPE-160245](https://bugs.mojang.com/browse/MCPE-160245)）
  * 旁观模式玩家死亡时不再重置其经验等级。
  * 旁观模式玩家的水雾效果不再会被移除。（[MCPE-161105](https://bugs.mojang.com/browse/MCPE-161105)）
  * 旁观模式玩家进入或离开气泡柱时不再会播放音效。（[MCPE-161536](https://bugs.mojang.com/browse/MCPE-161536)）
  * 潜影弹不再会跟随旁观模式玩家。（[MCPE-162069](https://bugs.mojang.com/browse/MCPE-162069)）
  * 现在旁观模式玩家在普通玩家的视角中是隐形的。
  * 服务器上不存在其他非旁观模式玩家时，旁观模式玩家不再会影响生物的消失。
  * 现在服务器上只有旁观模式玩家在线时，生物消失会被暂停。

性能与稳定性

* 修复了在PlayStation 4版上的和平模式世界中使用刷怪蛋时发生的崩溃。
* 修复了当结构方块加载一个动画结构，且玩家进入传送门离开维度时可能发生的崩溃 。（[MCPE-132561](https://bugs.mojang.com/browse/MCPE-132561)）
* 修复了在加载带有未识别数据值的箭时导致游戏崩溃的漏洞。（[MCPE-157983](https://bugs.mojang.com/browse/MCPE-157983)）
* 修复了一个可能源自于爆炸的崩溃。
* 修复了退出分屏游戏会话时可能发生的崩溃。
* 修复了市场同捆包的价格在购买后不会显示为免费的问题。
* 在所有平台上的存储设置中加入了清除数据的按钮。该按钮可能有助于缓解下载内容相关的问题。（[MCPE-54531](https://bugs.mojang.com/browse/MCPE-54531)）
* 修复了凋零效果造成的伤害会被无保护魔咒盔甲减免的问题。（[MCPE-159407](https://bugs.mojang.com/browse/MCPE-159407)）

游戏内容

* 现在玩家使用键盘游玩时，向左前方或右前方移动也可以疾跑。（[MCPE-144702](https://bugs.mojang.com/browse/MCPE-144702)）
* 现在雪林生物群系被归为寒冷生物群系，生成在此处的村民会使用雪原皮肤。（[MCPE-147834](https://bugs.mojang.com/browse/MCPE-147834)）
* 修复了气泡柱上方的活板门中的玩家会积累摔落伤害的问题。（[MCPE-158858](https://bugs.mojang.com/browse/MCPE-158858)）
* 修复了导致玩家在使用VR Snap相机移动后转向错误方向的漏洞。（[MCPE-152443](https://bugs.mojang.com/browse/MCPE-152443)）

生物

* 幼年村民现在又可以拿走铁傀儡手上的花了。
* 守卫者不再能够悬浮在空中。（[MCPE-33641](https://bugs.mojang.com/browse/MCPE-33641)）
* 现在已驯服的生物会跟随玩家进入末地传送门。
* 修复了溺尸能够在攻击生物时切换手持物品的问题。（[MCPE-40288](https://bugs.mojang.com/browse/MCPE-40288)）
* 修复了攻击范围较远的生物能够穿墙攻击玩家的漏洞。（[MCPE-55790](https://bugs.mojang.com/browse/MCPE-55790)）
* 现在坐在船上的生物无法再进入其他维度。（[MCPE-154919](https://bugs.mojang.com/browse/MCPE-154919)）
* NPC现在能够不拥有名称，将名称隐藏在头顶。

方块

* 下落在双层台阶上的下落的方块不再会变成掉落物。（[MCPE-159921](https://bugs.mojang.com/browse/MCPE-159921)）
* 修复了巨型下界菌在菌岩上长出时菌柄可能会替换掉不完整方块的漏洞。（[MCPE-65661](https://bugs.mojang.com/browse/MCPE-65661)）
* 放置在其他方块下的含水方块的水的纹理不再渲染得太亮。（[MCPE-76949](https://bugs.mojang.com/browse/MCPE-76949)）
* 修复了红石线会在某些情况下显示错误的信号强度的问题。（[MCPE-81981](https://bugs.mojang.com/browse/MCPE-81981)）
* 修复了在世界建造高度限制附近使用黏性活塞时出现的一些漏洞。（[MCPE-96088](https://bugs.mojang.com/browse/MCPE-96088)）
* 现在破坏被雪层覆盖的花下方方块后会使花掉落，而不是使雪层掉落。（[MCPE-61609](https://bugs.mojang.com/browse/MCPE-61609)）
* 修复了信标从远处看会突然消失不见的问题。
* 现在附魔台上的书会面向离它最近的玩家。（[MCPE-29924](https://bugs.mojang.com/browse/MCPE-29924)）

物品

* 回退了导致箭和三叉戟停止移动的更改。（[MCPE-162085](https://bugs.mojang.com/browse/MCPE-162085)）

图形

* 修复了Android设备的屏幕位置的潜在问题。（[MCPE-159703](https://bugs.mojang.com/browse/MCPE-159703)）

用户界面

* 移除了非Switch平台设置菜单中的仅适用于NS的“清除账户登录数据”按钮。（[MCPE-129704](https://bugs.mojang.com/browse/MCPE-129704)）
* 修复了用户名可能会超过最大长度限制的漏洞。（[MCPE-152884](https://bugs.mojang.com/browse/MCPE-152884)）
* 将“档案”设置拆分为“通用”和“帐户”。
* 改进了文本转语音对新死亡屏幕的支持。
* 修复了某些世界模板会禁用成就的漏洞。
* 修复了在携带版UI下的工作台界面中，物品方格附近的深灰色区域可能会使物品被丢弃的漏洞。
* 修复了在携带版UI下的马、驴、骡和羊驼的物品栏中，物品方格附近的深灰色区域可能会使物品被丢弃的漏洞。
* 修复了showdeathmessage​游戏规则设置为false时仍会显示死亡消息的漏洞。
* 修复了玩家无法在装备界面拖拽或选择物品的问题。
* 将“黑暗效果强度”和“通知持续时间”辅助功能选项的描述文本的颜色更改为较浅的色度，以提升阅读体验。（[MCPE-162047](https://bugs.mojang.com/browse/MCPE-162047)）
* 修复了死亡消息有时会太长以至于无法在屏幕上显示的漏洞。（[MCPE-156550](https://bugs.mojang.com/browse/MCPE-156550))
* 修复了合成界面的搜索字符串不会正确保存的问题。
* 修复了Xbox上的物品栏界面会缺失耐久度条的问题。（[MCPE-162063](https://bugs.mojang.com/browse/MCPE-162063)）
* 修复了创建新的世界上的登录按钮无法在部分平台上生效的漏洞。
* 现在复制坐标的手柄提示会根据相应平台来使用正确图标。（[MCPE-162654](https://bugs.mojang.com/browse/MCPE-162654)）

Realms

* 缩小了上传世界和附加包时的文本以适宜对话框。
* 修复了自定义附加包不能在Realms设置中正确应用的问题，同时修复了上传包期间发生的崩溃。（[REALMS-10655](https://bugs.mojang.com/browse/REALMS-10655)）
* 连接到使用过时客户端的Realms时不再会出现未本地化的文本。

移动端触摸控制

* 修复了在移动设备上将物品从快捷栏移动到创造模式物品栏中的其他物品上时，该物品不会被删除的问题。
* 修复了触摸控制下的堆叠拆分进度条不对齐的问题。
* 调整了触摸控制下工具栏和状态效果图标的布局。
* 修复了无法在移动设备上滚动村民交易列表的问题。
* 现在当启用自动跳跃时，玩家在水中朝着陆地上的一格方块移动时会自动跳出水面。
* 将创造模式下关闭操作按钮并使用触控操作时破坏第一个方块的延时提高到800ms，以减少方块的误破坏。
* 现在使用触控也可以在物品栏中拖拽来放置物品。
* 现在可以在新触控模式下双击下降按钮以取消飞行状态。
* 优化了携带版UI下状态效果的显示位置。
* 触控设备的物品栏按钮现在会在关闭物品栏后重置为默认外观。
* 修复了玩家不能通过触摸控制来使不可堆叠物品交换位置的问题。
* 改进了轻触设置中的三种控制设计的对应图像。
* 修复了Xbox Series X|S主机上由于帧率显示错误，导致重启后游戏性能不稳定的问题。（[MCPE-155879](https://bugs.mojang.com/browse/MCPE-155879)）
* 修复了启用RTX时夜空亮度不正确的问题。（[MCPE-162445](https://bugs.mojang.com/browse/MCPE-162445)）
* 现在当玩家按住控制器上的“放置”按钮时，玩家又可以在物品栏方格中将物品分开。（[MCPE-163625](https://bugs.mojang.com/browse/MCPE-163625)）
* 修复了触摸控制玩家不能通过滚动来查看箱子内容物的问题。（[MCPE-163619](https://bugs.mojang.com/browse/MCPE-163619)）
* 修复了一些与加入Realms相关的问题。
{% endstep %}
{% endstepper %}
