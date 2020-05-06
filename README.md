<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="description" content="This is a testing demo page">
    <meta name="keywords" content="testing,html,demo">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Testing Demo Project</title>
<link rel="stylesheet" type="text/css" href="project.css">
    <link rel="stylesheet"  href="lib/bootstrap/css/bootstrap.min.css">
</head>
<body>
    <div id="head">
        <div class="logo_title">
               <h1>LinuxCast.net Demo Site</h1>
               <h2>简易的个性主页</h2>
        </div>
        <div class="navi">
           <ul>
               <li><a href = "">首页</a></li>
               <li><a href = "">闲言碎语</a></li>
               <li><a href = "">我是谁</a></li>
           </ul>
        </div>
        <div class="clear"></div>
    </div>
 
 
    <div id="wrapper">
        <div class="main">
              <div class="item">
                 <div class="item_img">
                    <img src="cast.png" alt="Testing Demo Project pic">
                 </div>
                 <div class="item_content">
                    <h3>LinuxCast测试标题测试标题</h3>
                    <p class="item_info">作者：XXX  发表于：2017年7月15号</p>
                    <p class="item_desc">LinuxCast测试内容测试内容测试内容测试文字测<br>
                    测试文字测试文字测试文字测试文字测试文字测试文字</p>
                 </div>
              </div>
              <div class="item">
                 <div class="item_img">
                    <img src="cast.png" alt="Testing Demo Project pic">
                 </div>
                 <div class="item_content">
                    <h3>LinuxCast测试标题测试标题</h3>
                    <p class="item_info">作者：XXX 发表于：2017年7月15号</p>
                    <p class="item_desc">LinuxCast测试内容测试内容测试内容测试文字测<br>
                    测试文字测试文字测试文字测试文字测试文字测试文字</p>
                 </div>
              </div>
 
 
              <div class="item">
                 <div class="item_img">
                    <img src="cast.png" alt="Testing Demo Project pic">
                 </div>
                 <div class="item_content">
                    <h3>LinuxCast测试标题测试标题</h3>
                    <p class="item_info">作者：XXX 发表于：2017年7月15号</p>
                    <p class="item_desc">LinuxCast测试内容测试内容测试内容测试文字测<br>
                    测试文字测试文字测试文字测试文字测试文字测试文字</p>
                 </div>
              </div>
 
 
              <div class="item">
                 <div class="item_img">
                    <img src="cast.png" alt="Testing Demo Project pic">
                 </div>
                 <div class="item_content">
                    <h3>LinuxCast测试标题测试标题</h3>
                    <p class="item_info">作者：XXX 发表于：2017年7月15号</p>
                    <p class="item_desc">LinuxCast测试内容测试内容测试内容测试文字测<br>
                    测试文字测试文字测试文字测试文字测试文字测试文字</p>
                 </div>
              </div>
        </div>
        <div class="side">
              <div class="author_info">
                   <div class="author_img">
                      <img src="author.jpg" alt="Testing Demo project pic">
                   </div>
                   <div class="author_desc">
                      <h4>Double Sweet</h4>
                      <p>emmm..<br>
                        emmmmmmmm...</p>
                   </div>
              </div>
              <div class="top_article">
                   <h4>推荐文章</h4>
                   <ul>
                   <li>好文要顶-1</li>
                   <li>好文要顶-2</li>
                   <li>好文要顶-3</li>
                   <li>好文要顶-4</li>
                   <li>好文要顶-5</li>
                   </ul>
              </div>
              <div class="site-info">
                   <p>访客：555555</p>
                   <p>文章：666篇</p>
              </div>
        </div>
        <div class="clear"></div>
 
 
    </div>
 
 
    <div id="footer">
      <div class="site_about">
           <p>2015-2017 CopyRight LinuxCast.net Demo Site</p>
      </div>
      <div class="site_link">
           <ul>
              <li><a href = "">关于我们</a></li>
              <li><a href = "">联系我们</a></li>
              <li><a href = "">使用条款</a></li>
              <li><a href = "">意见反馈</a></li>
           </ul>
      </div>
      <div class="clear"></div>
 
 
    </div>
 
 
    <script src="lib/jquery-2.1.1.min.js"></script>
    <script src="lib/bootstrap/js/bootstrap.min.js"></script>
</body>
</html>
//CSS

body{
background-image: url("bg.jpg");
}
 
 
a{
color: grey;/*背景颜色*/
text-decoration: none;/*去除文字的下划线*/
}
 
 
#head{
width: 960px;
margin: auto;
border-bottom: dotted 1px white; /*设置了白色的分界线*/ 
margin-bottom: 10px;
}
 
 
.logo_title{
    float: left;
}
 
 
.logo_title h1{
font-size: 30px;
color: white;
}
 
 
.logo_title h2{
font-size: 20px;
color: white;
}
 
 
.navi{
float: right;
}
 
 
.navi ul{
list-style: none;/*去除前面的黑点*/
margin-top: 75px;
}
 
 
.navi ul li{
display: inline-block;/*排列方式，排列到一行*/
font-size: 20px;
color: white;/*写不写都可以*/
margin-right: 20px;/*外填充距离*/
}
 
 
.navi ul li a{
color: white;
   border:solid 1px white;/*白色的方框*/
   border-radius: 6px;/*边角设置弧度*/
   padding: 4px;/*上下内填充*/
   padding-left: 14px;/*左内边距*/
   padding-right: 14px;/*右内边距*/
}
 
 
.clear{
clear: both;
}
#wrapper{
margin: auto;
width: 960px;
margin-top: 20px;
}
 
 
.main{
   width: 640px;
   background-color: white;
   float: left;
   margin-right:10px;
   padding: 20px;
   border-radius: 4px;
}
 
 
.item{
margin-top: 14px;
padding-bottom: 20px;
border-bottom: dotted 1px #999;
 
 
}
 
 
.item_img{
float: left;
width: 100px;
}
 
 
.item_img img{
width: 80px;
}
 
 
.item_content{
    /*padding-left: 100px;*/
    /*float: right;*/
    margin-bottom: 10px;
}
 
 
.item_content h3{
font-size: 14px;
color: #FF6347;
margin: 0;
}
 
 
.item_info{
font-size: 12px;
font-style: italic;
margin:0;
color: #999;
}
 
 
.item_desc{
font-size: 14px;
margin: 0;
color: gray;
margin-top:10px; /*与h2有一定的边距*/
border-left: solid 1px #ccc;/*设置左边框*/
padding-left: 10px;/*设置左填充*/
}
 
 
 
 
.side{
   width: 220px;
   background-color: white ;
   float: right;
   padding: 20px;
   border-radius: 6px;
   margin-left: 10px;
   height: 450px;
}
 
 
.author_img{
   margin-top: 20px;
   width: 120px;
   margin:auto;
}
 
 
.author_img img{
width: 120px;
border:solid 1px #ccc;
border-radius: 4px;
}
 
 
.author_desc{
   text-align: center;
   border:solid 1px #ccc;
   border-radius: 4px;
   background-color: #eee;
   padding-top:10px;
   padding-bottom: 10px;
   margin-top: 10px;
   margin-bottom: 10px;
}
 
 
.author_desc h4{
margin:0;
margin-bottom: 10px;
}
 
 
.author_desc p{
margin:0;
font-size: 14px;
margin-bottom: 10px;
}
 
 
.top_article h4{
font-size:14px;
font-style: italic;
margin:0;
border-bottom: dotted 1px #999;
border-top: 10px;
}
 
 
.top_article ul{
margin-left:0;
padding-left:10px;
list-style: none;
 
 
}
 
 
.top_article ul li{
margin:0;
font-size: 14px;
margin-top: 5px;
 
 
}
 
 
/*.site_info{
margin-top: 30px;
border-top: solid 1px #ccc; 
}
.site_info p{
font-size: 14px;
color: gray;
margin:0;
padding-left: 60px;
margin-top: 10px;
}*/
.site-info{
margin-top: 30px;
border-top: solid 1px #ccc;/*分界线*/
}
 
 
.site-info p{
font-size: 14px;
color: gray;
text-align: center;
/*padding-left: 60px;/*左填充*/
margin:0;
margin-top: 10px;
}
 
 
#footer{
margin: auto;
width: 960px;
border-top: dotted 1px #ccc;
margin-top: 20px;
}
 
 
.site_about{
float: left;
padding-top: 15px;
}
 
 
.site_about p{
font-size: 16px;
color: white;
}
 
 
.site_link{
float: right;
}
 
 
.site_link ul{
list-style: none;
margin-top: 30px;
}
 
 
.site_link ul li{
display: inline-block;
font-size: 14px;
margin-right: 10px;
color: white;
}
 
 
.site_link ul li a{
border-radius: 6px;
border:solid 1px white;
padding: 4px;
padding-left: 10px;
padding-right: 10px;
color: white;
}
————————————————
版权声明：本文为CSDN博主「doubleSweet.」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/double_sweet1/java/article/details/78608710
