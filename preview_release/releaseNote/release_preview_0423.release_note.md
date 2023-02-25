**Preview 0.2.4-beta 2022.4.23**

This is a **Preview** version.
此为**预览版**！
Preview versions might have potential bugs.
注意可能存在潜在问题!

**CN**
1. 修复 专辑与艺术家页面下,歌曲与专辑或艺术家(在同一专辑但艺术家不同的情况下)配对(解析)错误
2. 优化 专辑与艺术家解析机制(加载时间可能会延长)
3. 新增 专辑与艺术家以及流派支持按歌曲(或专辑)数量排序
4. 修复 歌曲在使用"添加日期"的排序依据下,滚动条不提示日期
5. 改进 使用通知提示大多数耗时操作而不是各种对话框
6. 改进 使用通知提示更多内部错误
7. 开发 增强混淆
8. 开发 清理代码, 替换所有AsyncTask

**注意**
1. 此次更新涉及存储播放队列数据库的改动,若发现当前播放队列异常,请清除数据
2. 此次更新涉及排序方式设置的改动,需要重新设置排序方式



**EN**
1. Fix: an error in pairing (parsing) between songs and albums or artists (in the case of the same album but different artists) under the album and artist page
2. Optimize: album and artist parsing mechanism (loading time may be extended)
3. Add: albums and artists and genres to support sorting by number of songs (or albums)
4. Fix: that the scroll bar does not prompt the date when the song is sorted by "Add Date"
5. Improve: notifications for most time-consuming operations instead of various dialogs
6. Improve: notification for more internal errors
7. Development: Enhanced Obfuscation
8. Development: clean up code, replace all AsyncTask

**Note**
1. This update involves changes to the storage play queue database. If you find that the current play queue is abnormal, please clear the data
2. This update involves changes to the sorting method settings, and the sorting method needs to be reset

**Commit Changelog**: https://github.com/chr56/Phonograph_Plus/compare/v0.2.3-RC2...preview_0423