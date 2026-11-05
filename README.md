# ZJGiscus

个人博客 [ZJBlog](https://www.zhijie.online) 的评论后端仓库：站点评论区由 [giscus](https://giscus.app) 驱动，评论数据全部存放在本仓库的 GitHub Discussions 中。本仓库不含源码，仅承载评论。

## 工作方式

- 评论以 discussion 承载，`pathname` 映射：每篇页面一个 discussion,标题即页面路径（如 `blogs/markdown-demo/`）,访客评论以回复形式挂在下面
- **Announcements** 分类是 giscus 的配置分类：仅维护者可开首层主题（由 giscus bot 在首条评论时自动创建）,普通访客只能回复——防灌水
- 访客在站点评论区发言无需本仓库权限；也可以直接在 GitHub 上回复对应 discussion
