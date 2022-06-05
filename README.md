# [蓝云的♂好伙伴们](https://blog.loli.sale/guys/)

## 基本要求

- 本站友链不是为了SEO,只是为了**交朋友**
- 添加后请多多**互访**
- 只接受**博客站**,除非引起我的兴趣
- 被必应或谷歌**收录**
- **不接受HTTP站点**
- 站点已平稳运行超过 **30 天**
- 谢绝免费域名
  - 其中，有些是例外的，例如
    - 包含在 Public Suffix List 中的 免费子域名
	- 向 Freenom 公司付费购买的 .ml、.tk 等域名
	- 由 Automattic 公司运营的 wordpress.com 在线博客服务
- 文章最好是以**原创内容**为主，不能接受有**大量水文**
  - 网站和博客可以长草，不要滥竽充数
- 还有一点，当然是要会用 Git 和 GitHub 啦。
- **申请通过标准最终解释权归蓝云所有**
  - 这就意味着可能有些不符合上述标准的站点仍有可能被我添加进友链之中
- 会使用 Git 和 GitHub

## 如何交换

如果你认为自己符合上面的要求，那么请

- 想将蓝云的网站添加到自己的友链中：
  - 站点名称：`蓝云Reyes`
  - URL：`https://loli.sale` 或 `https://blog.loli.sale`
  - Bio：`一个混吃等死的废物`
  - Logo
    - Favicon：
      - [`32x32`, ico](https://cdn.muir.fun/becod/logo_32x.ico)
      - [`192x192`, png](https://cdn.muir.fun/becod/logo_192x.png)
      - [`512x512`, png](https://cdn.muir.fun/becod/logo_512x.png)
    - 头像：
      - [avatar](https://cravatar.cn/avatar/95089b15994ad7fa930c08bf901fb4a8.png)

- 准备一个自己站点的 Logo
  - **原则上** Logo 应符合 Gravater `G` 分级要求（即适合在任何网站上展示给任何年龄段的任何人）

- 准备需要展示的站点名称
  - 长度应小于 16 个半角字符或 8 个全角字符，否则在展示时可能会被截断
  - **原则上** 站点名称应适合在任何网站上展示给任何年龄段的任何人

- 准备一条 Bio
  - 长度建议小于 28 个半角字符或 28 个全角字符，否则在展示时可能会被截断
  - **原则上** Bio 应适合在任何网站上展示给任何年龄段的任何人

- 在 GitHub 上 Fork 这个仓库

- 修改 `src/friends.yml` 文件
  - 按照如下格式将你的网站信息添加到 `friends.yml` 文件中：
```
  - name: "站点名称"
    bio: "长度建议小于 28 个半角字符或 14 个全角字符，否则在展示时可能会被截断"
    avatar: "https://example.com/favicon.ico"
    link: "https://example.com"
```

- 完成上述步骤后，请新建一个 Pull Request。
- 当 Pull Request 被 Review 并被通过、合并后，你的网站将会在 12 个小时内显示在 [♂好伙伴](https://blog.loli.sale/guys/)。