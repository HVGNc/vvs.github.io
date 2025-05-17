# MC1.18.1版本更新

{% hint style="success" %}
## 更新要点

**【更新】1.18.1版本补丁更新公告：BC1.18.1**

更新补丁版本：1.18.1 更新时间：2026-7-23&#x20;

更新内容：
{% endhint %}

<details>

<summary>新内容</summary>

**常规**

[选项](https://zh.minecraft.wiki/w/%E9%80%89%E9%A1%B9)

* 在存储设置中加入了“清除市场缓存”按钮。
  * 用于清除本地缓存数据，并不会删除已保存的游戏数据。

[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)

* 加入了“旁观模式”子选项。

`实验性 以下`内容需要开启[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)中的“旁观模式”子选项后才可使用。

游戏内容

[旁观模式](https://zh.minecraft.wiki/w/%E6%97%81%E8%A7%82%E6%A8%A1%E5%BC%8F)

* 现在属于[实验性玩法](https://zh.minecraft.wiki/w/%E5%AE%9E%E9%AA%8C%E6%80%A7%E7%8E%A9%E6%B3%95)中的“旁观模式”部分。
* 现在也可以通过`/`[`gamemode`](https://zh.minecraft.wiki/w/%E5%91%BD%E4%BB%A4/gamemode) `spectator`命令进入。

</details>

<details>

<summary></summary>



* 修复了在PlayStation上复制特定语言的备份世界时可能发生的崩溃。
* 修复了在Realms上游玩和聊天时可能发生的崩溃。
* 减少了钻石矿石的生成数量以匹配Java版。
* 修复了从其他维度返回主世界后移除光源导致的光照漏洞。（[MCPE-145828](https://bugs.mojang.com/browse/MCPE-145828)）
* 玩家重生或起床后不再遇到难以移动的问题。
* 加入一条警告提醒，解释在Android设备上将文件存储位置设置为外部时可能会面临数据丢失的风险。
* 修复了各种崩溃以及与Android多用户和Amazon Kids/Freetime有关的存储问题。（[MCPE-106524](https://bugs.mojang.com/browse/MCPE-106524)、[MCPE-107503](https://bugs.mojang.com/browse/MCPE-107503)、[MCPE-37685](https://bugs.mojang.com/browse/MCPE-37685)）
* 修复了在多人模式中当其他玩家离开玩家的渲染距离后模拟距离停止工作的问题。（[MCPE-147391](https://bugs.mojang.com/browse/MCPE-147391)）
* 当`checkForBlocks`为true并且目标位置被阻挡时，`/teleport`命令不再执行成功。
* 修复了当已经拥有最大数量的Realms时购买Realms的页面可能出错的问题。
* 优化了市场库存界面，并提高了内容的加载速度。

- 修复了某些情况下在PlayStation上保存一些较大世界时，会导致纹理受损或数据丢失的问题。（[MCPE-149193](https://bugs.mojang.com/browse/MCPE-149193)）
- 现在玩家与容器交互时又会正确打开物品栏界面了。（[MCPE-148531](https://bugs.mojang.com/browse/MCPE-148531)）
- 修复了附近生物数量过多时破坏方块、打开箱子或进入传送门会出现延迟或无响应的问题。（[MCPE-149214](https://bugs.mojang.com/browse/MCPE-149214)）
- 修复了将世界升级至1.18后其中的基岩层不会正确替换为深板岩的问题。（[MCPE-149251](https://bugs.mojang.com/browse/MCPE-149251)）

* 修复了一些游戏过程中可能发生的崩溃。
* 修复了能够通过熔炉不正确获得经验的问题。（[MCPE-152227](https://bugs.mojang.com/browse/MCPE-152227)）
* 修复了重载RTX世界时屏幕会变黑的问题。（[MCPE-152645](https://bugs.mojang.com/browse/MCPE-152645)）
* 修复了Android设备上远处方块的纹理会出现颗粒、扭曲和失真的问题。（[MCPE-141316](https://bugs.mojang.com/browse/MCPE-141316)）
* 修复了iOS设备上的流动的水和熔岩的纹理无法正确渲染的问题。
* 修复了各种帧率问题，尤其是配置较差的移动设备。（[MCPE-142934](https://bugs.mojang.com/browse/MCPE-142934)）
* 生物不再可以生成在按钮上。（[MCPE-153897](https://bugs.mojang.com/browse/MCPE-153897)）
* 修复了多次保存和重置区块时会使区块加载出现延迟、性能问题以及游戏性能不稳定的问题。（[MCPE-154110](https://bugs.mojang.com/browse/MCPE-154110)、[MCPE-154278](https://bugs.mojang.com/browse/MCPE-154278)）
* 修复了更新至1.18.30后无法打开世界的问题。
* “音乐之声”成就现在会在条件满足时达成。
* 修复了在Nintendo Switch上无法打开市场的问题。（[MCPE-154120](https://bugs.mojang.com/browse/MCPE-154120)）
* 修复了在市场购买商品时可能会出现无限的加载界面的问题。
* 提升了部分Android设备上的游戏性能。（[MCPE-142934](https://bugs.mojang.com/browse/MCPE-142934)）
* 修复了Nintendo Switch上的区块加载和卡顿问题。（[MCPE-154110](https://bugs.mojang.com/browse/MCPE-154110)）



</details>

<details>

<summary>改进</summary>

**改进**

* 启用了部分后端服务的配置更改。

</details>

