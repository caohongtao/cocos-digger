#digger
基于Quick-Cocos2d-x的鼹鼠挖地游戏。
demo：http://share.weiyun.com/719466c354a6a21d17f99eee9df8c08b
#玩法介绍
![输入图片说明](http://git.oschina.net/uploads/images/2015/1014/222620_f2846c9b_132413.jpeg "在这里输入图片标题")

**规则：**游戏的主角是一只小鼹鼠，他被蛇从地面追赶到地下。这条蛇会紧追不舍，因此鼹鼠要存活下去就需要无尽地往下挖地。

**操作：**左右下。如果点击方向后，该方向没有石块阻挡，则移动一格。如果有石块，则挖掘。

**石块：**每次挖掘，同被挖掘石块相邻的同色石块全部消失。同时悬空的石块会往下掉落。下落的石块会砸死小鼹鼠，因此移动的过程需要注意躲避。但是下落的石块在碰到左右两侧同色的稳定石块时，会粘连住。

**氧气：**鼹鼠每次挖一下，都会耗费一点氧气。但是挖掘的过程中会有各种道具，氧气便是其中一种，吃了后，可以大幅恢复氧气值。抢吃氧气的同时又要判断石块的掉落轨迹，很是刺激，操作犀利的大神可以挖的非常快且远。

**道具：**可以积攒的道具有3个，依次是蘑菇，栗子，可乐。蘑菇释放后鼹鼠会放个屁，将蛇臭晕若干时间。栗子释放后，鼹鼠吃伟哥，每次可以挖掘整排石块，直接拾取整排道具，且挖掘不消耗氧气。可乐释放后，会将蛇击退若干距离。
还有些不可积攒，直接使用的道具。钻头：有些特殊石块需要挖多次，钻头可以让挖掘力短时间内提升。钻石，金币等奖励。炸弹等陷阱。
#待改进
游戏基本完整，各界面交互正常，音效，暂停，死亡画面都切换正常，只差接入收费sdk。
![输入图片说明](http://git.oschina.net/uploads/images/2015/1014/230754_5ff8ebd3_132413.jpeg "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2015/1014/230738_f2e024dc_132413.jpeg "在这里输入图片标题")