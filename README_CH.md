# 第二届“独立营Indie Camp—48小时游戏创作挑战” 开发作品

![](https://pic1.cdncl.net/user/xfause/common_pic/23868c410228abc80beae17f0fffd35a.jpg?imageView2/2/w/1280)

## 背景及主题

开发时间为2018年12月7日至12月9日。

开发小组成员共五人，两位程序，两位美术，一位策划，我负责程序及策划。

本次游戏开发主题为：重生。

## 设计思路

重生这个题材说实话已经非常常见，拖尸类的机制和普通的Roguelike地牢类游戏都非常符合这个主题，因此在设计初我就决定无论从题材和游戏机制上都避开这些方面。

最后将重生的范围引申到整个世界、文明，游戏机制也顺势转化为回合卡牌策略过关游戏。

游戏背景是一个饱受人类过度开发，生态和人类自身生存都岌岌可危的一个世界。地图由六边形组成，游戏中共存在3类，每类各3个等级共9种建筑，加空地共10种单位，3类建筑分别为：自然建筑、废土地块、工厂建筑。不同等级的建筑占地面积，分别为1块基本单位，3块基本单位，7块基本单位。

游戏中另一个机制是卡牌系统，同样有3类各3级共9种卡牌，分别为神迹卡：可以将废土地块变为空地、灾难卡：可以将自然建筑和工厂建筑转变为工厂建筑、生长卡：将空白地块变成自然建筑。每种卡牌分为3级，对应等级的卡牌只能在对应等级的地块上整张使用，即2级神迹卡只能在2级废土上使用。每次随机五张卡牌给玩家使用，使用一张卡牌回合数+1，玩家可以选择重新发牌回合数同样+1。

游戏机制主要围绕两个数值展开：繁荣值和信仰值。每种地块具有自己的初始繁荣值和信仰值，因此每个关卡进入时会根据地图计算出两种数值。每种卡牌同样会对两种数值造成不同的影响，神迹卡大幅增加信仰值、灾难卡大幅降低繁荣值，小幅增长信仰值、生长卡小幅增加信仰值。同时使用卡牌后变化的地块也会对两种数值造成影响。过关条件为增加信仰值高于目标的同时不使得繁荣值低于目标。

为了游戏的趣味性和可重复挑战，原本想增加一个记录最少回合数通关的记录榜单，但由于时间原因无法完成。

另外一个比较大的缺陷是由于我对数值策划的能力不是很足，所以很多单位的数值设置和数值变化都是很简单的线性变化，此处可以改进，另外游戏其他可以改进的地方是卡牌种类和建筑种类。

## 截图

### 开发过程原型

![](https://pic1.cdncl.net/user/xfause/common_pic/1046adc7c45375b1f672100313887e10.jpg?imageView2/2/w/1280)

### 游戏内截图

![](https://pic1.cdncl.net/user/xfause/common_pic/346a4843957a01bdf2ee8ec75dd9e759.jpg?imageView2/2/w/1280)

## Demo下载

游戏demo下载：

链接: https://pan.baidu.com/s/14ZjtaHpOOVhaBr1dyfls9w 提取码: vued
