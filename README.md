<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.00, maximum-scale=1.0, user-scalable=0">
  <!-- <link rel="stylesheet" href="./style.css"> -->
  <style></style>
  <title>这里是笔记</title>
<link href="style.css" rel="stylesheet"></head>
<body>
  <div id="game" data-status="start">  
    <div class="game-panel">
      <section class="game-intro game-ui">
        <h1 class="section-title">这里是笔记</h1>
        <p class="game-desc">第一节课</p>
        <p class="game-level">Lecture Notes-4.29


github pages

-静态展示页面的服务

通常使用html、markdown文件

需要条件：username.github.io



静态站点建站系统

-octpress (ruby)

-pelican(python)

-hexo (node.js)



安装过程：

-node.js npm(包管理器，相当于python中的pip)

-sudo npm install -g hexo-cli



使用

-初始化：hexo init

-创建：hexo n "标题“

-生成：hexo g

-预览：hexo s



发布到git

-使用hexo一键发布: hexo d

-手动push方式: 将publish目录，git push origin master




Hexo安装：http://ms.zjer.cn/index.php?r=studio/post/view&sid=531&id=2380781 

Markdown简明教程：https://github.com/Melo618/Simple-Markdown-Guide</p>
        <button class="js-play button">开始阅读</button>
      </section>
      <section class="game-failed game-ui">
        <h1 class="section-title">阅读结束</h1>
        <p class="game-info-text">最终得分: <span class="score"></span></p>
        <button class="js-replay button">重新开始</button>
      </section>
      <section class="game-success game-ui">
        <h1 class="section-title">Chocolatey安装与使用
1、安装

最简单的方式是以管理员身份运行cmd，输入：

@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin


安装成功的话，输入choco，会显示chocolatey的版本号。


2、使用

安装软件：choco install 软件包名

升级软件：choco upgrade 软件包名

删除软件：choco uninstall 软件包名

考虑到Windows的权限问题，建议用管理员身份运行cmd或者powershell，再运行。


3、可视化操作

建议安装chocolateygui 包，在可视化环境下使用。</h1>
        <p class="game-next-level game-info-text"></p>
        <button class="js-next button">继续阅读</button>
        
      </section>
      <section class="game-all-success game-ui">
        <h1 class="section-title">通关成功</h1>
        <p class="game-next-level game-info-text">你已经成功地防御了怪兽的所有攻击。</p>
        <button class="js-replay button">再玩一次</button>
      </section>
    </div>
    <canvas id="canvas" width="700px" height="600px">
        <!-- 动画画板 -->
    </canvas>
  </div>
  <!-- 主逻辑函数 -->
  <!-- <script type="text/javascript" src="./js/jquery-3.2.1.min.js"></script> -->
  <!-- <script src="./js/app.js" ></script> -->
<script type="text/javascript" src="bundle.js"></script></body>
</html>
