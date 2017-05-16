## About

一直想做一个类似`Lifeline`的游戏，采用直接对话而不是选择的模式。

这样代入感更强，当然，也就需要一些更智能的算法。比如机器学习，深度学习。

接触到`itchat`这个库，发现可以通过微信实现。这样降低开发难度，也无须开发独立的软件。

做了一个demo，效果还是可以。

## 问题：
机器人不会稳定不掉线，一旦掉线重启后，所有玩家的记录就会丢失了。

因为TX方面封装加密了用户ID，通过web接收到的都是加密后的字符串，而每次重登录后，同一用户id都不一样。

## 可能的解决办法：
让用户设置用户名和密码，存储进度。虽然这样代入感要弱一点，但也只有这样了目前。

## 后续
- [x] demo
- [ ] 更精致、吸引人的剧情...