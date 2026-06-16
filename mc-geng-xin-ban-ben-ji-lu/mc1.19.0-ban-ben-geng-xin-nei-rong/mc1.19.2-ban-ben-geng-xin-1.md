# MC1.19.7版本更新



{% hint style="success" icon="rotate" %}
## **更新要点**

**【更新】1.19.7版本补丁更新公告：BC1.19.7**

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

<summary><strong>实验性</strong><br></summary>



</details>

<details>

<summary><strong>修复</strong></summary>

性能与稳定性

* 游戏不再会在玩家浏览市场时崩溃。
* 修复了刷怪蛋相关的崩溃。（[MCPE-159302](https://bugs.mojang.com/browse/MCPE-159302)）
* 现在会防止客户端或服务端上的传送门在低渲染距离下出现不同步。（[MCPE-158167](https://bugs.mojang.com/browse/MCPE-158167)）
* 修复了从下界和末地返回主世界时可能发生的崩溃。
* 进入新手硬币包界面时游戏不再会崩溃。
* 提升了使用/locate biome​命令时的性能，以减轻服务器在搜索距离较远的生物群系时产生的卡顿。（[MCPE-157609](https://bugs.mojang.com/browse/MCPE-157609)）
* 修复了缺失如游戏手柄等连接设备时可能发生的崩溃。
* 修复了村民在交易过程中改变职业时发生的崩溃。现在村民在交易过程中改变职业时会关闭交易界面。
* 修复了活塞在可移动方块或箭附近伸缩时可能发生的崩溃。
* 修复了在同一刻内传送和杀死一个实体时可能发生的崩溃。

游戏内容

* 更改了流浪商人的生成机制以匹配Java版，其不再会生成于水中、熔岩中或地下。（[MCPE-46911](https://bugs.mojang.com/browse/MCPE-46911)）
* 修复了弓、弩和三叉戟在初次使用时可能无法正常使用的问题。（[MCPE-159467](https://bugs.mojang.com/browse/MCPE-159467)）
* 修复了在创造模式下新的荒野更新音乐不能在对应生物群系中播放的问题。
* 修复了渔夫村民无法在最大等级下收购船的问题。
* 现在远古城市中心里通往红石电路房间的隐藏门会正确打开或关闭。（[MCPE-156718](https://bugs.mojang.com/browse/MCPE-156718)）
* 熔岩桶未能被放置或提供给部分方块时，其中的熔岩不再会消失。（[MCPE-50664](https://bugs.mojang.com/browse/MCPE-50664)）
* 修复了远程攻击生物的武器附魔不会正常生效的问题。（[MCPE-113623](https://bugs.mojang.com/browse/MCPE-113623)）
* 修改了生物在紫水晶类方块上行走时发出的脚步声的音量。
* 修复了部分具有耐久度的物品无法通过创造模式物品栏获取的问题。
* 现在远古城市中会更频繁地生成幽匿斑簇。（[MCPE-154229](https://bugs.mojang.com/browse/MCPE-154229)）
* 玩家进入坐标位于Y=-21以下的下界传送门后不再会受到伤害。（[MCPE-154888](https://bugs.mojang.com/browse/MCPE-154888)）
* 修复了记分板上的分数不能正确排序的问题。（[MCPE-141427](https://bugs.mojang.com/browse/MCPE-141427)）
* 修复了使用/kill​命令清除浮漂实体后会有掉落物的问题。（[MCPE-142329](https://bugs.mojang.com/browse/MCPE-142329)）
* 玩家的灵魂疾行魔咒现在可以正常地在灵魂沙上生效。（[MCPE-157152](https://bugs.mojang.com/browse/MCPE-157152)）
* 修复了导致health\_boost​显示错误的生命值，并且会在玩家死后将其隐形，使其无法与世界进行交互的漏洞。
* 现在交易时村民会根据输入槽中的物品播放正确的音效。（[MCPE-152555](https://bugs.mojang.com/browse/MCPE-152555)）
* 远古城市中的生物头颅现在拥有与Java版相匹配的旋转方向。（[MCPE-153547](https://bugs.mojang.com/browse/MCPE-153547)）
* 现在指定format\_version​为1.19.20或更高版本时，会在根定义中启用事件过滤器以通过独立于序列或随机的方式来进行计算。
* 修复了从生命提升效果中得到的额外生命值无法被保留的问题。（[MCPE-153504](https://bugs.mojang.com/browse/MCPE-153504)）

生物

* 北极熊在受到攻击时不再会逃跑。
* 蝌蚪在陆地上的扑腾速度现在和Java版以及其他鱼类更加接近。（[MCPE-154316](https://bugs.mojang.com/browse/MCPE-154316)）
* 现在玩家穿戴上金质盔甲后，猪灵会停止攻击。（[MCPE-65516](https://bugs.mojang.com/browse/MCPE-65516)）
* 无职业的僵尸村民现在可以搭乘矿车或船。（[MCPE-76831](https://bugs.mojang.com/browse/MCPE-76831)）
* 劫掠兽现在可以摧毁红树树叶、杜鹃花丛、杜鹃树叶、洞穴藤蔓、垂滴叶、孢子花以及垂根。（[MCPE-156551](https://bugs.mojang.com/browse/MCPE-156551)、[MCPE-125322](https://bugs.mojang.com/browse/MCPE-125322)）
* 现在会在放置自定义生物桶后生成对应的生物。
* 修复了在放置生物桶时生成顺序的问题，现在所有被施加的活动对象属性都可以正常加载。
* 悦灵现在能够在船上捡起和投掷物品。（[MCPE-156377](https://bugs.mojang.com/browse/MCPE-156377)）
* 悦灵现在总是能够捡起掉落物形式的脚手架。（[MCPE-157512](https://bugs.mojang.com/browse/MCPE-157512)）
* 悦灵现在会在唱片机播放的音乐结束时正确停止跳舞。
* 悦灵现在能够看向如玩家等目标。（[MCPE-158222](https://bugs.mojang.com/browse/MCPE-158222)）
* 鱼被放置在单独一格水中时不再会抖动。
* 修复了使用entity\_born​或on\_tame​事件生成狼时会生成出红色的狼的问题。
* 修复了女巫可能会停止自然生成的漏洞。沼泽小屋结构现在被设置为女巫在地表生成的地点。（[MCPE-60552](https://bugs.mojang.com/browse/MCPE-60552)）
* 末影龙不再能够摧毁哭泣的黑曜石、重生锚、光源方块、拒绝方块、允许方块、边界方块和拼图方块。（[MCPE-158343](https://bugs.mojang.com/browse/MCPE-158343)）
* 修复了导致拥有minecraft:behavior.sleep​意向的生物的碰撞箱缩小的问题。（[MCPE-46040](https://bugs.mojang.com/browse/MCPE-46040)）
* 降低了悦灵和蜜蜂卡在不完整方块中的概率。（[MCPE-155777](https://bugs.mojang.com/browse/MCPE-155777)）
* 现在监守者会检测到在幽匿感测体上潜行的玩家。（[MCPE-155804](https://bugs.mojang.com/browse/MCPE-155804)）
* 现在监守者可以自由下落20格，而不只是3格。（[MCPE-158304](https://bugs.mojang.com/browse/MCPE-158304)）
* 悦灵现在可以拾取和手中盔甲耐久度不同的盔甲物品。（[MCPE-158339](https://bugs.mojang.com/browse/MCPE-158339)）
* 现在在实体死亡后它们在世界中的数据会被删除。（[MCPE-155283](https://bugs.mojang.com/browse/MCPE-155283)）
* 修复了可能导致被保存的Y坐标大于或等于25的生物无法加载的问题。

方块

* 移除了红树木板、红树木楼梯和红树木台阶的英文名称中的单词“Wood”。（[MCPE-156791](https://bugs.mojang.com/browse/MCPE-156791)）
* 现在即使随机刻速度被设置为0，缠怨藤和垂泪藤也会在没有附着方块时掉落。（[MCPE-69305](https://bugs.mojang.com/browse/MCPE-69305)）
* 在没有完全成熟时，悬挂的红树胎生苗被精准采集附魔工具采集时不再会掉落任何物品。（[MCPE-156821](https://bugs.mojang.com/browse/MCPE-156821)）
* 沾泥的红树根现在可以横向放置。（[MCPE-153721](https://bugs.mojang.com/browse/MCPE-153721)）
* 在周边放置方块时，悬挂的红树胎生苗不再会改变颜色。（[MCPE-156570](https://bugs.mojang.com/browse/MCPE-156570)）
* 末地传送门框架的英文名称由“End Portal”更改为“End Portal Frame”。（[MCPE-76821](https://bugs.mojang.com/browse/MCPE-76821)）
* 紫水晶块的英文名称由“Amethyst Block”更改“Block of Amethyst”。（[MCPE-125821](https://bugs.mojang.com/browse/MCPE-125821)）
* 红树原木、红树木和去皮红树原木现在可用于合成营火。（[MCPE-157271](https://bugs.mojang.com/browse/MCPE-157271)）
* 现在物品栏中的营火可以被正确堆叠。（[MCPE-159398](https://bugs.mojang.com/browse/MCPE-159398)）
* 修复了活塞被手动破坏后可能不会掉落其自身的漏洞。（[MCPE-158314](https://bugs.mojang.com/browse/MCPE-158314)）
* 现在村民工作时发出的锻造台音效与玩家使用锻造台时相同。（[MCPE-79716](https://bugs.mojang.com/browse/MCPE-79716)）
* 钟不再能被点燃或被烧毁。
* 红树树叶和杜鹃树叶不再会阻止对应树木的生长。（[MCPE-154980](https://bugs.mojang.com/browse/MCPE-154980)）

幽匿类方块

* 如果两个事件同时发生，幽匿感测体现在会优先感应距离较近的那个。（[MCPE-155793](https://bugs.mojang.com/browse/MCPE-155793)）
* 如果两个事件同时发生且距离相同，幽匿感测体现在会优先感应振动频率较高的那个。
* 幽匿感测体现在感测到苦力怕爆炸的振动频率为15。
* 幽匿感测体现在感测到末地水晶爆炸的振动频率为15。（[MCPE-153733](https://bugs.mojang.com/browse/MCPE-153733)）
* 幽匿感测体现在感测到生物桶放置的振动频率为12。
* 幽匿感测体现在感测到发射器发射TNT的振动频率为12。
* 振动粒子的方向现在总是会朝着对应的幽匿感测体。（[MCPE-156648](https://bugs.mojang.com/browse/MCPE-156648)）
* 幽匿催发体现在会在催发时发出催发音效。（[MCPE-153562](https://bugs.mojang.com/browse/MCPE-153562)）
* 若keepInventory​游戏规则设置为true​，则幽匿催发体不再会在玩家死亡时蔓延。（[MCPE-157884](https://bugs.mojang.com/browse/MCPE-157884)）
* 幽匿催发体上有生物死亡时不再会覆上幽匿脉络。
* 幽匿催发体现在会在没有经验的生物在其附近死亡时蔓延。
* 幽匿感测体现在可以检测到蜜蜂、鸡、悦灵、幻翼和末影龙的飞行。（[MCPE-153725](https://bugs.mojang.com/browse/MCPE-153725)、 [MCPE-154055](https://bugs.mojang.com/browse/MCPE-154055)）
* 幽匿感测体现在可以根据振动发生的距离发出整个范围内的红石信号强度。之前版本中只会发出1到15级甚至更小范围的信号强度。
* 现在幽匿催发体被破坏后会掉落5点经验而不是20点。
* 幽匿斑块地物现在可以被放置在更多种类的方块上。（[MCPE-156669](https://bugs.mojang.com/browse/MCPE-156669)）

图形

* 修复了当玩家在拥有迅捷效果的情况下疾跑时视场角会出现的卡顿问题。
* 在数据驱动方块被镶嵌后，基于轴心点旋转的几何箱现在会围绕着正确的轴心点旋转。
* 修复了雪层下落在玩家上方时玩家能够透视的问题，因此雪层现在覆盖住玩家的视线时会显示为固体方块。（[MCPE-150709](https://bugs.mojang.com/browse/MCPE-150709)）
* 修复了Windows上RTX功能启用时，发光方块的光点会错误聚集在某处的问题。（[MCPE-159485](https://bugs.mojang.com/browse/MCPE-159485)、[MCPE-159488](https://bugs.mojang.com/browse/MCPE-159488)）

用户界面

* “转动视角”的提示现在会显示玩家重新设置的热键而不是默认的按键。
* 猪装备上鞍后的骑乘提示的英文名称由“Mount”更改为“Ride”，以匹配其他可骑乘动物。
* 为大型图标嵌入纹理（如玩家手中的物品）的操作加入了内容日志警告。
* 修复了在iOS上使用鼠标和键盘时，若滚动条的一部分落在滚动条外边，玩家无法将鼠标悬停在滚动条内的UI元素上的问题。这是滚动条聚集在最近的非修剪元素的结果。
* 现在物品栏中带有can\_place\_on​组件的方块的悬停文本顺序现在和游戏的保存顺序一致。（[MCPE-153516](https://bugs.mojang.com/browse/MCPE-153516)）
* 移除了Oculus平台上的控制器设置选项卡。
* 现在山羊角的音效在设置中被划分在“唱片机/音符盒”音效分类中。（[MCPE-154885](https://bugs.mojang.com/browse/MCPE-154885)）
* 修复了加入服务器功能不会保存IPV6地址的问题。（[MCPE-66233](https://bugs.mojang.com/browse/MCPE-66233)）

Realms

* 更新了Realms Plus上的FAQ，以阐明所有平台上的基岩版均可购买Realms Plus。
* 修复了创建新的Realms后会进入游玩界面，而不是返回创建新世界界面的问题。
* 现在可以在VR平台上使用Realms反馈的截图键。

**其他修复**

* 修复了一些游戏过程中可能发生的崩溃。
* 修复了村民的职业不会表现在其服装上的问题。（[MCPE-160475](https://bugs.mojang.com/browse/MCPE-160475)）
* 修复了在部分设备上游玩时会出现图形缺陷的漏洞。（[MCPE-160491](https://bugs.mojang.com/browse/MCPE-160491)、[MCPE-160758](https://bugs.mojang.com/browse/MCPE-160758)、[MCPE-160451](https://bugs.mojang.com/browse/MCPE-160451)）
* 修复了悬浮在生物上方的名称会稍微偏移的漏洞。（[MCPE-160254](https://bugs.mojang.com/browse/MCPE-160254)）
* 修复了市场世界中的部分方块会在Realms上显示为数据更新方块的问题。
* 付费表情不再能被免费装备。
* 修复了在部分平台上加载装有纹理包的世界时可能出现的崩溃。（[MCPE-160800](https://bugs.mojang.com/browse/MCPE-160800)）
* 修复了当删除世界时其在云端同步的世界不会被删除的漏洞。
* 修复了Xbox上在仍有存储空间的情况下出现内存已满提示的问题。

</details>

