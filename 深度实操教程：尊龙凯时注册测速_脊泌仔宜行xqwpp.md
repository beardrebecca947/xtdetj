尊龙凯时注册测速【Q-——333307——】尊龙凯时注册测速【 辋芷《888yx●vip》 】
尊龙凯时注册测速【Q-——333307——】尊龙凯时注册测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是不是也想过拥有一个属于自己的技术博客，但被服务器费用、域名备案、复杂的部署流程劝退了？

其实，用 GitHub Pages 搭建博客完全免费，不需要买服务器，也不需要备案。配合 Hexo 静态框架，你只需要专注写作，剩下的交给自动化流程。今天这篇教程，手把手带你从零开始，30分钟上线你的第一个个人站点。

 环境准备：只需三步

在动手之前，请确认你电脑上已经有了这两个基础环境：

- Git：版本管理工具。Windows用户请到官网下载，Mac用户建议用 `brew install git`。
- Node.js：Hexo的运行环境。建议安装 LTS 版本（比如 20.x），避免版本兼容问题。

> 小提示：安装完成后，在终端输入 `node -v` 和 `git --version`，能看到版本号就说明安装成功了。

 正式搭建：Hexo 初始化

打开终端，输入下面这行命令：

```bash
npm install -g hexo-cli
```

然后在你想存放博客的目录下（比如桌面），依次执行：

```bash
hexo init my-blog
cd my-blog
npm install
```

这时你就得到了一个带有默认主题的完整博客框架。输入 `hexo s`，浏览器打开 `http://localhost:4000`，就能看到本地预览效果了。

 免费部署：将博客推送到 GitHub

1. 新建仓库：在 GitHub 上创建一个新仓库，名字必须是 `<你的用户名>.github.io`（例如 `sunny.github.io`）。
2. 修改配置：打开 `_config.yml`，把 `url` 改成你的仓库地址，并在 `deploy` 部分填上 `repo` 和 `branch: main`。
3. 一键推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

这就是网速最丝滑的部分——所有静态文件会自动推送到 GitHub 仓库的 main 分支。等几分钟，访问 `https://<你的用户名>.github.io`，你的个人博客已经全球可访问了。

 进阶优化：切换主题

默认主题比较素，你可以去 [Hexo Themes 页面](https://hexo.io/themes/) 挑选一款更喜欢的。以经典的 NexT 主题为例：

```bash
cd my-blog
git clone https://github.com/theme-next/hexo-theme-next themes/next
```

然后在 `_config.yml` 中把 `theme` 字段改成 `next`，再次 `hexo s` 刷新页面，你会看到全新的界面。

> 建议开启主题自带的本地搜索和访问统计功能，提升读者体验。

 写文章与发布流程

写文章非常轻量，本质上就是一个 Markdown 文件：

```bash
hexo new post "我的第一篇技术博客"
```

打开 `source/_posts/` 下的生成文件，在头部标签（title、date、tags）下面用 Markdown 语法写正文。保存后，执行：

```bash
hexo g && hexo d
```

文章就会自动发布到线上。

 结语与互动

现在你已经拥有了一个完全免费、可自定义的个人技术博客。后续你可以进一步配置自定义域名（绑定自己的 `com` `cn` 域名需要去域名商处解析，但免费域名依然推荐），或者接入 CI/CD 实现自动部署。

有什么疑问，或者部署过程中遇到了小坑？欢迎在评论区留言交流，也可以把这篇教程转发给同样在折腾建站的朋友。GitHub 开源世界的魅力，就在于大家一起踩坑一起进步。我们下次见。

相关推荐：

https://github.com/gardnermatthew7446/fsiwef/blob/main/2027%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9A%E5%B0%8A%E9%BE%99%E5%87%AF%E6%97%B6%E5%9C%B0%E5%9D%80%E4%BB%A3%E7%90%86_%E6%B3%84%E5%85%84%E6%97%A5%E5%91%B3%E6%8A%BCcjooi.md

<img src="https://i.postimg.cc/QC3cDV9T/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(74).png" />

相关推荐：

https://github.com/gardnermatthew7446/fsiwef/commit/6783c6dd51ccd6026ecf23dc3bc539819d3ab57a

<img src="https://i.postimg.cc/QC3cDV9T/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(74).png" />
相关推荐：

https://github.com/aguilarsara36/yicdke/blob/main/2027%E7%A7%91%E6%8A%80%E7%88%86%E7%82%B9%EF%BC%9A%E5%B0%8A%E9%BE%99%E5%87%AF%E6%97%B6%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%88%BB%E5%AD%9F%E5%93%9F%E7%9B%B4%E8%92%99yrxyy.md

<img src="https://i.postimg.cc/J0Lj8tD5/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(75).png" />
相关推荐：

https://github.com/aguilarsara36/yicdke/commit/b1d41cd8b12d17591961ddf3003ac406ba041dbe

<img src="https://i.postimg.cc/Hx5bFbx1/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(72).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
