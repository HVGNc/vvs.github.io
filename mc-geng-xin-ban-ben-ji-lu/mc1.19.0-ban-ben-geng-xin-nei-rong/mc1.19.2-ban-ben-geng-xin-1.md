# MC1.19.7版本更新



{% hint style="success" icon="rotate" %}
## **更新要点**

#### **【更新】1.19.7版本补丁更新公告：BC1.19.7**

更新补丁版本：1.19.7 更新时间：2028-3-10

更新内容：
{% endhint %}

<details>

<summary><strong>更改</strong></summary>

### 更改 <a href="#geng-gai" id="geng-gai"></a>

#### 方块 <a href="#fang-kuai" id="fang-kuai"></a>

[漏斗](https://zh.minecraft.wiki/w/%E6%BC%8F%E6%96%97)

* 现在能够吸入其上方高度低于1格的方块上的物品。

[羊毛](https://zh.minecraft.wiki/w/%E7%BE%8A%E6%AF%9B)

* ID现在被拆分为不同颜色羊毛的ID。

#### 生物 <a href="#sheng-wu" id="sheng-wu"></a>

[海豚](https://zh.minecraft.wiki/w/%E6%B5%B7%E8%B1%9A)

* 现在在陆地上时会扑腾，以匹配[Java版](https://zh.minecraft.wiki/w/Java%E7%89%88)。

#### 非生物实体 <a href="#fei-sheng-wu-shi-ti" id="fei-sheng-wu-shi-ti"></a>

[末地水晶](https://zh.minecraft.wiki/w/%E6%9C%AB%E5%9C%B0%E6%B0%B4%E6%99%B6)

* 增大了碰撞箱以匹配[Java版](https://zh.minecraft.wiki/w/Java%E7%89%88)。

#### 游戏内容 <a href="#you-xi-nei-rong" id="you-xi-nei-rong"></a>

[潜行](https://zh.minecraft.wiki/w/%E6%BD%9C%E8%A1%8C)

* 现在会将玩家的高度降低到1.49格，使其能够穿过1.5格高的空隙。
* 现在玩家位于小于1.8格的空间时会自动进入潜行状态。
* 现在玩家潜行时会降低相机视角高度。
* 现在玩家取消潜行需要足够的空间。
* 现在有足够的空间潜行但不能站立时，玩家会从[游泳](https://zh.minecraft.wiki/w/%E6%B8%B8%E6%B3%B3)状态切换至潜行状态。

#### 常规 <a href="#chang-gui" id="chang-gui"></a>

游戏指南

* 更新了游戏指南界面，加入了有关新触摸控制的内容。

</details>

<details>

<summary><strong>实验性</strong></summary>

### 实验性 <a href="#shi-yan-xing" id="shi-yan-xing"></a>

本段落的内容需要开启[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)中的“下一个主要更新”、“即将推出的创作者功能”和“测试版 API”子选项后才可使用。

#### 常规 <a href="#chang-gui-2" id="chang-gui-2"></a>

生物

* 现在物品栏和快捷栏中的猪灵的头会正确渲染耳朵的位置，使其不再覆盖头部。（[MCPE-164605](https://bugs.mojang.com/browse/MCPE-164605)）
* 现在玩家在骑乘骆驼时会受到摔落伤害。

[命令](https://zh.minecraft.wiki/w/%E5%91%BD%E4%BB%A4)

* 修复了执行对象在命令执行前被移除时会产生的崩溃。

#### 技术性 <a href="#ji-shu-xing" id="ji-shu-xing"></a>

API

* 将`Location`和`BlockLocation`类移出测试版脚本API，并将其所有的引用改为`Vector3`接口。
* `ItemStack`
  * 现在使用`setLore(undefined)`或`setLore([])`函数可以清除物品词缀。
  * 加入了`clearLore`函数。
    * 用于清除物品词缀。
  * 修复了对`EntityItemComponent.itemStack`返回的`ItemStacks`调用`getComponent`或`ItemStack.getComponents`函数时会出现的漏洞。
* `BeforeChatEvent`
  * 加入了`getTargets(): Player[]`函数。
    * 用于返回发送消息的目标玩家。
  * 加入了`setTargets(players: Player[])`函数。
    * 用于设置发送消息的目标玩家。
  * 移除了`targets`属性。
* `Block`
  * 加入了`isAir`函数。
    * 用于返回方块是否为空气。
  * 加入了`isLiquid`函数。
    * 用于返回方块是否为流体。
  * 加入了`isSolid`函数。
    * 用于返回方块是否为完整固体。
  * 为下列方块加入了`inventory`组件：
    * 木桶
    * 信标
    * 高炉
    * 酿造台
    * 投掷器
    * 发射器
    * 熔炉
    * 漏斗
    * 唱片机
    * 讲台
    * 烟熏炉
* `Events`
  * 加入了`entityDie`事件。
    * 在实体死亡时触发。
  * 将`projectileHit`属性改为只读。
* `Player`
  * 将`tell`函数重命名为`sendMessage`。
  * 加入了`getSpawnPosition`方法。
    * 用于返回重生点位置。
  * 加入了`getSpawnDimension`方法。
    * 用于返回重生点所在维度。
  * 加入了`setSpawn(spawnPosition : Vec3, spawnDimension : Dimension)`方法。
    * 用于设置重生点的位置和所在维度。
  * 加入了`clearSpawn`方法。
    * 将重生点的位置和所在维度设为`undefined`。
* `World`
  * 将`say`函数重命名为`sendMessage`。
  * 加入了`getDefaultSpawnPosition`方法。
    * 用于返回重生点位置。
  * 加入了`setDefaultSpawn(spawnPosition : Vec3)`方法。
    * 用于设置重生点位置，维度为`overworld`。
* `BeforeDataDrivenEntityTriggerEvent`
  * 加入了`getModifiers(): DefinitionModifier[]`函数。
    * 用于返回实体的定义修饰符。
  * 加入了`setModifiers(modifiers: DefinitionModifier[])`函数。
    * 用于设置实体的定义修饰符。
  * 移除了`modifiers`属性。
* `BoolBlockProperty`
  * 加入了`getValidValues(): boolean[]`函数。
    * 用于返回`BoolBlockProperty`的所有有效布尔值。
  * 移除了`validValues`属性。
* 将`BlockHitInformation`改为接口。
* `ChatEvent`
  * 加入了`getTargets(): Player[]`函数。
    * 用于返回发送消息的目标玩家。
  * 移除了`targets`属性。
* 将`Color`改为接口。
* `DataDrivenEntityTriggerEvent`
  * 加入了`getModifiers(): DefinitionModifier[]`函数。
    * 用于返回实体的定义修饰符。
  * 移除了`modifiers`属性。
* `DefinitionModifier`
  * 加入了`getComponentGroupsToAdd(): string[]`函数。
    * 用于返回会与`DefinitionModifier`一同加入的属性组。
  * 加入了`setComponentGroupsToAdd(newGroups: string[]): void`函数。
    * 用于设置会与`DefinitionModifier`一同加入的属性组。
  * 加入了`getComponentGroupsToRemove(): string[]`函数。
    * 用于返回会与`DefinitionModifier`一同被移除的属性组。
  * 加入了`setComponentGroupsToRemove(newGroups: string[]): void`函数。
    * 用于设置会与`DefinitionModifier`一同被移除的属性组。
  * 加入了`getTriggers(): Trigger[]`函数。
    * 用于返回`DefinitionModifier`的事件触发器。
  * 加入了`setTriggers(newTriggers: Trigger[]): void`函数。
    * 用于设置`DefinitionModifier`的事件触发器。
  * 移除了`componentGroupsToAdd`属性。
  * 移除了`componentGroupsToRemove`属性。
  * 移除了`triggers`属性。
* `DirectionBlockProperty`
  * 加入了`getValidValues(): Direction[]`函数。
    * 用于返回`BoolBlockProperty`的所有有效方向枚举值。
  * 移除了`validValues`属性。
* `Entity`
  * 加入了`getViewDirection(): Vector3`函数。
    * 用于返回实体的视觉方向。
  * 加入了`getRotation(): XYRotation`函数。
    * 用于返回实体的旋转方向。
  * 加入了`getVelocity(): Vector`函数。
    * 用于返回实体的速度。
  * 移除了`viewDirection`属性。
  * 移除了`rotation`属性。
  * 移除了`velocity`属性。
* `EntityAgeableComponent`
  * 加入了`getDropItems(): string[]`函数。
    * 用于返回实体成长时的掉落物。
  * 加入了`getFeedItems(): EntityDefinitionFeedItem[]`函数。
    * 用于返回可对实体进行喂食的物品。
  * 移除了`dropItems`属性。
  * 移除了`feedItems`属性。
* `EntityBreathableComponent`
  * 加入了`getBreatheBlocks(): BlockPermutation[]`函数。
    * 用于返回实体处于其中时可进行呼吸的方块。
  * 加入了`getNonBreatheBlocks(): BlockPermutation[]`函数。
    * 用于返回实体处于其中时不可进行呼吸的方块。
  * 移除了`breatheBlocks`属性。
  * 移除了`nonBreatheBlocks`属性。
* `EntityHealableComponent`
  * 加入了`getFeedItems(): FeedItem[]`函数。
    * 用于返回可恢复实体生命值的物品。
  * 移除了`items`属性。
* 将`EntityHitInformation`改为接口。
* `EntityRideableComponent`
  * 加入了`getFamilyTypes(): string[]`函数。
    * 用于返回可被骑乘的实体种类。
  * 加入了`getSeats(): Seat[]`函数。
    * 用于返回实体上每一个座位的骑乘者信息。
  * 移除了`familyTypes`属性。
  * 移除了`seats`属性。
* `EntityTameableComponent`
  * 加入了`getTameItems(): string[]`函数。
    * 用于返回可驯服实体的物品。
  * 移除了`tameItems`属性。
* `FeedItem`
  * 加入了`getEffects(): FeedItemEffect[]`函数。
    * 用于返回`FeedItem`的效果。
  * 移除了`effects`属性。
* `IntBlockProperty`
  * 加入了`getValidValues(): number[]`函数。
    * 用于返回`IntBlockProperty`的所有有效整值。
  * 移除了`validValues`属性。
* `ItemDurabilityComponent`
  * 加入了`getDamageRange(): NumberRange`函数。
    * 用于返回描述物品丢失耐久度的概率的数字范围。
  * 移除了`damageRange`属性。
* 将`NumberRange`改为接口。
* `ProjectileHitEvent`
  * 加入了`getBlockHit(): BlockHitInformation`函数。
    * 用于返回方块碰撞信息。
  * 加入了`getEntityHit(): EntityHitInformation`函数。
    * 用于返回实体碰撞信息。
  * 移除了`blockHit`属性。
  * 移除了`entityHit`属性。
* `StringBlockProperty`
  * 加入了`getValidValues(): string[]`函数。
    * 用于返回`StringBlockProperty`的所有有效字符串值。
  * 移除了`validValues`属性。

</details>

<details>

<summary><strong>修复</strong></summary>

### 修复 <a href="#xiu-fu" id="xiu-fu"></a>

原版趋同

* 其中一个方块被破坏时，连接多个方块的钟不再会掉落为物品。
* 现在繁殖马会产下随机变种的幼年马。（[MCPE-129071](https://bugs.mojang.com/browse/MCPE-129071)）
* 修复了死亡的玩家会阻止其他玩家跳过夜晚的问题。
* 现在无论屏幕比例为多少，食用和饮用动画都会保持居中显示。
* 现在远距离的音符盒的音效衰减是线性的。（[MCPE-164935](https://bugs.mojang.com/browse/MCPE-164935)）

游戏内容

* 玩家接触能够造成伤害的方块时不再会快速受到伤害。（[MCPE-165347](https://bugs.mojang.com/browse/MCPE-165347)）
* 修复了在1.8或更高版本进入1.7.1.0的世界时可能发生的崩溃。（[MCPE-165564](https://bugs.mojang.com/browse/MCPE-165564)）
* 游泳或使用鞘翅滑翔的玩家射出弹射物时，其不再会生成在玩家所在位置上方。（[MCPE-31896](https://bugs.mojang.com/browse/MCPE-31896)）
* 游泳或使用鞘翅滑翔的玩家手动丢弃物品或死亡时，物品不再会生成在玩家所在位置上方。（[MCPE-31896](https://bugs.mojang.com/browse/MCPE-31896)）
* 现在使用十字准星的玩家可以在游泳或使用鞘翅滑翔时正确进行挖掘，或与前方物品交互，而不是在玩家所在位置上方一格进行交互。（[MCPE-57257](https://bugs.mojang.com/browse/MCPE-57257)）
* 现在即使拥有相同的成书，玩家也可以在物品栏中移动成书。
* 双击熔炉的输出槽时不再会将物品丢弃。（[MCPE-165079](https://bugs.mojang.com/browse/MCPE-165079)）
* 修复了侦测器无法检测数据损坏导致的更改的漏洞。（[MCPE-150506](https://bugs.mojang.com/browse/MCPE-150506)）
* 漏斗现在能够吸入其上方高度低于完整方块的方块上的物品。（[MCPE-55824](https://bugs.mojang.com/browse/MCPE-55824)）
* 对刷怪笼使用蜜蜂刷怪蛋时不再会创建内容日志错误。
* 带有脚本的行为包现在能够从世界中移除。

方块

* 现在破坏红树原木或木头后会正确导致其上的树叶消失。
* 末地水晶和方块占用同一空间时不再会导致方块消失。

图形

* 修复了创造模式下使用三叉戟对准方块时会出现“挖掘”工具提示的问题。（[MCPE-44846](https://bugs.mojang.com/browse/MCPE-44846)）

生物

* 现在鹦鹉在玩家骑乘的马跳跃时不再会颤抖。
* 修复了在渲染距离外全局性实体（如末影龙、弹射物）不会被渲染的漏洞。（[MCPE-161136](https://bugs.mojang.com/browse/MCPE-161136)）
* 现在定义热带鱼生成规则的JSON文件会被放置在正确的文件夹中。（[MCPE-165963](https://bugs.mojang.com/browse/MCPE-165963)）
* 现在女巫的JSON文件会定义其饮用药水和远程攻击的动作。

触摸控制

* 更新了游戏指南界面，加入了有关新触摸控制的内容。
* 现在将控制模式由游戏手柄更改为触控后选择一个物品时，会返回至所选择的物品栏或将该物品丢弃。
* 修复了在熔炉界面中双击窗口会导致无法选择其他槽位的问题。
* 修复了打开小型箱子时第一个槽位上会自动启用渐进式选择的漏洞。

移动平台

* 现在在携带版UI下创建新世界并关闭文本朗读选项后，“按 打开聊天栏 打开聊天”信息会被移除。

用户界面

* 现在海洋探险家地图、林地探险家地图和藏宝图会显示正确的物品栏图标。（[MCPE-163464](https://bugs.mojang.com/browse/MCPE-163464)）
* 修复了无法使用鼠标在好友选项下拉菜单中滚动内容的漏洞。
* 修复了登录或注册界面的图形元素会延伸至对话框容器范围之外的问题。

命令

* ​/replaceitem​和/loot replace block​命令不再会在炼药锅中放置物品。（[MCPE-129472](https://bugs.mojang.com/browse/MCPE-129472)）
* ​/teleport​命令中的旋转方向现在会相对于命令执行者，而不是目标。

修复

* 修复了启动游戏时的加载进度可能会卡在66%的问题。（[MCPE-168284](https://bugs.mojang.com/browse/MCPE-168284)）
* 修复了在iOS平台上启动游戏时可能发生的崩溃。
* 修复了在PC平台上启用光线追踪时，告示牌不会显示其文本的漏洞。（[MCPE-167638](https://bugs.mojang.com/browse/MCPE-167638)）
* 修复了玩家在连接到服务器或Realms后加载本地游戏时会加载错误数据的问题。（[MCPE-164765](https://bugs.mojang.com/browse/MCPE-164765)）
* 现在玩家首次启动游戏时会收到启用文本转语音选项的提示。
* 修复了在PlayStation平台上无法购买或续期Realms的问题。

</details>
