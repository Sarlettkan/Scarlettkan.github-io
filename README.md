
<!DOCTYPE html><html lang="zh-CN" data-theme="light"><head><meta charset="UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=edge"><meta name="viewport" content="width=device-width,initial-scale=1"><title>清·婉</title><meta name="description"><meta name="author" content="清·婉"><meta name="copyright" content="清·婉"><meta name="format-detection" content="telephone=no"><link rel="shortcut icon" href="https://s2.ax1x.com/2020/02/13/1qOFUI.png"><meta http-equiv="Cache-Control" content="no-transform"><meta http-equiv="Cache-Control" content="no-siteapp"><link rel="preconnect" href="//cdn.jsdelivr.net"/><link rel="dns-prefetch" href="//cdn.jsdelivr.net"/><link rel="preconnect" href="https://hm.baidu.com"/><link rel="dns-prefetch" href="https://hm.baidu.com"/><link rel="preconnect" href="https://fonts.googleapis.com" crossorigin="crossorigin"/><link rel="dns-prefetch" href="https://fonts.googleapis.com"/><link rel="preconnect" href="//busuanzi.ibruce.info"/><link rel="dns-prefetch" href="//busuanzi.ibruce.info"/><meta name="twitter:card" content="summary"><meta name="twitter:title" content="清·婉"><meta name="twitter:description"><meta name="twitter:image" content="https://s2.ax1x.com/2020/02/13/1qOFUI.png"><meta property="og:type" content="website"><meta property="og:title" content="清·婉"><meta property="og:url" content="https://liwanrong.github.io/"><meta property="og:site_name" content="清·婉"><meta property="og:description"><meta property="og:image" content="https://s2.ax1x.com/2020/02/13/1qOFUI.png"><meta property="article:published_time" content="2020-05-06T10:21:43.759Z"><meta property="article:modified_time" content="2020-05-06T10:21:43.759Z"><script src="https://cdn.jsdelivr.net/npm/js-cookie/dist/js.cookie.min.js"></script><script>var autoChangeMode = '2'
var t = Cookies.get("theme")
if (autoChangeMode == '1'){
  var isDarkMode = window.matchMedia("(prefers-color-scheme: dark)").matches
  var isLightMode = window.matchMedia("(prefers-color-scheme: light)").matches
  var isNotSpecified = window.matchMedia("(prefers-color-scheme: no-preference)").matches
  var hasNoSupport = !isDarkMode && !isLightMode && !isNotSpecified

  if (t === undefined){
    if (isLightMode) activateLightMode()
    else if (isDarkMode) activateDarkMode()
    else if (isNotSpecified || hasNoSupport){
      console.log('You specified no preference for a color scheme or your browser does not support it. I Schedule dark mode during night time.')
      var now = new Date()
      var hour = now.getHours()
      var isNight = hour < 6 || hour >= 18
      isNight ? activateDarkMode() : activateLightMode()
  }
  } else if (t == 'light') activateLightMode()
  else activateDarkMode()

} else if (autoChangeMode == '2'){
  now = new Date();
  hour = now.getHours();
  isNight = hour < 6 || hour >= 18
  if(t === undefined) isNight? activateDarkMode() : activateLightMode()
  else if (t === 'light') activateLightMode()
  else activateDarkMode() 
} else {
  if ( t == 'dark' ) activateDarkMode()
  else if ( t == 'light') activateLightMode()
}

function activateDarkMode(){
  document.documentElement.setAttribute('data-theme', 'dark')
  if (document.querySelector('meta[name="theme-color"]') !== null){
    document.querySelector('meta[name="theme-color"]').setAttribute('content','#000')
  }
}
function activateLightMode(){
  document.documentElement.setAttribute('data-theme', 'light')
  if (document.querySelector('meta[name="theme-color"]') !== null){
  document.querySelector('meta[name="theme-color"]').setAttribute('content','#fff')
  }
}</script><link rel="stylesheet" href="/css/index.css"><link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free/css/all.min.css"><link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@latest/dist/jquery.fancybox.min.css"><link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/node-snackbar/dist/snackbar.min.css"><link rel="canonical" href="https://liwanrong.github.io/"><script>var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?17100f845d6bbf9fc52828f5503aa360";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script><link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Titillium+Web"><script>var GLOBAL_CONFIG = { 
  root: '/',
  algolia: undefined,
  localSearch: {"path":"search.xml","languages":{"hits_empty":"找不到您查询的内容:${query}"}},
  translate: {"defaultEncoding":2,"translateDelay":0,"cookieDomain":"https://xxx/","msgToTraditionalChinese":"繁","msgToSimplifiedChinese":"簡"},
  copy: {
    success: '复制成功',
    error: '复制错误',
    noSupport: '浏览器不支持'
  },
  bookmark: {
    message_prev: '按',
    message_next: '键将本页加入书签'
  },
  runtime_unit: '天',
  runtime: true,
  copyright: {"languages":{"author":"作者: 清·婉","link":"链接: ","source":"来源: 清·婉","info":"著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。"}},
  ClickShowText: undefined,
  medium_zoom: true,
  fancybox: true,
  Snackbar: {"bookmark":{"message_prev":"按","message_next":"键将本页加入书签"},"chs_to_cht":"你已切换为繁体","cht_to_chs":"你已切换为简体","day_to_night":"你已切换为深色模式","night_to_day":"你已切换为浅色模式","bgLight":"#5d0c5b","bgDark":"#af17ab","position":"bottom-left"},
  baiduPush: false,
  highlightCopy: true,
  highlightLang: true,
  highlightShrink: 'false',
  isFontAwesomeV5: true,
  isPhotoFigcaption: true,
  islazyload: true,
  isanchor: true
  
}</script><script>var GLOBAL_CONFIG_SITE = { 
  isPost: false,
  isHome: true,
  isSidebar: false  
  }</script><noscript><style>
#page-header {
  opacity: 1
}
.justified-gallery img{
  opacity: 1
}
</style></noscript></head><body><div id="mobile-sidebar"><div id="menu_mask"></div><div id="mobile-sidebar-menus"><div class="mobile_author_icon"><img class="avatar-img" src="https://s2.ax1x.com/2020/02/13/1qOFUI.png" onerror="onerror=null;src='/img/friend_404.gif'" alt="avatar"/></div><div class="mobile_post_data"><div class="mobile_data_item is-center"><div class="mobile_data_link"><a href="/archives/"><div class="headline">文章</div><div class="length_num">19</div></a></div></div><div class="mobile_data_item is-center">      <div class="mobile_data_link"><a href="/tags/"><div class="headline">标签</div><div class="length_num">8</div></a></div></div><div class="mobile_data_item is-center">     <div class="mobile_data_link"><a href="/categories/"><div class="headline">分类</div><div class="length_num">8</div></a></div></div></div><hr/><div class="menus_items"><div class="menus_item"><a class="site-page" href="/"><i class="fa-fw fa fa-home"></i><span> 主页</span></a></div><div class="menus_item"><a class="site-page" href="/archives/"><i class="fa-fw fa fa-archive"></i><span> 时间轴</span></a></div><div class="menus_item"><a class="site-page" href="/tags/"><i class="fa-fw fa fa-tags"></i><span> 标签</span></a></div><div class="menus_item"><a class="site-page" href="/categories/"><i class="fa-fw fa fa-folder-open"></i><span> 分类</span></a></div><div class="menus_item"><a class="site-page"><i class="fa-fw fas fa-book" aria-hidden="true"></i><span> 笔记</span><i class="fa fa-chevron-down menus-expand" aria-hidden="true"></i></a><ul class="menus_item_child"><li><a class="site-page" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8"><i class="fa-fw fab fa-ubuntu"></i><span> 创客与学科教学应用</span></a></li></ul></div><div class="menus_item"><a class="site-page" href="/about/"><i class="fa-fw fas fa-user-alt"></i><span> 关于</span></a></div><div class="menus_item"><a class="site-page" href="/link/"><i class="fa-fw fa fa-link"></i><span> 友链</span></a></div><div class="menus_item"><a class="site-page" href="/message/"><i class="fa-fw fa fa-envelope"></i><span> 留言板</span></a></div><div class="menus_item"><a class="site-page"><i class="fa-fw fas fa-heartbeat" aria-hidden="true"></i><span> 影音</span><i class="fa fa-chevron-down menus-expand" aria-hidden="true"></i></a><ul class="menus_item_child"><li><a class="site-page" href="/gallery/"><i class="fa-fw fa fa-image"></i><span> 相册</span></a></li><li><a class="site-page" href="/music/"><i class="fa-fw fa fa-music"></i><span> 音乐</span></a></li></ul></div></div></div></div><div id="body-wrap"><div id="web_bg" data-type="photo"></div><div class="full_page" id="nav" style="background-color:transparent;"><div id="page-header"><span class="pull_left" id="blog_name"><a class="blog_title" id="site-name" href="/">清·婉</a></span><span class="pull_right menus"><div id="search_button"><a class="site-page social-icon search"><i class="fa fa-search fa-fw"></i><span> 搜索</span></a></div><div class="menus_items"><div class="menus_item"><a class="site-page" href="/"><i class="fa-fw fa fa-home"></i><span> 主页</span></a></div><div class="menus_item"><a class="site-page" href="/archives/"><i class="fa-fw fa fa-archive"></i><span> 时间轴</span></a></div><div class="menus_item"><a class="site-page" href="/tags/"><i class="fa-fw fa fa-tags"></i><span> 标签</span></a></div><div class="menus_item"><a class="site-page" href="/categories/"><i class="fa-fw fa fa-folder-open"></i><span> 分类</span></a></div><div class="menus_item"><a class="site-page"><i class="fa-fw fas fa-book" aria-hidden="true"></i><span> 笔记</span><i class="fa fa-chevron-down menus-expand" aria-hidden="true"></i></a><ul class="menus_item_child"><li><a class="site-page" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8"><i class="fa-fw fab fa-ubuntu"></i><span> 创客与学科教学应用</span></a></li></ul></div><div class="menus_item"><a class="site-page" href="/about/"><i class="fa-fw fas fa-user-alt"></i><span> 关于</span></a></div><div class="menus_item"><a class="site-page" href="/link/"><i class="fa-fw fa fa-link"></i><span> 友链</span></a></div><div class="menus_item"><a class="site-page" href="/message/"><i class="fa-fw fa fa-envelope"></i><span> 留言板</span></a></div><div class="menus_item"><a class="site-page"><i class="fa-fw fas fa-heartbeat" aria-hidden="true"></i><span> 影音</span><i class="fa fa-chevron-down menus-expand" aria-hidden="true"></i></a><ul class="menus_item_child"><li><a class="site-page" href="/gallery/"><i class="fa-fw fa fa-image"></i><span> 相册</span></a></li><li><a class="site-page" href="/music/"><i class="fa-fw fa fa-music"></i><span> 音乐</span></a></li></ul></div></div><span class="toggle-menu close"><a class="site-page"><i class="fa fa-bars fa-fw" aria-hidden="true"></i></a></span></span></div><div id="site-info"><h1 id="site_title">清·婉</h1><div id="site_subtitle"><span id="subtitle"></span></div><div id="site_social_icons"><a class="social-icon" href="https://github.com/liwanrong/liwanrong.github.io" target="_blank" title="Github"><i class="fab fa-github" aria-hidden="true"></i></a><a class="social-icon" href="mailto:645831899@qq.com" target="_blank" title="Email"><i class="fa fa-envelope" aria-hidden="true"></i></a><a class="social-icon" href="/atom.xml" target="_blank" title="RSS"><i class="fa fa-rss" aria-hidden="true"></i></a></div></div><div id="scroll_down"><i class="fa fa-angle-down scroll-down-effects"></i></div></div><main class="layout_page" id="content-inner"><div class="recent-posts" id="recent-posts"><div class="recent-post-item"><div class="post_cover left_radius"><a href="/2019/11/09/Blog%20Building-Personal%20Blog%20Building%20Based%20on%20Hexo+GitHub/" title="【博客搭建】 基于Hexo+GitHub的个人博客搭建">     <img class="post_bg" data-src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1573310872850&amp;di=a72b6afbca771a26cddd59a5ce07e277&amp;imgtype=0&amp;src=http%3A%2F%2Faliyunzixunbucket.oss-cn-beijing.aliyuncs.com%2Fjpg%2F8f758d4e914b780117430d09cca4f0f2.jpg%3Fx-oss-process%3Dimage%2Fresize%2Cp_100%2Fauto-orient%2C1%2Fquality%2Cq_90%2Fformat%2Cjpg%2Fwatermark%2Cimage_eXVuY2VzaGk%3D%2Ct_100" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="【博客搭建】 基于Hexo+GitHub的个人博客搭建"></a></div><div class="recent-post-info"><a class="article-title" href="/2019/11/09/Blog%20Building-Personal%20Blog%20Building%20Based%20on%20Hexo+GitHub/" title="【博客搭建】 基于Hexo+GitHub的个人博客搭建">【博客搭建】 基于Hexo+GitHub的个人博客搭建</a><div class="article-meta-wrap"><span class="article-meta"><i class="fa fa-thumb-tack article-meta__icon sticky"></i><span class="sticky">置顶</span><span class="article-meta__separator">|</span></span><time class="post-meta__date" title="发表于 2019-11-09 20:20:00"><i class="fa fa-calendar" aria-hidden="true"></i>2019-11-09</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/WebSite/">WebSite</a></span></div><div class="content">
            本文档更新于2020年05月06日。
          


            主要对本博客做了如下修改：新增Gitee部署自建图床魔改主题延迟修复
          

　　为了尽早体会到拥有一个个人博客的乐趣，在使用Typecho搭建个人博客后由于不想出云服务 ...</div></div></div><div class="recent-post-item"><div class="post_cover right_radius"><a href="/2020/04/22/Task08%EF%BC%9AGit%E4%B8%8EGithub%E4%BD%BF%E7%94%A8%E5%88%9D%E6%AD%A5/" title="Task08：Git与Github使用初步">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task08：Git与Github使用初步"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task08%EF%BC%9AGit%E4%B8%8EGithub%E4%BD%BF%E7%94%A8%E5%88%9D%E6%AD%A5/" title="Task08：Git与Github使用初步">Task08：Git与Github使用初步</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:08:35"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">Git简介
版本控制系统（Version Control System, VCS）
其它VCS: CVS, Subersion, Visual source safe
开源共享，可以自架服务器，同时使用客户端访问与应用
专用的第三方的Git服务，相当于租用了别人的Git服务器，在上面创建软件仓库并进 ...</div></div></div><div class="recent-post-item"><div class="post_cover left_radius"><a href="/2020/04/22/Task07%EF%BC%9A%E8%BF%9C%E7%A8%8B%E6%96%87%E4%BB%B6%E4%BC%A0%E8%BE%93%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%A1%88/" title="Task07：远程文件传输的几种方案">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task07：远程文件传输的几种方案"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task07%EF%BC%9A%E8%BF%9C%E7%A8%8B%E6%96%87%E4%BB%B6%E4%BC%A0%E8%BE%93%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%A1%88/" title="Task07：远程文件传输的几种方案">Task07：远程文件传输的几种方案</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:07:40"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">scpscp扩展：Winscpsftp：可以理解为从ssh通道走的FTP可以使用的客户端
Winscp
Filezilla
建议Windows中使用Chocolatey

远程修改实现
场景：需要修改远程主机上的某个文件
解决方案　
ssh远程登录并用nano，vi编辑
先用scp、winscp等下 ...</div></div></div><div class="recent-post-item"><div class="post_cover right_radius"><a href="/2020/04/22/Task06%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86/" title="Task06：Linux用户管理">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task06：Linux用户管理"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task06%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86/" title="Task06：Linux用户管理">Task06：Linux用户管理</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:07:30"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">创建、删除组
创建组：groupadd
删除组：groupdel
tip: 创建新用户时，会自动创建同名用户组



查看组信息
cat /etc/group

修改文件或目录的所在组
sudo chgrp 组名、文件或目录
默认不修改子目录组信息，要递归修改：
chgrp -R 组名 目录名

添 ...</div></div></div><div class="recent-post-item"><div class="post_cover left_radius"><a href="/2020/04/22/Task05%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E6%9D%83%E9%99%90/" title="Task05：Linux用户权限">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task05：Linux用户权限"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task05%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E6%9D%83%E9%99%90/" title="Task05：Linux用户权限">Task05：Linux用户权限</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:07:15"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">用户权限
以ls -l为例  -rw-rw-r– 1 lwr lwr  398 4月   1 00:16 id_rsa.pub
依次：权限标识符，硬连接数，用户与组，文件容量，最后修改日期，名称

权限标识符：10位
第一位：d/- （类别，d表示目录 -表示文件）
后九位：
第一组RWX：拥有者的 ...</div></div></div><div class="recent-post-item"><div class="post_cover right_radius"><a href="/2020/04/22/Task04%EF%BC%9ALinux%E8%BF%9C%E7%A8%8B%E7%AE%A1%E7%90%86/" title="Task04：Linux远程管理">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task04：Linux远程管理"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task04%EF%BC%9ALinux%E8%BF%9C%E7%A8%8B%E7%AE%A1%E7%90%86/" title="Task04：Linux远程管理">Task04：Linux远程管理</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:06:57"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">Ctrl-Alt-T:启动终端
shutdown：开关机及重启命令
默认一分钟关机
取消: shutdown -c
shutdown -r 重启
定时任务： -num; hh:mm, now
远程管理时尽量不要关机或重启

ifconfig：网络配置
 ifconfig | grep

ping
默 ...</div></div></div><div class="recent-post-item"><div class="post_cover left_radius"><a href="/2020/04/22/Task03%EF%BC%9ALinux%E5%9F%BA%E6%9C%AC%E5%91%BD%E4%BB%A4/" title="Task03：Linux 基本命令">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task03：Linux 基本命令"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task03%EF%BC%9ALinux%E5%9F%BA%E6%9C%AC%E5%91%BD%E4%BB%A4/" title="Task03：Linux 基本命令">Task03：Linux 基本命令</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:05:39"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">文件与目录
分区：Linux没有分区概念，Linux以目录的组织，只有根目录
/bin：可执行文件
/sbin：供超级用户使用的可执行文件 （s=super）
/etc：配置文件
eg：源地址：/etc/apt/sources.list


/home：家目录，给用户存储文件用
每一个用户都有一个用 ...</div></div></div><div class="recent-post-item"><div class="post_cover right_radius"><a href="/2020/04/22/Task02%EF%BC%9AUbuntu%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE/" title="Task02：Ubuntu基本设置">     <img class="post_bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" alt="Task02：Ubuntu基本设置"></a></div><div class="recent-post-info"><a class="article-title" href="/2020/04/22/Task02%EF%BC%9AUbuntu%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE/" title="Task02：Ubuntu基本设置">Task02：Ubuntu基本设置</a><div class="article-meta-wrap"><time class="post-meta__date" title="发表于 2020-04-22 11:05:30"><i class="fa fa-calendar" aria-hidden="true"></i>2020-04-22</time><span class="article-meta"><span class="article-meta__separator">|</span><i class="fa fa-inbox article-meta__icon" aria-hidden="true"></i><a class="article-meta__categories" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/">创客与学科教学应用</a></span></div><div class="content">拓展：虚拟机镜像分享站点：https://www/osboxes.org/ubuntusf.net
操作系统
用户、应用软件、操作系统（内核（管理硬件系统）-系统调用，终端命令，图形界面））、硬件系统
类型
桌面：Windows Mac Linux
服务器：Unix（最早 美国） Linux Win ...</div></div></div><nav id="pagination"><div class="pagination"><span class="page-number current">1</span><a class="page-number" href="/page/2/">2</a><a class="page-number" href="/page/3/">3</a><a class="extend next" rel="next" href="/page/2/"><i class="fa fa-fw fa-chevron-right" aria-hidden="true"></i></a></div></nav></div><div class="aside_content" id="aside_content"><div class="card-widget card-info"><div class="card-content"><div class="card-info-avatar is-center"><img class="avatar-img" src="https://s2.ax1x.com/2020/02/13/1qOFUI.png" onerror="this.onerror=null;this.src='/img/friend_404.gif'" alt="avatar"/><div class="author-info__name">清·婉</div><div class="author-info__description"></div></div><div class="card-info-data"><div class="card-info-data-item is-center"><a href="/archives"><div class="headline">文章</div><div class="length_num">19</div></a></div><div class="card-info-data-item is-center">      <a href="/tags"><div class="headline">标签</div><div class="length_num">8</div></a></div><div class="card-info-data-item is-center">     <a href="/categories"><div class="headline">分类</div><div class="length_num">8</div></a></div></div><div class="card-info-bookmark is-center"><a class="bookmark button--primary button--animated" id="bookmark-it" href="javascript:;" title="加入书签" target="_self"><i class="fa fa-bookmark" aria-hidden="true"></i><span>加入书签</span></a></div><div class="card-info-social-icons is-center"><a class="social-icon" href="https://github.com/liwanrong/liwanrong.github.io" target="_blank" title="Github"><i class="fab fa-github" aria-hidden="true"></i></a><a class="social-icon" href="mailto:645831899@qq.com" target="_blank" title="Email"><i class="fa fa-envelope" aria-hidden="true"></i></a><a class="social-icon" href="/atom.xml" target="_blank" title="RSS"><i class="fa fa-rss" aria-hidden="true"></i></a></div></div></div><div class="card-widget card-announcement"><div class="card-content"><div class="item-headline"><i class="fa fa-bullhorn card-announcement-animation" aria-hidden="true"></i><span>公告</span></div><div class="announcement_content">与你相遇，是我的幸运~</div></div></div><div class="card-widget card-recent-post"><div class="card-content"><div class="item-headline"><i class="fa fa-history" aria-hidden="true"></i><span>最新文章</span></div><div class="aside-recent-item"><div class="aside-recent-post"><a href="/2020/04/22/Task08%EF%BC%9AGit%E4%B8%8EGithub%E4%BD%BF%E7%94%A8%E5%88%9D%E6%AD%A5/"><div class="aside-post-cover"><img class="aside-post-bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" title="Task08：Git与Github使用初步" alt="Task08：Git与Github使用初步"/></div><div class="aside-post-title"><div class="aside-post_title" href="/2020/04/22/Task08%EF%BC%9AGit%E4%B8%8EGithub%E4%BD%BF%E7%94%A8%E5%88%9D%E6%AD%A5/" title="Task08：Git与Github使用初步">Task08：Git与Github使用初步</div><time class="aside-post_meta post-meta__date" title="发表于 2020-04-22 11:08:35">2020-04-22</time></div></a></div><div class="aside-recent-post"><a href="/2020/04/22/Task07%EF%BC%9A%E8%BF%9C%E7%A8%8B%E6%96%87%E4%BB%B6%E4%BC%A0%E8%BE%93%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%A1%88/"><div class="aside-post-cover"><img class="aside-post-bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" title="Task07：远程文件传输的几种方案" alt="Task07：远程文件传输的几种方案"/></div><div class="aside-post-title"><div class="aside-post_title" href="/2020/04/22/Task07%EF%BC%9A%E8%BF%9C%E7%A8%8B%E6%96%87%E4%BB%B6%E4%BC%A0%E8%BE%93%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%A1%88/" title="Task07：远程文件传输的几种方案">Task07：远程文件传输的几种方案</div><time class="aside-post_meta post-meta__date" title="发表于 2020-04-22 11:07:40">2020-04-22</time></div></a></div><div class="aside-recent-post"><a href="/2020/04/22/Task06%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86/"><div class="aside-post-cover"><img class="aside-post-bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" title="Task06：Linux用户管理" alt="Task06：Linux用户管理"/></div><div class="aside-post-title"><div class="aside-post_title" href="/2020/04/22/Task06%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86/" title="Task06：Linux用户管理">Task06：Linux用户管理</div><time class="aside-post_meta post-meta__date" title="发表于 2020-04-22 11:07:30">2020-04-22</time></div></a></div><div class="aside-recent-post"><a href="/2020/04/22/Task05%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E6%9D%83%E9%99%90/"><div class="aside-post-cover"><img class="aside-post-bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" title="Task05：Linux用户权限" alt="Task05：Linux用户权限"/></div><div class="aside-post-title"><div class="aside-post_title" href="/2020/04/22/Task05%EF%BC%9ALinux%E7%94%A8%E6%88%B7%E6%9D%83%E9%99%90/" title="Task05：Linux用户权限">Task05：Linux用户权限</div><time class="aside-post_meta post-meta__date" title="发表于 2020-04-22 11:07:15">2020-04-22</time></div></a></div><div class="aside-recent-post"><a href="/2020/04/22/Task04%EF%BC%9ALinux%E8%BF%9C%E7%A8%8B%E7%AE%A1%E7%90%86/"><div class="aside-post-cover"><img class="aside-post-bg" data-src="https://s2.ax1x.com/2020/02/12/1b3O6f.jpg" onerror="this.onerror=null;this.src='/img/404.jpg'" title="Task04：Linux远程管理" alt="Task04：Linux远程管理"/></div><div class="aside-post-title"><div class="aside-post_title" href="/2020/04/22/Task04%EF%BC%9ALinux%E8%BF%9C%E7%A8%8B%E7%AE%A1%E7%90%86/" title="Task04：Linux远程管理">Task04：Linux远程管理</div><time class="aside-post_meta post-meta__date" title="发表于 2020-04-22 11:06:57">2020-04-22</time></div></a></div></div></div></div><div class="card-widget card-categories"><div class="card-content"><div class="item-headline"><i class="fa fa-folder-open" aria-hidden="true"></i><span>分类</span></div><ul class="card-category-list">
            <li class="card-category-list-item"><a class="card-category-list-link" href="/categories/Educating/"><span class="card-category-list-name">Educating</span><span class="card-category-list-count">1</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/Learning/"><span class="card-category-list-name">Learning</span><span class="card-category-list-count">2</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/Major-Learning/"><span class="card-category-list-name">Major Learning</span><span class="card-category-list-count">1</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/Markdown%E8%AF%AD%E6%B3%95/"><span class="card-category-list-name">Markdown语法</span><span class="card-category-list-count">1</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/SQL-Server/"><span class="card-category-list-name">SQL Server</span><span class="card-category-list-count">1</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/Thinking/"><span class="card-category-list-name">Thinking</span><span class="card-category-list-count">3</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/WebSite/"><span class="card-category-list-name">WebSite</span><span class="card-category-list-count">2</span></a></li><li class="card-category-list-item"><a class="card-category-list-link" href="/categories/%E5%88%9B%E5%AE%A2%E4%B8%8E%E5%AD%A6%E7%A7%91%E6%95%99%E5%AD%A6%E5%BA%94%E7%94%A8/"><span class="card-category-list-name">创客与学科教学应用</span><span class="card-category-list-count">8</span></a></li>
                       
            </ul></div></div><div class="card-widget card-tags"><div class="card-content"><div class="item-headline"><i class="fa fa-tags" aria-hidden="true"></i><span>标签</span></div><div class="card-tag-cloud"><a href="/tags/Hexo/" style="font-size: 16px; color: #999">Hexo</a> <a href="/tags/Learning/" style="font-size: 22px; color: #99a9bf">Learning</a> <a href="/tags/Markdown/" style="font-size: 16px; color: #999">Markdown</a> <a href="/tags/RMMV/" style="font-size: 16px; color: #999">RMMV</a> <a href="/tags/Reading/" style="font-size: 16px; color: #999">Reading</a> <a href="/tags/SQL/" style="font-size: 16px; color: #999">SQL</a> <a href="/tags/Skills/" style="font-size: 19px; color: #99a1ac">Skills</a> <a href="/tags/Typecho/" style="font-size: 16px; color: #999">Typecho</a></div></div></div><div class="card-widget card-archives"><div class="card-content"><div class="item-headline"><i class="fa fa-archive" aria-hidden="true"></i><span>归档</span></div><ul class="card-archive-list"><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2020/04/"><span class="card-archive-list-date">四月 2020</span><span class="card-archive-list-count">8</span></a></li><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2020/02/"><span class="card-archive-list-date">二月 2020</span><span class="card-archive-list-count">1</span></a></li><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2020/01/"><span class="card-archive-list-date">一月 2020</span><span class="card-archive-list-count">1</span></a></li><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2019/12/"><span class="card-archive-list-date">十二月 2019</span><span class="card-archive-list-count">3</span></a></li><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2019/11/"><span class="card-archive-list-date">十一月 2019</span><span class="card-archive-list-count">3</span></a></li><li class="card-archive-list-item"><a class="card-archive-list-link" href="/archives/2019/10/"><span class="card-archive-list-date">十月 2019</span><span class="card-archive-list-count">3</span></a></li></ul></div></div><div class="card-widget card-webinfo"><div class="card-content"><div class="item-headline"><i class="fas fa-chart-line" aria-hidden="true"></i><span>网站资讯</span></div><div class="webinfo"><div class="webinfo-item"><div class="webinfo-article-name">文章数目 :</div><div class="webinfo-article-count">19</div></div><div class="webinfo-item"><div class="webinfo-runtime-name">已运行时间 :</div><div class="webinfo-runtime-count" id="webinfo-runtime-count" start_date="11/8/2019 00:00:00">     </div></div><div class="webinfo-item"><div class="webinfo-site-wordcount-name">本站总字数 :</div><div class="webinfo-site-wordcount">12.3k</div></div><div class="webinfo-item">      <div class="webinfo-site-uv-name">本站访客数 :</div><div class="webinfo-site-uv-count" id="busuanzi_value_site_uv"></div></div><div class="webinfo-item"><div class="webinfo-site-name">本站总访问量 :</div><div class="webinfo-site-pv-count" id="busuanzi_value_site_pv"></div></div></div></div></div></div></main><footer id="footer" style="background-color:transparent;" data-type="photo"><div id="footer-wrap"><div class="copyright">&copy;2019 - 2020 By 清·婉</div><div class="framework-info"><span>驱动 </span><a href="https://hexo.io" target="_blank" rel="noopener"><span>Hexo</span></a><span class="footer-separator">|</span><span>主题 </span><a href="https://github.com/jerryc127/hexo-theme-butterfly" target="_blank" rel="noopener"><span>Butterfly</span></a></div><div class="footer_custom_text">表独立兮山之上，云容容兮而在下。</div></div></footer></div><section class="rightside" id="rightside"><div id="rightside-config-hide"><a class="translate_chn_to_cht" id="translateLink" href="javascript:translatePage();" title="简繁转换" target="_self">简</a><i class="darkmode far fa-moon" id="darkmode" title="夜间模式"></i></div><div id="rightside-config-show"><div id="rightside_config" title="设置"><i class="fa fa-cog" aria-hidden="true"></i></div><i class="fa fa-arrow-up" id="go-up" title="回到顶部" aria-hidden="true"></i></div></section><div class="search-dialog" id="local-search"><div class="search-dialog__title" id="local-search-title">本地搜索</div><div id="local-input-panel"><div id="local-search-input"><div class="local-search-box"><input class="local-search-box--input" placeholder="搜索文章" type="text"/></div></div></div><hr/><div id="local-search-results"><div id="local-hits"></div><div id="local-stats"><div class="local-search-stats__hr" id="hr"><span>由</span> <a href="https://github.com/wzpan/hexo-generator-search" target="_blank" rel="noopener" style="color:#49B1F5;">hexo-generator-search</a>
 <span>提供支持</span></div></div></div><span class="search-close-button"><i class="fa fa-times"></i></span></div><div class="search-mask"></div><script src="https://cdn.jsdelivr.net/npm/jquery@latest/dist/jquery.min.js"></script><script src="/js/utils.js"></script><script src="/js/main.js"></script><script src="/js/tw_cn.js"></script><script src="https://cdn.jsdelivr.net/npm/medium-zoom/dist/medium-zoom.min.js"></script><script src="https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@latest/dist/jquery.fancybox.min.js"></script><script src="https://cdn.jsdelivr.net/npm/node-snackbar/dist/snackbar.min.js"></script><script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script><script src="https://cdn.jsdelivr.net/npm/instant.page@latest/instantpage.min.js" type="module"></script><script src="https://cdn.jsdelivr.net/npm/lozad/dist/lozad.min.js"></script><script src="/js/third-party/click_heart.js"></script><script src="/js/search/local-search.js"></script><script src="https://cdn.jsdelivr.net/npm/typed.js"></script><script>var subtitleType = function () {
  loadScript('https://sdk.jinrishici.com/v2/browser/jinrishici.js',function () {
      var subtitleEffect = true
      jinrishici.load(function (result) {
        if (subtitleEffect) {
          var sub = ''.length == 0 ? new Array() : ''.split(',')
          var content = result.data.content
          var both = sub.unshift(content)
          var typed = new Typed('#subtitle', {
            strings: sub,
            startDelay: 300,
            typeSpeed: 150,
            loop: false,
            backSpeed: 50,
          })
        } else {
          document.getElementById('subtitle').innerHTML = result.data.content
        }
      })
    }
  )
}
window.addEventListener('load', subtitleType)
</script><script src="/jsdelivr.js"></script><script src="https://cdn.jsdelivr.net/gh/stevenjoezhang/live2d-widget@latest/autoload.js"></script></body></html>
