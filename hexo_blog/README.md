# hexo_blog

博客（langyuf.github.io）的图片目录，由博客仓库的 `tools/sync-notes.js`
自动把笔记配图同步到 `notes/` 下，其余目录手动维护。

| 目录 | 用途 | 博客侧引用位置 |
| --- | --- | --- |
| avatar/ | 头像（avatar.jpg） | _config.butterfly.yml `avatar.img` |
| wallpaper/ | 壁纸（wallpaper-1.jpeg） | _config.butterfly.yml `background` |
| site/ | favicon、404 占位、兜底图 | _config.butterfly.yml / _config.yml |
| covers/ | 首页轮播封面 | tools/notes.config.json `fileCover` |
| notes/ | 笔记配图，按主题分目录 | 文章正文（sync-notes 自动改写） |
| posters/ | 电影海报（待添加） | source/movies/index.md |
| music/ | 音乐封面（待添加） | source/music/index.md |
