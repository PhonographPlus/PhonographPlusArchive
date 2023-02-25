**Preview 2022.6.30**
**Commit log**: https://github.com/chr56/Phonograph_Plus/compare/preview_0627...preview_0630

**CN**
与前一预览版相比:
- 修复 播放列表歌曲封面必不显示
- 修复 "最常听的歌曲"为空时无法刷新
- 开发 重构大量历史代码 (可能出现状态栏等色彩异常, 多选模式异常等问题,请及时反馈)

预览版对比稳定版新增功能汇总:
- 新增 全新的文件夹视图: 
— 与媒体库其他视图并列; 
— 从MediaStore读取歌曲文件(可大幅改善在Android10以上的性能), 当然也可以使用旧方式; 
— 尝试完全支持浏览外部可移除存储设备(如SD卡等); 
— 使用下拉刷新;
— 允许按照文件名,文件大小,添加日期,修改日期排序;
- 改进 重构播放列表详情, 简化编辑
- 改进 "最常听的歌曲"计算方法
- 新增 支持刷新并重新计算"最常听的歌曲"播放列表
- 修复 多选时菜单图标颜色错误
- 改进 小幅度重构专辑页面
- 开发 更新依赖（导致滚动条外观有所不同）
- 开发 重构大量历史代码, 包括
— 专辑详情
— 播放列表详情
— 文件扫描
— 排序
— 列表控制菜单
— 主题控制(可能出现状态栏等色彩异常)
— 多选模式(可能发生异常)
— 播放器托盘

已知问题:
- 专辑详情转场动画异常
- 艺术家详情多选冲突
- 文件视图路径现阶段不显示历史记录

**EN**
Compared to the previous preview:
- Fix: covers of playlist songs not loading
- Fix: "My Top Tracks" could not be refreshed when empty
- Development: refactoring of plenty of historical codes (may have bugs such as abnormal status bar color or glitch behavior in multi-selection mode, please provide feedback in time)

New features added in Preview since latest Stable:
- Add: a brand new Folders Page: 
— Among with other pages of the Library; 
— Read song files from MediaStore (significantly better performance on Android 10 and above), but you can still use old method to read song files; 
— (Try to) fully support browsing external removable storage devices (such as SD cards, etc.);
— Use sweep-down-refresh;
— Allow sorting files by file name, file size, date added, date modified;
- Improve: refactor Playlist Detail and simplify editing
- Improve: calculation for "My Top Tracks"
- Add: support for force to refresh and recalculate "My Top Tracks" playlists
- Fix: wrong color of context menu icon when multiple selection
- Improve: minor refactoring of the album page
- Development: clean up the code of Album Details Page, and begin to handle with the plan about redesigning
- Development: refactoring of plenty of historical codes, including
— Album Detail
— Playlist Detail
— File Scanning
— Sort Order
— List Appearance Popup Menu
— Theme (may have bugs such as abnormal status bar color)
— Multi-selection (may have glitch behavior)
— Sliding Player Panel

Known Issues:
- Glitch Album Detail Transition Animation
- Multi-selection confliction in Artist Detail
- No path history for brand new File Page (currently)
