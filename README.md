# ========== 资料栏 ========== #
# 头像路径
avatar: /avatar/Misaka.jpg
# 博主名称
author: fi3ework
# 博客签名
signature: witness me
# 社交账号（您可以自定义顺序）
social:
  email: 12345@qq.com
  github: //github.com/fi3ework
  # wechat 需要是二维码图片的路径
  wechat: /assets/example_qr.png
  # qq 需要是二维码图片的路径
  qq: 
  telegram: 
  twitter: 
  weibo: 
  zhihu: 
  douban: 
  facebook: 
  instagram: 
  stack-overflow: 
  segmentFault: 
  juejin: 
  v2ex: 
  bilibili: 
  linkedin: 
  steam: 
  others: 
  rss: 

# 友链
friends:
  friendA: //www.baidu.com
  friendB: //www.google.com

# “关于我”页面
about:
  # 是否启用“关于我”页面
  enable: true
  # “关于我”页面头图
  image: '/intro/about-bg.jpg'

# 搜索网站功能
search:
  # 是否启用“搜索”页面
  enable: false
  # 搜索的网站链接，不能为空。例如 'fi3ework.github.io'
  url: 
  # 搜索引擎：'bing' (默认), 'google' or 'baidu'
  engine: google
# 展示账户信息前的图标
# 默认情况下，只识别 Fontawsome 中以 'fab' 和 'fas' 开头的免费 Icons
# https://fontawesome.com/v5.15/icons?d=gallery&p=2&s=brands,solid&m=free
profile_icons:
  enable: false
  friends: 'fas fa-heart'
  about: 'fas fa-id-card'
  search: 'fas fa-search'
# 自定义链接
profile_links:
  # - name: GOOGLE
  #   url: //www.google.com
  #   icon: 'fab fa-google'
  # - name: GALLERY
  #   url: //www.unsplash.com
  #   icon: 'fas fa-images'

# ========== 网站 ========== #
# 网站名称（有助于 SEO）
SEO_title: fi3ework's Studio
# 网站关键词（有助于 SEO），每篇文章也可以在 `Front-matter` 添加特定的关键字
SEO_keywords:
  - hexo
  - 'hexo-theme'
  - 'hexo-blog'
# 显示在网站头图上的主标题
main_title: fi3ework's Studio
# 显示在网站头图上的副标题
subtitle: it's better to burn out than to fade away
# 主页头图
site_header_image: '/intro/index-bg.jpg'
# 文章页默认头图
post_header_image: '/intro/post-bg.jpg'
# 404 页头图
_404_image: '/intro/404-bg.jpg'

# ========== Theme ========== #
# 首页的文章摘要字数（默认显示 300 个字，填 0 则不显示摘要）
truncate_length: 150
# 显示「阅读更多」按钮，如果首页的文章配置了摘要或 hexo-excerpt
read_more_button: false
# 开启文章右侧的大纲目录
toc: true
# 开启博客页面的字数统计 & 阅读时间
reading_info: true
# 头图高度（默认是屏幕高度的 50%, 可以直接输入其他数字）
index_intro_height: 50
post_intro_height: 50
about_intro_height: 50
# 博客浮动按钮主题，可选值有：'default'，'rounded'
float_button_theme: default
# 博客阅读进度条颜色，可选值有：'default'（灰色），'feature'（主题色）
read_progress_color: default
# 博客 Banner 主题，可选值有：'default'，'clean'
post_banner_theme: default
# 显示头像的边框
avatar_border: true
# 设置主页个人信息随页面滚动
# 如果您自定义了许多链接，请保持 false
profile_sticky: false
# 显示文章的 Category 信息
show_categories: false

# ========== 搜索 ========== #
algolia_search:
  enable: false
  hits:
    per_page: 10  # 每页的结果数
  labels:
    input_placeholder: Search for Posts  # 搜索栏 placeholder
    hits_empty: "We did not find any results for the search: ${query}" # 搜索结果提示
    hits_stats: "${hits} results found in ${time} ms"  # 搜索无结果的提示

# ========== 评论插件 ========== #
# 目前支持直接添加 Livere（推荐），Disqus，Gitment，Gitalk，友言及 Valine，填写插件对应的字段即可启用。
# 如果想添加其他评论插件，在 custom.ejs 中添加即可
comment:
  # Livere  site: https://livere.com/
  livere_uid: 
  # Disqus  site: https://disqus.com/
  disqus_shortname: 
  # Gitment  site: https://github.com/imsun/gitment
  gitment_owner: 
  gitment_repo: 
  gitment_client_id: 
  gitment_client_secret: 
  # Youyan  site: http://www.uyan.cc/
  youyan_uid: 
  # Valine  site: https://valine.js.org/
  valine_appId: 
  valine_appKey: 
  valine_placeHolder: 
  # gitalk: https://github.com/gitalk/gitalk#options
  # 建议设置 gitalk_pathname_id 为 true
  waline_serverURL: 
  waline_placeHolder: 
  waline_avatar: 
  waline_login: 
  # gitalk site: https://github.com/gitalk/gitalk/
  # Value 'true' is recommended for gitalk_pathname_id setting
  gitalk_client_id: 
  gitalk_client_secret: 
  gitalk_admin: 
  gitalk_owner: 
  gitalk_repo: 
  gitalk_pathname_id: false
  gitalk_create_issue_manually: true
  # utteranc site: https://utteranc.es/
  utteranc_repo:  
  utteranc_label: 
  utteranc_theme: 
  utteranc_issue_term: 

# ========== 统计 ========== #
# 是否开启不蒜子阅读量统计
busuanzi: false
# 统计方式，填写 pv 或 uv
busuanzi_pv_or_uv: 'pv'
# 自定义统计标语，'${count}' 会自动替换成统计值
busuanzi_slug: 'PV: ${count} :)'
# 百度统计（填写 siteID）
baidu_analytics: 
# Google 统计（填写 siteID）
google_analytics: 
# CNZZ 统计
CNZZ_analytics: 

# ========== 其他 ========== #
# 网站的标签页缩略图
favicon: /assets/favicon.ico
# 博客结尾的 copyright 信息
copyright:
  enable: false
  # https://creativecommons.org/
  license: '本文采用<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">知识共享署名-非商业性使用 4.0 国际许可协议</a>进行许可'
# Website Approve
website_approve:
  enable: false
  icp_approve: # 例如'京ICP备 04000001号'
  beian_approve: # 例如'11040102700068'
  beian_img: /assets/beian.png
# 文章时效性提醒
outdated_threshold:
  enable: false
  days: 180
  # 默认情况下，每篇文章都将显示时效性提醒信息。但您不一定需要这样。
  # 如果设置为 true，您可以在指定文章的 Front-matter 处设置 `timeliness: true` 以启用时效性提醒，其它文章将不显示。
  specify_article: false
# Mermaid 图表: https://github.com/knsv/mermaid
mermaid:
  enable: false
  # 版本号 '8' 代表使用最新的 Mermaid 8.x 版本
  version: 8.11.0
  theme: dark
  # 更多配置选项可查阅：https://github.com/knsv/mermaid/blob/master/src/mermaidAPI.js
  options:
# LaTeX 数学公式支持
math:
  mathjax:
    enable: false
    # 版本号不应该低于 '3.0.0'，否则您需要手动修改 CDN 链接。
    # 版本号 '3' 代表使用最新的 mathjax 3.x 版本
    version: 3.2.0

# ========== 实验性功能 ========== #
# 注意：接下来的选项为实验性功能。
# 它们可能存在浏览器兼容性问题，或者可能导致网页功能性崩溃。

# 自定义字体 - 浏览器兼容性问题
# 基于 https://github.com/typekit/webfontloader 和 CSS Variables
# 请阅读 README.md 文档的相关内容，确保正确启用此功能。
custom_font:
  enable: false
  # 字体名，使用 ':' 选择字重和变体
  name: 'Noto Sans SC:n3,n4,n5,n7'
  # 字体 CDN 链接
  url: 'https://fonts.googleapis.cnpmjs.org/css2?family=Noto+Sans+SC:wght@300;400;500;700&display=swap'

# ========== 主题开发 ========== #
# 确保访问者获取最新版本的资源。
# 创建新的 Release 前设置一个更高的值。
source_version: 20231124
