# Simulation-of-flash-animation-carousel
Web front-end project
Sorry, I haven't learned how to upload the code, I would like to put the code in readme, or go to my gist query, thank you for your attention


<!--
    声明当前文档类型 为html （html5向下兼容）
-->
<!doctype html>
<html><!--根目录标签-->
<head><!--头 放置网页信息 浏览器 搜索引擎-->
	<title>模拟flash动画轮播</title><!--网页标题-->
	<meta name="keywords" content="关键词，关键词" />
	<meta name="description" content="描述" />
	<style>
	/*初始化 解决浏览器兼容问题*/
	*{
		margin: 0;
		padding:0;
	}
	body{
		background:#222;
	}
	.flash{/*类选择器*/
		width:760px;  
		height:300px;
		background:red;
		margin:100px auto 0;/*上外边距100像素 左右自适应居中 下外边距0*/
        border-radius:20px;/*圆角幅度*/
        box-shadow：0px 0px 6px 1px #fff;/*背景阴影: 水平偏移值 垂直偏移值 边缘模糊度 范围 */
        padding:20px;
        position: relative;/*相对定位 参照物*/
    }
    .flash .content{/*找到class名字叫做flash里面的class名字叫做content的标签*/
        width:760px;
        height:300px;
        background:red;
        position: relative;/*相对定位 参照物*/
    }
    .flash .content .con{
    	width:760px;
    	height:300px;
    	position: absolute;
    	left:0;
    	top:0;
    	display:none;
        overflow:hidden;/*超出隐藏*/
    }
    flash .content .con:nth-child(1){
    	background:url('images/bg1.jpg');
    	display:block;
    }
    flash .content .con:nth-child(2){
    	background:rgb(230,108,87);
    }
    flash .content .con:nth-child(3){
    	background:rgb(32,47,61);
    }
    flash .content .con:nth-child(4){
    	background:url('images/bg2.jpg');
    }
    .flash .content .con img{
    	position: absolute;/*绝对定位:随意移动 怎么移动：围绕参照物移动*/
    }
    /*第一部分样式*/
    .flash .content .con img.f-1-1{
    	/*left:20px;*/left:-340px;
    	/*opacity:1;*/opacity:0;
    	top:80px;  
    }
    .flash .content .con img.f-1-2{
    	/*left:20px;*/left:-340px;
    	/*opacity:1;*/opacity:0;
    	top:150px;
    }
    .flash .content .con img.f-1-3{
    	/*left:315px;*/left:760px;
    	/*opacity:1;*/opacity:0;
    	top:0px;
    }
    /*第二部分样式*/
    .flash .content .con img.f-2-1{
    	left:20px;
    	/*opacity:1;*/opacity:0;
    	/*top:50px;*/top:170px;  
    }
    .flash .content .con img.f-2-2{
    	left:20px;
    	/*opacity:1;*/opacity:0;
    	/*top:160px;*/top:300px;
    }
    .flash .content .con img.f-2-3{
    	left:420px;
    	/*opacity:1;*/opacity:0;
    	/*top:0px;*/top:300px;
    }
     /*第三部分样式*/
    .flash .content .con img.f-3-1{
    	/*left:320px;*/left:200px;
    	/*opacity:1;*/opacity:0;
        top:120px;  
    }
    .flash .content .con img.f-3-2{
    	left:320px;
    	/*opacity:1;*/opacity:0;
    	/*top:200px;*/top:300px;
    }
    .flash .content .con img.f-3-3{
    	left:-110px;
    	/*opacity:1;*/opacity:0;
    	top:0px;
    }
     /*第四部分样式*/
    .flash .content .con img.f-4-1{
    	left:80px;
    	/*opacity:1;*/opacity:0;
    	/*top:0px;*/top:300px;  
    }
    .flash .content .con img.f-4-2{
    	left:340px;
    	/*opacity:1;*/opacity:0;
    	top:80px;
    }
    .flash .content .con img.f-4-3{
    	left:340px;
    	/*opacity:1;*/opacity:0;
    	/*top:220px;*/top:300px;
    }
    .flash .btn{
    	position:absolute;
    	top:110px;
    }
    .flash .left{
    	left:0;
    }
    .flash .right{
    	right:0;
    }  	    	  	    	    	  
	</style> 
</head>
<body><!--身体 网页内容-->
    <div class="flash">
        <div class="content">
            <!--第一部分开始-->
            <div class="con">
            	<img class="f-1-1" src="images/flash1.png"  alt="注释说明"/>
            	<img class="f-1-2" src="images/flash12.png" alt="注释说明"/>
            	<img class="f-1-3" src="images/flash13.png" alt="注释说明"/>
            </div>
            <!--第一部分结束-->

            <!--第二部分开始-->
            <div class="con">
            	<img class="f-2-1" src="images/flash1.png"  alt="注释说明"/>
            	<img class="f-2-2" src="images/flash22.png" alt="注释说明"/>
            	<img class="f-2-3" src="images/flash23.png" alt="注释说明"/>
            </div>
            <!--第二部分结束-->

            <!--第三部分开始-->
            <div class="con">
            	<img class="f-3-1" src="images/flash1.png"  alt="注释说明"/>
            	<img class="f-3-2" src="images/flash32.png" alt="注释说明"/>
            	<img class="f-3-3" src="images/flash33.png" alt="注释说明"/>
            </div>
            <!--第三部分结束-->

            <!--第四部分开始-->
            <div class="con">
            	<img class="f-4-1" src="images/flash1.png"  alt="注释说明"/>
            	<img class="f-4-2" src="images/flash42.png" alt="注释说明"/>
            	<img class="f-4-3" src="images/flash43.png" alt="注释说明"/>
            </div>
            <!--第四部分结束-->
        </div>
        <img class="btn left" src="images/left.png"/>
        <img class="btn right" src="images/right.png"/>
    </div>
    <script src="js/jquery-1.11.1.min.js"></script>
    <script>
     var _index=0;//序列号
     var arrCss = [];//存放样式
     var Class =[];//存放类名
    Css();//获取到对应的css样式值
    auto();//动画
    //动画
    function auto(){
       $('.flash .content ,con').eq(_index).find("img").removeAttr('style'); 
       	   $('.flash .content ,con').eq(_index).find(Class[1]).animate(arrCss[1],1000,function(){$('.flash .content ,con').eq(_index).find(Class[2]).animate(arrCss[2],1000);

       	   })
       });
    
    };
    //判断对应样式 根据序列号
    function Css(){
    	$('.flash .content .con') .eq(_index) .fadeIn().siblings().fadeout();
         if (_index == 0) {
         	  Class =['.f-1-1','.f-1-2','.f-1-3']
              arrCss = [{left:"20px",opacity:1},{left:"20px",opacity:1},{left:"315px",opacity:1}]
         }else if (_index == 1) {
         	   Class =['.f-2-1','.f-2-2','.f-2-3']
              arrCss = [{top:"50px",opacity:1},{top:"160px",opacity:1},{top:"0px",opacity:1}]
          }else if (_index == 2) {
          	   Class =['.f-3-1','.f-3-2','.f-3-3']
              arrCss = [{left:"320px",opacity:1},{top:"200px",opacity:1},{opacity:1}]
          }else if (_index == 3) {
          	   Class =['.f-4-1','.f-4-2','.f-4-3']
              arrCss = [{top:"0px",opacity:1},{opacity:1},{top:"220px",opacity:1}]
          }

    } 
    $('.left').click(function(){
    	_index++;
    	if (_index>3) {_index = 0};
         Css()
         auto();
    });
     $('.right').click(function(){
    	_index--;
    	if (_index<0) {_index = 3};
         Css()
         auto()
    });
    </script>
</body>
</html>
