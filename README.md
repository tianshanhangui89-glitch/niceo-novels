# Niceo 小说 · 数据源

给「Niceo 小说」Android App（com.gui.novels）提供在线数据。App 启动/下拉刷新时拉取，新章无需重装。

- `books.json`：书架索引
- `books/<id>/index.json`：每本书目录（章节号、标题、hash）
- `books/<id>/chapters/NNN.md`：每章正文（Markdown），按需拉取并离线缓存

地址：`https://raw.githubusercontent.com/tianshanhangui89-glitch/niceo-novels/main/books.json`（主）、
`https://cdn.jsdelivr.net/gh/tianshanhangui89-glitch/niceo-novels@main/books.json`（备）。

由 `/workspace/novel-reader/publish_novels.sh` 自动生成，请勿手工编辑。
