# PureMusicGPL3
原微博See作者全新作品PureMusic棉花音乐疑似违反GPLV3协议

## 拿国外人的GPLV3开源项目改没问题，GPLV3没说限制收费什么的

# 但不要这么离谱去违反协议，丢中国人脸

这个软件中发现大量RetroMusicPlayer源码内容，大量RetroMusicPlayer原作者原软件包名信息，**并未在此软件内包括你的软件主页并未发现任何相关版权说明以及GPLV3开源说明**（截至到2023年9月4日），请作者做出完整解释。
GPLV3 写道：
For example, if you distribute copies of such a program, whether gratis or for a fee, you must pass on to the recipients the same freedoms that you received. You must make sure that they, too, receive or can get the source code. And you must show them these terms so they know their rights.
你做为一个多年的开发者，不可能不知道GPLV3协议。
明知软件为GPLV3协议而进行Copy改动并写道：Thanks RetroMusicPlayer UI，这不仅仅是UI而是大量移植，是在RetroMusicPlayer原项目直接改动，而不遵守GPLV3协议，明显违反。
比最近的CEC-IDE更**

https://github.com/pure-music/PureMusic/issues/4

![image](https://github.com/vwps/PureMusicGPL3/assets/143679824/3f38a72d-216e-4b86-9777-4a92247f9e4d)

此软件1.2.5.1安装包已在仓库中

本页更新时间：2023年9月4日

-------

2023年9月4日12:51
作者（疑似）回复：Github也回复你，
**说不同点**：
RetroMusicPlayer基于系统播放器，Pure基于exoplayer，支持网络歌曲（云盘）播放。
RetroMusicPlayer仅管理本地歌曲文件，读取android系统媒体数据库， Pure使用sqldelight管理本地歌曲和云盘歌曲。
RetroMusicPlayer页面跳转基于Android官方的androidx.navigation，Pure用的是我自己写的独立的页面管理器。
RetroMusicPlayer歌手信息刮削用的deez的服务，Pure用的是spodify的服务。
RetroMusicPlayer图片加载和缓存逻辑和Pure不同。
RetroMusicPlayer的数据刷新依赖Android原生的Live Observer， Pure依赖EventBus。
**相同点**： 这部分我没有什么修改，另外这部分我也将在迁移。 也可以开源。
UI和主题，交互相同。
歌曲队列的管理逻辑。

我的回复：
v wps:
只要包含原来项目gpl3代码就需要开源，你没包含吗？
建议阅读相关资料并改正
包含原来项目，原来项目是gpl3项目，那么需要PureMusic完整开源代码
一些比较轻的协议也需要注明原作者名称包括哪部分修改了

2023年9月4日12:51左右
TG频道管理员删除了我部分发言（我在多个频道评论下留言上面信息），TG管理员（不知道是不是作者）删除了我6条。


