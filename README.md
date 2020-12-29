# NightModeForDouyu.com
Stylus浏览器插件斗鱼夜间模式样式备份。

—— （根据本人自己的使用习惯制作，所以...你懂的）——

1、常用页面夜间模式全覆盖
2、去除广告
3、去除导航栏中游戏等无用杂项
4、部分icon更换使之更符合当前主题
5、自定义屏蔽，可选是否屏蔽弹幕等级、铭牌等元素

⭐建议使用H5播放器（可以屏蔽播放器内元素）⭐

⭐建议开启Stylus选项里的即时注入模式⭐

⭐如有问题请到我的网站【www.asifadeaway.com】点击右下角会话按钮给我留言⭐

最近看斗鱼越来越少了，新增功能或改版啥的我都不知道，所以我新增夜化会滞后，见谅。

*斗鱼给部分直播间的装修毫无规律可言，修复一个直播间另一个可能就会出问题，非常恶心人，所以只靠样式来处理是不行的，如果想达到直播间页面只留播放器的效果的话，请在Tampermonkey上安装本人的这个非常简单的小脚本【斗鱼直播间播放器置顶：https://greasyfork.org/zh-CN/scripts/399600】配合本样式使用即可。此脚本为半公开，只能通过链接访问。

目前已知bug：启用本样式会导致斗鱼首页下方推荐直播缩略图不显示以及部分分类直播不加载。此bug暂不清楚是什么原因导致的。因为我一直是直接把关注页收藏到书签的，几乎不看首页所以没发现这个情况，暂时也不知道该怎么修复。不过这里也提供一个解决办法：点击浏览器工具栏stylus图标，再点击本样式名称后面的操作菜单（竖着的三个点），勾选排除当前链接。这样可以在首页不启用本样式，即可解决问题。

---------------------------------------------------

2020-12-29 18:45 —— 适配斗鱼最新改动。

2020-12-22 21:57 —— 在假扮主播的弹幕前增加“假主播”的标签提示，修复弹幕收藏面板位置不正确的问题，其他优化。

2020-12-05 20:18 —— 本人自己的网站全面升级为Https，自此使用本样式浏览器将不会再显示网站存在不安全内容。

2020-11-05 18:47 —— 修复点击取消关注不显示确认弹窗的问题。

2020-10-09 19:50 —— 新增粉丝弹幕颜色保留开关，不影响自定义用户发言颜色使用。

2020-10-07 22:27 —— 新增直播间弹幕侧上方贡献周榜、贵宾、粉丝团屏蔽选项。

2020-09-28 21:14 —— 优化部分图标及元素夜化，新增直播间右侧用户及主播的昵称和发言颜色自定义，方便设定为自己觉得更合适的颜色。

2020-09-15 09:15 —— 修复部分直播间被错误屏蔽的问题。

2020-09-14 21:36 —— 增加自定义屏蔽选项并增加之前被默认屏蔽部分元素夜化。

2020-09-11 19:30 —— 加入自定义屏蔽选项，目前暂时只有用户等级屏蔽，后续看需要增加。更改屏蔽选项后需点击样式更新按钮才可生效。

2020-09-10 17:27 —— 先占个坑，刚才试了几次都上传不了更新，提示stylish内部错误，只能等等再更了，后续会加上屏蔽选项，可以自由选择部分内容是屏蔽还是不屏蔽。

2020-04-05 16:37 —— 修复屏蔽直播间装修会把播放器也屏蔽的问题，完美修复方法见上方说明。

2020-03-04 19:51 —— 适配直播间部分更新。

2020-02-04 20:01 —— 屏蔽播放器弹幕点赞提示。

2020-02-03 19:37 —— 修复关注分组夜化。

2019-11-25 16:44 —— 屏蔽直播间各种充值活动。

2019-10-21 17:09 —— 修复屏蔽直播间新活动会把播放器同时屏蔽的问题。

2019-10-05 11:35 —— 新增主播点评夜化及其他细节优化，斗鱼不知道啥时候新增的「播单」功能对我来说没用，且改起来比较费劲实在懒得搞我就直接屏蔽了。

2019-09-02 17:26 —— 细节优化。

2019-08-16 19:48 —— 新增关注页“添加分组”功能夜化以及其他细节优化。

2019-08-03 17:38 —— 优化直播间“收藏的弹幕”显示效果。

2019-07-16 16:20 —— 小修小补，最近斗鱼看得少了。

2019-06-24 15:55 —— 刚从台湾回来，把这段时间没看斗鱼又更新的部分适配了。

2019-04-23 21:18 —— 鱼新版关注页卡片右上角增加直播中角标。

2019-04-22 21:18 —— 适配斗鱼新版关注页。

2019-02-25 16:03 —— 屏蔽直播分类轮播广告，由于广告屏蔽后会空一块，所以加了个屏蔽提示。

2019-02-22 10:14 —— 修复直播播放器网页全屏错位问题。

2019-02-21 09:43 —— 修复排行榜夜化以及优化部分icon。

2019-02-20 18:31 —— 修复头部导航存在的问题。

2019-02-17 16:50 —— 修复部分icon错误。

2019-02-15 21:54 —— 部分细节优化。

2019-02-15 08:48 —— 修复我的关注页面部分错误。

2019-02-14 23:48 —— 狗日的斗鱼又改版了，花了好几个小时适配新版，连我的Switch暗黑三都没来得及玩。目前斗鱼只改了部分页面，后面估计还有大动作，操斗鱼。

2019-01-26 15:43 —— 修复直播间右侧弹幕被错误屏蔽的问题（我之前发现了这个情况但我以为是自己把斗鱼弹幕屏蔽等级调得太高就没在意- -没想到是我自己把弹幕误伤了...

2019-01-18 10:54 —— 新增赛事页面夜化及赛事直播间无用元素屏蔽，其他页面细节优化。

2019-01-16 19:34 —— 修复礼物宝箱被屏蔽的问题。

2019-01-16 18:37 —— 修复H5播放器黑屏问题。

2018-11-17 18:37 —— 部分细节优化。暴力屏蔽直播间所有活动元素，可能会有误伤。

2018-11-08 20:44 —— 修复直播分类页"列表页分区定制化"被直播间列表错误遮挡的问题，并增加夜化。

2018-11-01 20:41 —— 更换直播载入图片（H5播放器），更换播放器控制栏icon颜色使之符合当前主题。

2018-10-22 22:21 —— 修复因斗鱼更改部分元素命名导致夜化失效的问题。

2018-09-12 14:56 —— 去除屏蔽指定等级用户弹幕，斗鱼现在自带此功能。

2018-09-06 09:30 —— 优化细节及直播间去活动化。

2018-08-15 15:02 —— 增加由uBlock广告屏蔽插件自动屏蔽的广告。

2018-07-13 21:06 —— 屏蔽全站广告（之前是一直在开了去广告插件的情况下做的所以部分广告并没有看到，重装了浏览器才发现还有些广告没有去掉//= =...）

2018-06-29 20:10 —— 各种细节优化，修改Chrome浏览器（需进入 chrome://flags 开启 Overlay Scrollbars）滚动条使之符合当前主题。

2018-06-09 18:38 —— 各种细节优化，播放器右侧弹幕池里自己的弹幕更显眼。

2018-05-24 11:38 —— 直播间H5播放器控制栏icon修改。

2018-05-19 11:23 —— 新增直播间H5播放器右键菜单夜化，Flash播放器请右键选择切换H5播放器。

2018-04-24 15:53 —— 新增搜索结果页面夜化并更换部分icon颜色使之符合当前主题。

2018-04-24 15:04 —— 去除弹幕列表点击用户名后弹出的卡片屏蔽并夜化。

2018-04-20 10:37 —— 优化竞猜夜化，继续更换竞猜icon使之符合当前主题。

