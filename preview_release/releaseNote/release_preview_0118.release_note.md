**Preview 0.1.0 2022.1.18**

**注意:此版本问题<del>极多</del>, 谨慎使用**

开发 清理代码
开发 移除ButterKnife
开发 使用AGP 7.0.4 (以及Gradle7.1.1) 构建
开发 升级Glide(3.8.0 -> 4.12.0), 可能引起若干封面加载问题

修复 播放列表更改(新建/改名/删除)后,未能及时刷新（仅限App内操作）
改进 再删除播放列表失败后, 可尝试使用SAF(Storage Access Framework, 存储访问框架)授权目录后再次尝试删除（目前交互体验不佳, 且可能误删文件!!!）
改进 对于Android 10 (Q)以上版本用户, 使用SAF创建和复制(单个)播放列表
改进 对于Android 8 (O)以上版本用户, 使用SAF授权后再追加歌曲至已有播放列表（目前交互体验不佳）

完整日志详见: https://github.com/chr56/Phonograph_Plus/compare/v0.0.8...preview_0118