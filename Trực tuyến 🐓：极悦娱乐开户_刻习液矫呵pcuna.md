极悦娱乐开户【Q-——333307——】极悦娱乐开户【 辋芷《888yx●vip》 】
极悦娱乐开户【Q-——333307——】极悦娱乐开户【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人拥有漂亮的个人博客？其实你只需要一个 GitHub 账号，就能免费搭建一个属于自己的技术博客。本文将手把手教你用 Hexo 框架部署到 GitHub Pages，无需购买服务器，支持自定义域名，整个过程约 30 分钟。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 服务器，不花一分钱
- 加载速度快：全球 CDN 加速，国内访问友好
- SEO 友好：静态页面天然利于搜索引擎收录，适合沉淀技术文章
- 版本管理：文章自动备份，写作更安心

 第一步：环境准备

在开始前，请确保你的电脑已安装以下工具：

1. Node.js（建议 LTS 版本，>= 12.0）
2. Git（用于代码提交）
3. GitHub 账号（没有的话先去注册）

打开终端，输入以下命令验证环境：

```bash
node -v
git --version
```

如果都能输出版本号，说明安装成功了。

 第二步：安装 Hexo 并初始化项目

```bash
 全局安装 hexo-cli
npm install -g hexo-cli

 初始化博客项目
hexo init my-blog
cd my-blog

 安装依赖
npm install
```

初始化完成后，本地预览：

```bash
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面就说明成功了！

 第三步：部署到 GitHub Pages

1. 创建仓库：在 GitHub 新建一个仓库，命名为 `你的用户名.github.io`

2. 安装部署插件：

```bash
npm install hexo-deployer-git --save
```

3. 修改配置：打开 `_config.yml`，修改部署部分：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 一键部署：

```bash
hexo clean && hexo g && hexo d
```

部署完成后，访问 `https://你的用户名.github.io`，你的博客就上线啦！

 第四步：优化与美化

为了让博客更好看、更好收录，建议做以下优化：

- 更换主题：推荐 `Next`、`Butterfly` 或 `Fluid` 主题，搜索「Hexo 主题」即可找到
- 提交搜索引擎：将站点提交到百度、Google Search Console，加速收录
- 添加 SEO 插件：安装 `hexo-seo-automatic` 或 `hexo-generator-seo-friendly-sitemap` 插件

 结语与互动

以上就是从零搭建个人博客的全过程。如果你在部署过程中遇到任何问题，欢迎在评论区留言，我会第一时间回复。也可以点赞收藏本文，方便日后查阅。

你在用哪个博客框架？Typecho、Hugo 还是 Hexo？ 评论区聊聊你的看法，我们一起交流学习！

---

本文关键词：GitHub Pages、Hexo 教程、免费博客、个人博客搭建、静态博客部署

相关推荐：

https://github.com/burkemichael2/ljxymn/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%9E%81%E6%82%A6%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1_%E7%81%B0%E6%82%84%E5%B1%AF%E5%BF%8C%E5%8F%AFpmpvs.md

<img src="https://i.postimg.cc/J0x4PVMd/jiyue1-00009.png" />

相关推荐：

https://github.com/burkemichael2/ljxymn/commit/49c3e8d604a654400322953882c9080e1aef5469

<img src="https://i.postimg.cc/W4qzjHwt/jiyue1-00003.png" />
相关推荐：

https://github.com/coxsergio55/aujyza/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%9E%81%E6%82%A6%E5%B9%B3%E5%8F%B0app_%E7%BC%B8%E6%B2%B8%E8%8B%9F%E6%B1%97%E6%BB%93kmhjy.md

<img src="https://i.postimg.cc/v8tBQ95M/jiyue1-00013.png" />
相关推荐：

https://github.com/coxsergio55/aujyza/commit/8d2bc56bbee9d60a2b1c7398c4c407328bb03a8e

<img src="https://i.postimg.cc/VvgLDQzs/jiyue1-00010.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
