# 小网页做好以后，怎样公开分享并收集有效反馈

[English](SHARING_GUIDE.md) · [返回示例与仓库介绍](README.zh-CN.md)

这份指南适用于自己编写或用 AI 辅助完成的小工具、互动网页、个人主页与早期 Demo。下面用本仓库的随机分组工具说明实际步骤。

## 1. 先确认作品运行需要什么

打开[随机分组工具](https://sakuraladder.github.io/wuxianyuedu-creative-web-starters/groups.html)。这个示例在当前浏览器页面读取名单、随机分组并显示结果，不需要服务器、账号、API Key 或数据库。

只有 HTML、CSS、JavaScript 和本地素材的项目，通常可以使用静态网页托管。需要后端、共享记录或外部 API 的项目，还要另外配置相应服务；静态托管不会自动提供这些能力。

保持相关文件在正确的目录，检查链接与素材路径。以 `/` 开头的地址指向域名根目录，放到项目子目录后，效果可能与相对路径不同。

## 2. 获得真正可打开的体验地址

本仓库的[在线示例](https://sakuraladder.github.io/wuxianyuedu-creative-web-starters/)使用 GitHub Pages。类似的静态项目可以这样发布：

1. 把准备公开的文件放进自己管理的仓库，在入口目录保留 `index.html`。
2. 打开仓库的 **Settings → Pages**。
3. 不需要构建步骤的简单项目，选择 **Deploy from a branch**，指定来源分支和文件夹后保存。
4. 等待部署完成，使用 Pages 设置页显示的站点网址。

正式使用前核对托管服务当前的要求和额度。GitHub 的[建站说明](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)和[发布来源说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)介绍了可用配置。

`localhost` 和电脑文件路径不是普通访客能用的公开网址。源码页面与实际运行的网页也应分别标明。

## 3. 以普通访客身份检查

使用退出作者账号的浏览器：

- 打开页面与主要链接，检查图片和样式，不只看第一屏。
- 完成一次主要任务。分组工具可以输入六个示例名字，分成两组，检查每个名字只出现一次、每组三人。
- 再试空名单、组数大于人数等输入。这个示例应说明问题，并隐藏上一次结果。
- 测试准备支持的设备和浏览器，记录实际测过的环境；其他环境保留为未验证。

这些是本仓库示例的预期行为。修改自己的项目后，需要重新检查，不能直接沿用示例的兼容结论。

## 4. 写清别人怎样开始体验

使用[作品介绍模板](PROJECT_BRIEF_TEMPLATE.zh-CN.md)，填写用途、实际体验地址、作者、当前版本、操作方法、账号或付费要求、测试环境与已知限制。

对分组工具，可以先给一个明确任务：“把六个示例名字分成两组。”再问：

- 没有人指导时，能否独立完成？
- 输入的组数超过人数时，实际发生了什么？

互动个人主页可以请访客找到一项作品并打开体验地址；互动卡片或早期 Demo 则应写清需要测试的操作，以及目前尚未完成的部分。

## 5. 选择展示和交流的位置

托管服务提供运行地址。作品介绍页或社区帖子可以补充作者、截图、制作背景和反馈入口。发布前核对目标社区当前规则，并说明自己与项目的关系。

[无限月读 / Infinite Tsukuyomi](https://www.wuxianyuedu.cn/)是本仓库维护团队运营的创作社区，欢迎 Demo、互动内容、小工具、个人网页、二次元小玩意和游戏。可以先浏览已有作品，再根据当前投稿说明确认适用的格式、账号要求与其他条件。本教程中的可运行示例位于 GitHub Pages。

平台与当前示例的操作界面主要使用中文；本仓库另有英文运行与分享说明。

## 6. 让反馈对应到可核对的修改

使用[体验反馈模板](FEEDBACK_TEMPLATE.zh-CN.md)，一起记录任务、操作步骤、预期结果和实际结果。修改后更新版本或日期，说明改了什么，再请人重复同一个任务。作品介绍、截图和体验地址也应对应这个版本。

本仓库示例的问题可以[提交 GitHub Issue](https://github.com/sakuraladder/wuxianyuedu-creative-web-starters/issues/new)，提交需要 GitHub 账号。自己的项目则应提供实际有人维护的反馈渠道。

本文由无限月读平台团队维护，使用 AI 辅助整理，记录的是一个公开静态网页示例。许可见[仓库 LICENSE](LICENSE)。
