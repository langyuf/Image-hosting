# Image-hosting

个人图床仓库。博客等项目的图片统一存放在这里，通过 jsDelivr CDN 引用：

```
https://cdn.jsdelivr.net/gh/langyuf/Image-hosting@main/<路径>
```

> 仓库必须保持公开，jsDelivr 才能读取；推送后首次访问会有短暂数据同步延迟。

## 目录结构

```
hexo_blog/            博客（langyuf.github.io）图片
├── avatar/           头像
├── wallpaper/        网站壁纸
├── site/             站点杂项（favicon、404、兜底图等）
├── covers/           首页轮播图封面
├── notes/            笔记文章配图（linux/、ml/ 等按主题分类）
├── posters/          电影海报（待添加）
└── music/            音乐封面（待添加）
```

## 使用约定

- 文件名用英文/数字，避免中文和空格带来的 URL 编码问题
- 图片按用途放进对应目录，不要堆在根目录
- 引用路径统一带 `@main` 锁定默认分支，例如：
  `https://cdn.jsdelivr.net/gh/langyuf/Image-hosting@main/hexo_blog/site/favicon.ico`
