# :basketball: SprintNBA

## 完整的NBA第三方Android客户端，包含NBA头条新闻、视频集锦/赛场花絮、比赛直播（目前支持比赛前瞻、文字直播、球队及球员技术统计、视频直播(企鹅推出了球队通、联盟通... 简直不能忍啊！！)）、球队战绩排行、球员数据排名、虎扑论坛专区（已实现发帖与回复功能）、球队及球员的详细资料。

## 声明

本项目部分API来自NBA中文官网与虎扑体育，纯练手之作，个人未从中获取任何利益，其所有内容均可在NBA中文官网与虎扑体育获取。数据的获取与共享可能会侵犯到NBA中文官网与虎扑体育的权益，若被告知需停止共享与使用，本人会立即删除整个项目。

## 项目

本项目采用 MaterialDesign + MVP + Retrofit2 开发。项目的大部分功能已经完成，并在百度手机助手等应用商店上架V1.1版本。目前正在不断完善中，喜欢的话不防给个star哈。

## 重要更新

### V2.0
1. 增加比赛视频直播
2. 优化比赛视频直播的稳定性。支持换源

### V1.1
1. 由于腾讯视频对真实地址解析后播放进行了加密，故采用新方法进行真实地址解析，若遇到不可播放的视频，可点击右上角跳转到内嵌网页播放。
2. 增强UI体验。修复一些bug
3. 若初次体验V1.0 导致V1.1应用自动更新无法下载，则应到设置->应用->SprintNBA下，授予SD读写权限。

### V1.0
初次版本，含NBA新闻、视频花絮、赛程及文字直播、技术统计、球队及球员数据排行、详细资料，虎扑论坛专区。

## 下载
- APK本地下载：[SprintNBA-2.0.apk](https://raw.githubusercontent.com/smuyyh/SprintNBA/master/app/release/SprintNBA-2.0.apk)

- 百度手机助手应用商店：[SprintNBA-2.0](http://shouji.baidu.com/software/11090327.html)

- 百度91无线：[SprintNBA-2.0](http://apk.91.com/Soft/Android/com.yuyh.sprintnba-3-2.0.html)

- 安卓市场：[SprintNBA-2.0](http://apk.hiapk.com/appinfo/com.yuyh.sprintnba/3)

## TODO

*   [ ] 代码优化
*   [ ] 虎扑论坛部分功能暂未完善
*   [ ] 单支球队赛程
*   [ ] 优化相关视频播放。腾讯视频真实地址提取功能不稳定，导致部分视频不能播放。
*   [ ] 部分BUG修复（有疑问欢迎提[issue](https://github.com/smuyyh/SprintNBA/issues/new)）

## 应用截图

友情提示：高清图片，耐心等待哟~~

- **头条新闻**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_news_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/news_detail_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/news_img_1.png?raw=true" width="280"/>

<br>

- **比赛视频/赛场花絮**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_video_list_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_video_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/video_play.png?raw=true" width="280"/>

<br>

- **比赛相关**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_schedule_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/match_data_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/match_live_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/match_video_live_source.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/match_video_live.png?raw=true" width="280"/>

<br>

- **球队/球员 相关**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_team_sort_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_player_stats_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/player_list_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/player_detail_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/team_detail_1.png?raw=true" width="280"/>

<br>

- **虎扑论坛相关**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_hupu_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/thread_list_1.png?raw=true" width="280"/>
<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/thread_detail_1.png?raw=true" width="280"/>

<br>

- **其他**

<img src="https://github.com/smuyyh/SprintNBA/blob/master/screenshot/home_other_1.png?raw=true" width="280"/>
