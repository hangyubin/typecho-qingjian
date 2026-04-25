```markdown
# 清简 (QingJian)

一款简洁优雅的 Typecho 主题，采用左侧边栏布局，注重阅读体验。

## 预览

![预览截图](screenshot.png)

## 特性

- 左侧固定侧边栏，支持头像、站点统计、最新文章、分类、标签云
- 响应式设计，移动端自动切换为汉堡菜单
- 阅读进度条 + 文章目录 (TOC) 侧滑面板
- 面包屑导航
- 评论区支持登录状态识别
- 内置「映画集」瀑布流相册页面（支持无限滚动、20 种图片切换特效）
- 友情链接页面模板
- 自定义主题色、Logo、Favicon、副标题、自定义 CSS
- 打印友好
- 404 页面

## 安装

1. 下载本仓库，将文件夹重命名为 `qingjian`
2. 上传至 Typecho 的 `usr/themes/` 目录
3. 登录后台 → 控制台 → 外观 → 启用「清简」

## 目录结构

```
qingjian/
├── index.php          # 首页
├── post.php           # 文章页
├── page.php           # 独立页面
├── archive.php        # 归档页
├── comments.php       # 评论模块
├── header.php         # 公共头部（侧边栏）
├── footer.php         # 公共底部
├── functions.php      # 主题设置
├── style.css          # 主样式
├── gallery.css        # 相册样式
├── gallery.php        # 瀑布流相册页面
├── links.php          # 友情链接页面
└── README.md
```

## 相册使用

1. 在网站根目录的 `/usr/uploads/album/` 下创建文件夹，放入图片
2. 新建独立页面，自定义模板选择「映画集」
3. 在插件设置中可配置扫描目录、每页数量、主题色

## 许可

MIT License
```

简洁够用，直接复制保存为 `README.md` 放在主题根目录即可。如果需要英文版或者想补充截图、徽章之类的，告诉我。
