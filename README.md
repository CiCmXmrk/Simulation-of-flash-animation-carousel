

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="utf-8">
    <link rel="canonical" href="https://blog.csdn.net/weixin_42159233/article/details/86529883"/>
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <meta name="renderer" content="webkit"/>
    <meta name="force-rendering" content="webkit"/>
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="report" content='{"pid": "blog", "spm":"1001.2101"}'>
    <meta name="referrer" content="always">
    <meta http-equiv="Cache-Control" content="no-siteapp" /><link rel="alternate" media="handheld" href="#" />
    <meta name="shenma-site-verification" content="5a59773ab8077d4a62bf469ab966a63b_1497598848">
    <meta name="applicable-device" content="pc">
    <link  href="https://g.csdnimg.cn/static/logo/favicon32.ico"  rel="shortcut icon" type="image/x-icon" />
    <title>【风变编程】第五课笔记_ArtlexKylin的博客-CSDN博客_风变编程python第五关答案</title>
    <script>
      (function(){ 
        var el = document.createElement("script"); 
        el.src = "https://s3a.pstatp.com/toutiao/push.js?1abfa13dfe74d72d41d83c86d240de427e7cac50c51ead53b2e79d40c7952a23ed7716d05b4a0f683a653eab3e214672511de2457e74e99286eb2c33f4428830"; 
        el.id = "ttzz"; 
        var s = document.getElementsByTagName("script")[0]; 
        s.parentNode.insertBefore(el, s);
      })(window)
    </script>
        <meta name="keywords" content="风变编程python第五关答案">
        <meta name="csdn-baidu-search"  content='{"autorun":true,"install":true,"keyword":"风变编程python第五关答案"}'>
    <meta name="description" content="python基础语法第五课一、列表（list）1. 列表中变量类型**可不唯一**2. 元素提取，**左闭右开**3. 切片与取一个元素，**返回值的类型不一样**二、字典&amp;amp;amp;amp;amp;amp;nbsp;第五课一、列表（list）1. 列表中变量类型可不唯一list1 = ['小明', 18, 1.70]print(list1)输出：['小明', 18, 1.7]&amp;amp;amp;amp;amp;amp;nbsp;2. 元素提取，...">
    <script src='//g.csdnimg.cn/tingyun/1.8.3/blog.js' type='text/javascript'></script>
        <link rel="stylesheet" type="text/css" href="https://csdnimg.cn/release/blogv2/dist/pc/css/detail_enter-08aca08f14.min.css">
        <link rel="stylesheet" type="text/css" href="https://csdnimg.cn/release/blogv2/dist/pc/themesSkin/skin-technology/skin-technology-a1f8f1d1b8.min.css">
    <script src="https://csdnimg.cn/public/common/libs/jquery/jquery-1.9.1.min.js" type="text/javascript"></script>
    <script type="text/javascript">
        var isCorporate = false;//注释删除enterprise
        var username =  "weixin_42159233";
        var skinImg = "white";
        var blog_address = "https://blog.csdn.net/weixin_42159233";
        var currentUserName = "weixin_44724371";
        var isOwner = false;
        var loginUrl = "http://passport.csdn.net/account/login?from=https://blog.csdn.net/weixin_42159233/article/details/86529883";
        var blogUrl = "https://blog.csdn.net/";
        var avatar = "https://profile.csdnimg.cn/5/A/6/3_weixin_42159233";
        var articleTitle = "【风变编程】第五课笔记";
        var articleDesc = "python基础语法第五课一、列表（list）1. 列表中变量类型**可不唯一**2. 元素提取，**左闭右开**3. 切片与取一个元素，**返回值的类型不一样**二、字典&amp;amp;amp;amp;amp;amp;nbsp;第五课一、列表（list）1. 列表中变量类型可不唯一list1 = [\'小明\', 18, 1.70]print(list1)输出：[\'小明\', 18, 1.7]&amp;amp;amp;amp;amp;amp;nbsp;2. 元素提取，...";
        var articleTitles = "【风变编程】第五课笔记_ArtlexKylin的博客-CSDN博客_风变编程python第五关答案";
        var nickName = "ArtlexKylin";
        var articleDetailUrl = "https://blog.csdn.net/weixin_42159233/article/details/86529883";
        if(window.location.host.split('.').length == 3) {
            blog_address = blogUrl + username;
        }
        var skinStatus = "White";
        var blogStaticHost = "https://csdnimg.cn/release/blogv2/"
    </script>
    <script src="https://g.csdnimg.cn/??fixed-sidebar/1.1.6/fixed-sidebar.js" type="text/javascript"></script>
    <script src='//g.csdnimg.cn/common/csdn-report/report.js' type='text/javascript'></script>
    <link rel="stylesheet" type="text/css" href="https://csdnimg.cn/public/sandalstrap/1.4/css/sandalstrap.min.css">
    <style>
        .MathJax, .MathJax_Message, .MathJax_Preview{
            display: none
        }
    </style>
    <script src="https://dup.baidustatic.com/js/ds.js"></script>
</head>
<body class="nodata " style="">
        <script>
            var toolbarSearchExt = '{"landingWord":["风变编程python第五关答案"],"queryWord":"风变编程","tag":["风变编程","python小课","python入门"],"title":"【风变编程】第五课笔记"}';
        </script>
    <script src="https://g.csdnimg.cn/common/csdn-toolbar/csdn-toolbar.js" type="text/javascript"></script>
    <script>
    (function(){
        var bp = document.createElement('script');
        var curProtocol = window.location.protocol.split(':')[0];
        if (curProtocol === 'https') {
            bp.src = 'https://zz.bdstatic.com/linksubmit/push.js';
        }
        else {
            bp.src = 'http://push.zhanzhang.baidu.com/push.js';
        }
        var s = document.getElementsByTagName("script")[0];
        s.parentNode.insertBefore(bp, s);
    })();
    </script>
<link rel="stylesheet" href="https://csdnimg.cn/release/blogv2/dist/pc/css/blog_code-01256533b5.min.css">
<link rel="stylesheet" href="https://csdnimg.cn/release/blogv2/dist/mdeditor/css/editerView/chart-3456820cac.css" />
<div class="main_father clearfix d-flex justify-content-center" style="height:100%;"> 
    <div class="container clearfix" id="mainBox">
        <main>
<script type="text/javascript">
    var blogSensitiveWords = "";
    function getQueryString(name) {   
      var reg = new RegExp("(^|&)" + name + "=([^&]*)(&|$)"); //构造一个含有目标参数的正则表达式对象  
      var r = window.location.search.substr(1).match(reg);  //匹配目标参数
      if( r != null ) return decodeURIComponent( r[2] ); return '';   
    }
    function stripscript(s){ 
      var pattern = new RegExp("[`~!@#$^&*()=|{}':;',\\[\\].<>/?~！@#￥……&*（）——|{}【】‘；：”“'。，、？%]") 
      var rs = ""; 
      for (var i = 0; i < s.length; i++) { 
        rs = rs+s.substr(i, 1).replace(pattern, ''); 
      } 
      return rs; 
    }
    var blogHotWords = stripscript(getQueryString('utm_term')).length > 1 ? stripscript(getQueryString('utm_term')) : ''
</script>
<div class="blog-content-box">
    <div class="article-header-box">
        <div class="article-header">
            <div class="article-title-box">
                <h1 class="title-article" id="articleContentId">【风变编程】第五课笔记</h1>
            </div>
            <div class="article-info-box">
                <div class="article-bar-top">
                    <img class="article-type-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/reprint.png" alt="">
                    <div class="bar-content">
                    <a class="follow-nickName " href="https://blog.csdn.net/weixin_42159233" target="_blank" rel="noopener">ArtlexKylin</a>
                    <span class="time">2019-01-17 20:07:54</span>
                    <img class="article-read-img article-heard-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/articleReadEyes.png" alt="">
                    <span class="read-count">15493</span>
                    <a id="blog_detail_zk_collection" class="un-collection" data-report-click='{"mod":"popu_823","spm":"1001.2101.3001.4232","ab":"new"}'>
                        <img class="article-collect-img article-heard-img un-collect-status isdefault" style="display:inline-block" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCollect.png" alt="">
                        <img class="article-collect-img article-heard-img collect-status isactive" style="display:none" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCollectionActive.png" alt="">
                        <span class="name">收藏</span>
                        <span class="get-collection">
                            37
                        </span>
                    </a>
                    </div>
                </div>
                <div class="blog-tags-box">
                    <div class="tags-box artic-tag-box">
                            <span class="label">分类专栏：</span>
                                <a class="tag-link" href="https://blog.csdn.net/weixin_42159233/category_8617267.html" target="_blank" rel="noopener">风变编程</a>
                            <span class="label">文章标签：</span>
                                <a data-report-click='{"mod":"popu_626","spm":"1001.2101.3001.4223","strategy":"风变编程","ab":"new"}' class="tag-link" href="https://www.csdn.net/tags/MtTaEg1sNjI3MzEtYmxvZwO0O0OO0O0O.html" target="_blank" rel="noopener">风变编程</a>
                                <a data-report-click='{"mod":"popu_626","spm":"1001.2101.3001.4223","strategy":"python小课","ab":"new"}' class="tag-link" href="https://www.csdn.net/tags/MtTaIg0sMjM0NzgtYmxvZwO0O0OO0O0O.html" target="_blank" rel="noopener">python小课</a>
                                <a data-report-click='{"mod":"popu_626","spm":"1001.2101.3001.4223","strategy":"python入门","ab":"new"}' class="tag-link" href="https://www.csdn.net/tags/Mtjagg3sNzQ0LWJsb2cO0O0O.html" target="_blank" rel="noopener">python入门</a>
                    </div>
                </div>
                <div class="slide-content-box">
                </div>
                <div class="operating">
                </div>
            </div>
        </div>
    </div>
    <article class="baidu_pl">
        <div id="article_content" class="article_content clearfix">
        <link rel="stylesheet" href="https://csdnimg.cn/release/blogv2/dist/mdeditor/css/editerView/ck_htmledit_views-b5506197d8.css">
                <div id="content_views" class="markdown_views prism-atom-one-dark">
                    <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
                        <path stroke-linecap="round" d="M5,0 0,2.5 5,5z" id="raphael-marker-block" style="-webkit-tap-highlight-color: rgba(0, 0, 0, 0);"></path>
                    </svg>
                    <p></p>
<div class="toc">
 <h3>python基础语法</h3>
 <ul><li><a href="#_2">第五课</a></li><li><ul><li><a href="#list_4">一、列表&#xff08;list&#xff09;【可边长数组】</a></li><li><ul><li><a href="#_7">&#xff08;一&#xff09;列表中变量类型“可不唯一”</a></li><li><a href="#_15">&#xff08;二&#xff09;元素提取&#xff0c;“左闭右开”</a></li><li><a href="#_34">&#xff08;三&#xff09;切片与取一个元素&#xff0c;“返回值的类型不一样”</a></li><li><a href="#append_44">&#xff08;四&#xff09;append()方法&#xff0c;只能在最后添加“一个”变量</a></li><li><a href="#del_56">&#xff08;五&#xff09;del&#xff0c;删除元素</a></li></ul>
   </li><li><a href="#_66">二、字典</a></li><li><ul><li><a href="#len_71">&#xff08;一&#xff09;len()函数</a></li><li><a href="#_83">&#xff08;二&#xff09;更改值</a></li><li><a href="#_95">&#xff08;三&#xff09;提取元素</a></li><li><a href="#_103">&#xff08;四&#xff09;删除与增加键值对</a></li></ul>
   </li><li><a href="#_117">三、列表与字典的异同</a></li><li><ul><li><a href="#_119">&#xff08;一&#xff09;列表中元素有序&#xff0c;字典中元素无序</a></li><li><a href="#_136">&#xff08;二&#xff09;都支持任意嵌套</a></li></ul>
   </li><li><a href="#_172">四、补充&#xff1a;元组</a></li><li><a href="#INF_181">INF、练习题</a></li><li><ul><li><a href="#_183">&#xff08;一&#xff09;找到那只狼</a></li></ul>
   </li><li><a href="#INF1_205">INF&#43;1、练习题答案</a></li><li><ul><li><a href="#_211">&#xff08;一&#xff09;找到那只狼</a></li></ul>
  </li></ul>
 </li></ul>
</div>
<br />  
<p></p> 
<h1><a id="_2"></a>第五课</h1> 
<p><a href="https://blog.csdn.net/weixin_42159233/article/details/86680847">链接&#xff1a;[ 全文章目录 ]</a></p> 
<h2><a id="list_4"></a>一、列表&#xff08;list&#xff09;【可边长数组】</h2> 
<hr /> 
<h3><a id="_7"></a>&#xff08;一&#xff09;列表中变量类型“可不唯一”</h3> 
<pre><code class="prism language-python">list1 <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span> <span class="token number">18</span><span class="token punctuation">,</span> <span class="token number">1.70</span><span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list1<span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
[&#39;小明&#39;, 18, 1.7]
</code></pre> 
<p> </p> 
<h3><a id="_15"></a>&#xff08;二&#xff09;元素提取&#xff0c;“左闭右开”</h3> 
<pre><code class="prism language-python">list2 <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token number">5</span><span class="token punctuation">,</span><span class="token number">6</span><span class="token punctuation">,</span><span class="token number">7</span><span class="token punctuation">,</span><span class="token number">8</span><span class="token punctuation">,</span><span class="token number">9</span><span class="token punctuation">]</span>

<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">[</span><span class="token punctuation">:</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">:</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">[</span><span class="token punctuation">:</span><span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">:</span><span class="token number">3</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list2<span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">:</span><span class="token number">4</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
[5, 6, 7, 8, 9]
[5, 6, 7, 8, 9]
[7, 8, 9]
[5, 6]
[6, 7]
[7, 8]
</code></pre> 
<p> </p> 
<h3><a id="_34"></a>&#xff08;三&#xff09;切片与取一个元素&#xff0c;“返回值的类型不一样”</h3> 
<pre><code class="prism language-python">students <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token builtin">type</span><span class="token punctuation">(</span>students<span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token builtin">type</span><span class="token punctuation">(</span>students<span class="token punctuation">[</span><span class="token punctuation">:</span><span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
&lt;class &#39;str&#39;&gt;
&lt;class &#39;list&#39;&gt;
</code></pre> 
<p> </p> 
<h3><a id="append_44"></a>&#xff08;四&#xff09;append()方法&#xff0c;只能在最后添加“一个”变量</h3> 
<pre><code class="prism language-python">list3 <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span><span class="token number">2</span><span class="token punctuation">]</span>
list3<span class="token punctuation">.</span>append<span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list3<span class="token punctuation">)</span>
list3<span class="token punctuation">.</span>append<span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">4</span><span class="token punctuation">,</span><span class="token number">5</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>list3<span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
[1, 2, 3]
[1, 2, 3, [4, 5]]
</code></pre> 
<p> </p> 
<h3><a id="del_56"></a>&#xff08;五&#xff09;del&#xff0c;删除元素</h3> 
<pre><code class="prism language-python">students <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小美&#39;</span><span class="token punctuation">]</span>
<span class="token keyword">del</span> students<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>students<span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
[&#39;小红&#39;, &#39;小刚&#39;, &#39;小美&#39;]
</code></pre> 
<p> <br />  </p> 
<h2><a id="_66"></a>二、字典</h2> 
<hr /> 
<div align="center"> 
 <img width="80%" src="https://img-blog.csdnimg.cn/20190117193112693.?x-oss-process&#61;image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjE1OTIzMw&#61;&#61;,size_16,color_FFFFFF,t_70" /> 
</div>
<h3><a id="len_71"></a>&#xff08;一&#xff09;len()函数</h3> 
<p>列表的长度是 <strong>元素</strong> 个数&#xff1b;字典的长度是 <strong>键值对</strong> 个数</p> 
<pre><code class="prism language-python">students <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span>
scores <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">}</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token builtin">len</span><span class="token punctuation">(</span>students<span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token builtin">len</span><span class="token punctuation">(</span>scores<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
3
3
</code></pre> 
<p> </p> 
<h3><a id="_83"></a>&#xff08;二&#xff09;更改值</h3> 
<p>字典中的键具备唯一性&#xff0c;<strong>键唯一,值可重复</strong>。<br /> 也就是说字典里不能同时包含两个’小明’的键&#xff0c;但却可以有两个同为90的值。<br /> 但是&#xff0c;你输入了相同的键&#xff0c;那么字典里原来这个键对应的值会被替换掉</p> 
<pre><code class="prism language-python">scores <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">}</span>
scores<span class="token punctuation">[</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span> <span class="token operator">&#61;</span> <span class="token number">92</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
{&#39;小明&#39;: 95, &#39;小红&#39;: 90, &#39;小刚&#39;: 92}
</code></pre> 
<p> </p> 
<h3><a id="_95"></a>&#xff08;三&#xff09;提取元素</h3> 
<pre><code class="prism language-python">scores <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span> <span class="token number">95</span><span class="token punctuation">,</span> <span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">,</span> <span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">}</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
95
</code></pre> 
<p> </p> 
<h3><a id="_103"></a>&#xff08;四&#xff09;删除与增加键值对</h3> 
<pre><code class="prism language-python">scores <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span> <span class="token number">95</span><span class="token punctuation">,</span> <span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">,</span> <span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">}</span>
<span class="token keyword">del</span> scores<span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">]</span><span class="token comment">#删除</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">)</span>

scores<span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">]</span> <span class="token operator">&#61;</span> <span class="token number">100</span><span class="token comment">#增加</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
{&#39;小红&#39;: 90, &#39;小刚&#39;: 90}
{&#39;小红&#39;: 90, &#39;小刚&#39;: 90, &#39;小明&#39;: 100}
</code></pre> 
<p> <br />  </p> 
<h2><a id="_117"></a>三、列表与字典的异同</h2> 
<hr /> 
<h3><a id="_119"></a>&#xff08;一&#xff09;列表中元素有序&#xff0c;字典中元素无序</h3> 
<p>这也是为什么两者数据读取方法会不同的原因&#xff1a;<br /> 列表有序&#xff0c;要用 <strong>偏移量定位</strong> &#xff1b;字典无序&#xff0c;便通过 <strong>唯一的键来取值</strong> 。</p> 
<pre><code class="prism language-python">students1 <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span>
students2 <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>students1 <span class="token operator">&#61;&#61;</span> students2<span class="token punctuation">)</span>
<span class="token comment">#false</span>
scores1 <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">100</span><span class="token punctuation">}</span>
scores2 <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">100</span><span class="token punctuation">,</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">}</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores1 <span class="token operator">&#61;&#61;</span> scores2<span class="token punctuation">)</span>
<span class="token comment">#true</span>
</code></pre> 
<pre><code>输出&#xff1a;
False
True
</code></pre> 
<p> </p> 
<h3><a id="_136"></a>&#xff08;二&#xff09;都支持任意嵌套</h3> 
<p>除之前学过的数据类型外&#xff0c;列表可嵌套其他列表和字典&#xff0c;字典也可嵌套其他字典和列表。</p> 
<pre><code class="prism language-python">students <span class="token operator">&#61;</span> <span class="token punctuation">[</span><span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小美&#39;</span><span class="token punctuation">]</span><span class="token punctuation">,</span><span class="token punctuation">[</span><span class="token string">&#39;小强&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小兰&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小伟&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小芳&#39;</span><span class="token punctuation">]</span><span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>students<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
小兰
</code></pre> 
<p>此时列表嵌套列表&#xff0c;变成了二维数组<br />  <br /> 同理&#xff0c;字典嵌套字典&#xff1a;</p> 
<pre><code class="prism language-python">scores <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span>
    <span class="token string">&#39;第一组&#39;</span><span class="token punctuation">:</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">100</span><span class="token punctuation">,</span><span class="token string">&#39;小美&#39;</span><span class="token punctuation">:</span><span class="token number">85</span><span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token string">&#39;第二组&#39;</span><span class="token punctuation">:</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;小强&#39;</span><span class="token punctuation">:</span><span class="token number">99</span><span class="token punctuation">,</span><span class="token string">&#39;小兰&#39;</span><span class="token punctuation">:</span><span class="token number">89</span><span class="token punctuation">,</span><span class="token string">&#39;小伟&#39;</span><span class="token punctuation">:</span><span class="token number">93</span><span class="token punctuation">,</span><span class="token string">&#39;小芳&#39;</span><span class="token punctuation">:</span><span class="token number">88</span><span class="token punctuation">}</span>
    <span class="token punctuation">}</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">[</span><span class="token string">&#39;第一组&#39;</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<pre><code>输出&#xff1a;
100
</code></pre> 
<p> <br /> 混合嵌套&#xff1a;</p> 
<pre><code class="prism language-python">students <span class="token operator">&#61;</span> <span class="token punctuation">{<!-- --></span>
    <span class="token string">&#39;第一组&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小美&#39;</span><span class="token punctuation">]</span><span class="token punctuation">,</span>
    <span class="token string">&#39;第二组&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;小强&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小兰&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小伟&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;小芳&#39;</span><span class="token punctuation">]</span>
    <span class="token punctuation">}</span>
scores <span class="token operator">&#61;</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小明&#39;</span><span class="token punctuation">:</span><span class="token number">95</span><span class="token punctuation">,</span><span class="token string">&#39;小红&#39;</span><span class="token punctuation">:</span><span class="token number">90</span><span class="token punctuation">,</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">:</span><span class="token number">100</span><span class="token punctuation">,</span><span class="token string">&#39;小美&#39;</span><span class="token punctuation">:</span><span class="token number">85</span><span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{<!-- --></span><span class="token string">&#39;小强&#39;</span><span class="token punctuation">:</span><span class="token number">99</span><span class="token punctuation">,</span><span class="token string">&#39;小兰&#39;</span><span class="token punctuation">:</span><span class="token number">89</span><span class="token punctuation">,</span><span class="token string">&#39;小伟&#39;</span><span class="token punctuation">:</span><span class="token number">93</span><span class="token punctuation">,</span><span class="token string">&#39;小芳&#39;</span><span class="token punctuation">:</span><span class="token number">88</span><span class="token punctuation">}</span>
    <span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>students<span class="token punctuation">[</span><span class="token string">&#39;第一组&#39;</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>scores<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token string">&#39;小刚&#39;</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<p> <br />  </p> 
<h2><a id="_172"></a>四、补充&#xff1a;元组</h2> 
<hr /> 
<p>元组由小括号框起&#xff0c;除 <strong>不能改变元素</strong> 外&#xff0c;其他性质与列表相似</p> 
<pre><code class="prism language-python">tuple1 <span class="token operator">&#61;</span> <span class="token punctuation">(</span><span class="token string">&#39;A&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;B&#39;</span><span class="token punctuation">)</span>
</code></pre> 
<p> <br />  <br />  </p> 
<h2><a id="INF_181"></a>INF、练习题</h2> 
<hr /> 
<h3><a id="_183"></a>&#xff08;一&#xff09;找到那只狼</h3> 
<blockquote> 
 <p>练习目标<br /> 在层层嵌套的各种数据类型中&#xff0c;准确地提取出你需要的数据。</p> 
</blockquote> 
<p>练习要求</p> 
<p>在未来世界&#xff0c;一个新建的童话镇吸引了不少人入住。<br /> 不过&#xff0c;在人群里隐藏着一只狼&#xff0c;会威胁大家的安全。<br /> 童话镇的镇长希望你能找到它&#xff0c;并揭发其身份。<br /> 用程序语言就是说&#xff1a;列表中有个字符串是“狼”&#xff0c;将其打印出来吧。</p> 
<pre><code class="prism language-python"><span class="token comment">#变量定义</span>
townee <span class="token operator">&#61;</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{<!-- --></span><span class="token string">&#39;海底王国&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;小美人鱼&#39;</span><span class="token string">&#39;海之王&#39;</span><span class="token string">&#39;小美人鱼的祖母&#39;</span><span class="token string">&#39;五位姐姐&#39;</span><span class="token punctuation">]</span><span class="token punctuation">,</span><span class="token string">&#39;上层世界&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;王子&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;邻国公主&#39;</span><span class="token punctuation">]</span><span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token string">&#39;丑小鸭&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;坚定的锡兵&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;睡美人&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;青蛙王子&#39;</span><span class="token punctuation">,</span>
    <span class="token punctuation">[</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;主角&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;小红帽&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;配角1&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;外婆&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;配角2&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;猎人&#39;</span><span class="token punctuation">}</span><span class="token punctuation">,</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;反面角色&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;狼&#39;</span><span class="token punctuation">}</span><span class="token punctuation">]</span>
    <span class="token punctuation">]</span>
</code></pre> 
<p> <br />  <br />  <br />  </p> 
<h2><a id="INF1_205"></a>INF&#43;1、练习题答案</h2> 
<hr /> 
<p> <br />  <br />  <br />  </p> 
<h3><a id="_211"></a>&#xff08;一&#xff09;找到那只狼</h3> 
<p>考察点&#xff1a;<br /> 1.数据的嵌套<br /> 2.数据的提取</p> 
<pre><code class="prism language-python">townee <span class="token operator">&#61;</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{<!-- --></span><span class="token string">&#39;海底王国&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;小美人鱼&#39;</span><span class="token string">&#39;海之王&#39;</span><span class="token string">&#39;小美人鱼的祖母&#39;</span><span class="token string">&#39;五位姐姐&#39;</span><span class="token punctuation">]</span><span class="token punctuation">,</span><span class="token string">&#39;上层世界&#39;</span><span class="token punctuation">:</span><span class="token punctuation">[</span><span class="token string">&#39;王子&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;邻国公主&#39;</span><span class="token punctuation">]</span><span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token string">&#39;丑小鸭&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;坚定的锡兵&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;睡美人&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;青蛙王子&#39;</span><span class="token punctuation">,</span>
    <span class="token punctuation">[</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;主角&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;小红帽&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;配角1&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;外婆&#39;</span><span class="token punctuation">,</span><span class="token string">&#39;配角2&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;猎人&#39;</span><span class="token punctuation">}</span><span class="token punctuation">,</span><span class="token punctuation">{<!-- --></span><span class="token string">&#39;反面角色&#39;</span><span class="token punctuation">:</span><span class="token string">&#39;狼&#39;</span><span class="token punctuation">}</span><span class="token punctuation">]</span>
    <span class="token punctuation">]</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>townee<span class="token punctuation">[</span><span class="token number">5</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">[</span><span class="token string">&#39;反面角色&#39;</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
</code></pre> 
<p> <br />  <br /> <a href="https://blog.csdn.net/weixin_42159233/article/details/86680847">链接&#xff1a;[ 全文章目录 ]</a></p>
                </div>
                <link href="https://csdnimg.cn/release/blogv2/dist/mdeditor/css/editerView/markdown_views-d7a94ec6ab.css" rel="stylesheet">
                <link href="https://csdnimg.cn/release/blogv2/dist/mdeditor/css/style-f1c5feb645.css" rel="stylesheet">
        </div>
    </article>
</div>
<div class="more-toolbox" id="toolBarBox">
    <span id="fixedBar"></span>
    <div class="left-toolbox">
        <ul class="toolbox-list">
            <li class="tool-item tool-item-size tool-active is-like" id="is-like"><a>
            <img style="display:none;" id="is-like-imgactive-animation-like" class="animation-dom active-animation" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarThumbUpactive.png" alt="">
            <img class="isactive" style="display:none" id="is-like-imgactive" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarThumbUpactive.png" alt="">
            <img class="isdefault" style="display:block" id="is-like-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarThumbUp.png" alt="">   
            <span class="name" id="is-like-span">点赞</span>
            <span id="spanCount" class="count">
                    22
            </span>
            </a></li>
            <li class="tool-item tool-item-size tool-active tool-item-comment">
                <a href="#commentBox">
                    <img class="isdefault" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarComment.png" alt="">
                    <img class="isactive" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCommentactive.png" style="display:none;" alt="">
                    <span class="name">评论</span>
                    <span class="count">
                        4
                    </span>
                </a>
            </li>
            <li class="tool-item tool-item-size tool-active tool-QRcode" id="tool-share">
                <a href="javascript:;" data-report-click='{"mod":"1582594662_002","spm":"1001.2101.3001.4129","ab":"new"}'>
                    <img class="isdefault" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarShare.png" alt="">
                    <img class="isactive" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarShareactive.png" style="display:none;" alt="">
                    <span class="name">分享</span>
                </a>
                <div class="QRcode" id="tool-QRcode" style="left:-92%;">
                    <span id="QRcode-close">x</span>
                    <p class="title">
                    海报分享
                    </p>
                    <div id='shareCode'></div>
                    <p>
                    扫一扫，分享海报
                    </p>
                </div>
            </li>
            <li class="tool-item tool-item-size tool-active is-collection ">
                <a href="javascript:;" data-report-click='{"mod":"popu_824","spm":"1001.2101.3001.4130","ab":"new"}'>
                    <img style="display:none" id="is-collection-img-collection" class="animation-dom active-animation" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCollectionActive.png" alt="">
                    <img class="isdefault" id="is-collection-img" style="display:block" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCollect.png" alt="">
                    <img class="isactive" id="is-collection-imgactive" style="display:none" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarCollectionActive.png" alt="">
                    <span class="name" id="is-collection">收藏</span>
                    <span class="count get-collection" id="get-collection">
                        37
                    </span>
                </a>
            </li>
            <li class="tool-item tool-item-size tool-active tool-more">
              <a class="article-report">
                <img class="isdefault" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarReport.png" alt="">
                <img class="isactive" src="https://csdnimg.cn/release/blogv2/dist/pc/img/tobarReportactive.png" style="display:none;" alt="">
                <span class="name">举报</span>
              </a>
            </li>
            <li class="tool-item">
                    <a class="tool-attend tool-bt-button tool-bt-attend" href="javascript:;" data-report-view='{"mod":"1592215036_002","spm":"1001.2101.3001.4232","extend1":"关注"}'>关注</a>
                <a class="tool-item-follow active-animation" style="display:none;">关注</a>
            </li>
            <li class="tool-item">
                    <p class="company active" id="health-companies" href="javascript:;" >一键三连</p>
                <span class="triplet-prompt">点赞Mark关注该博主, 随时了解TA的最新博文<img class="close-prompt" src="https://csdnimg.cn/release/blogv2/dist/pc/img/closePrompt.png"></span>
            </li>
        </ul>
        <div style="display:flex">
         </div>
         <div class="hot-word-tip-box">
          <span class="hot-word-text">已标记关键词</span>
          <span class="hot-word-count"></span> 
          <span class="hot-word-bar"></span>
          <span class="hot-word-clear">清除标记</span>
        </div>
    </div>  
</div>
<script type=text/javascript crossorigin src="https://csdnimg.cn/release/phoenix/production/qrcode-7c90a92189.min.js"></script>
<script src="//g.csdnimg.cn/??sharewx/1.2.1/sharewx.js" type="text/javascript"></script>
<script type="text/javascript" crossorigin src="https://g.csdnimg.cn/collection-box/2.0.3/collection-box.js"></script>
                <div id="dmp_ad_58" style="width:100%;overflow-x:hidden"><div id="kp_box_58" data-pid="58"><script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="fluid"
     data-ad-layout-key="-gi-21+3s-18+2p"
     data-ad-client="ca-pub-1076724771190722"
     data-ad-slot="5869798804"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script><img class="pre-img-lasy" data-src="https://kunyu.csdn.net/1.png?p=58&a=3778&c=0&k=&spm=1001.2101.3001.5002&d=1&t=3&u=f4daba63f13c47438806bbffd7f65898" style="display: block;width: 0px;height: 0px;"></div></div>
            <div class="second-recommend-box recommend-box">
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42159233/article/details/86609827"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-1.baidujs\"}","dist_request_id":"","index":"1","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86609827"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86609827" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-1.baidujs\"}","dist_request_id":"","index":"1","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86609827"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.baidujs'>
					【<em>风变</em><em>编程</em>】第八、九课<em>笔记</em>
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42159233" target="_blank"><span class="blog-title">weixin_42159233的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-23</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42159233/article/details/86609827" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-1.baidujs\"}","dist_request_id":"","index":"1","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86609827"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">python基础语法第八课python中的格式化字符串
&amp;amp;amp;amp;nbsp;
第八课
python中的格式化字符串


语法：print(&rsquo; 格式串 &rsquo; % ( 变量 ))

s = &#39;abc&#39;
i = 123
f = 1.23
print(&#39;字符串：%s 整形：%d 浮点型: %f&#39; % (s, i, f))

输出：
字符串：abc 整形：123 浮点型: 1.230000

&amp;amp;amp;amp;nbsp;
2. 单变...</div>
			</a>
		</div>
	</div>
</div>
            </div>
<a id="commentBox" name="commentBox"></a>
<div class="comment-box">
	<div class="comment-edit-box d-flex">
		<a id="commentsedit"></a>
		<div class="user-img">
			<a href="https://blog.csdn.net/weixin_44724371" target="_blank">
				<img class="" src="https://profile.csdnimg.cn/1/4/1/3_weixin_44724371">
			</a>
		</div>
		<form id="commentform">
			<img class="comment-sofa-flag" src="https://csdnimg.cn/release/blogv2/dist/pc/img/commentFlag@2x.png">
      <textarea class="comment-content" name="comment_content" id="comment_content" placeholder="优质评论可以帮助作者获得更高权重" maxlength="1000"></textarea>
			<div class="comment-emoticon"><img class="comment-emoticon-img" data-url="https://csdnimg.cn/release/blogv2/dist/pc/img/" src="https://csdnimg.cn/release/blogv2/dist/pc/img/emoticon.png" alt="表情包"></div> 
      <span class="comment-emoticon-tip">插入表情</span>
      <div class="comment-emoticon-box">
        <div class="comment-emoticon-img-box">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:001.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/001.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:002.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/002.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:003.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/003.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:004.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/004.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:005.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/005.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:006.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/006.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:007.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/007.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:008.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/008.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:009.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/009.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:010.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/010.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:011.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/011.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:012.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/012.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:013.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/013.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:014.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/014.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:015.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/015.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:016.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/016.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:017.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/017.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:018.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/018.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:019.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/019.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:020.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/020.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:021.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/021.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:022.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/022.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:023.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/023.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:024.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/024.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:025.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/025.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:026.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/026.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:027.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/027.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:028.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/028.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:029.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/029.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:030.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/030.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:031.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/031.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:032.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/032.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:033.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/033.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:034.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/034.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:035.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/035.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:036.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/036.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:037.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/037.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:038.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/038.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:039.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/039.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:040.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/040.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:041.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/041.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:042.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/042.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:043.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/043.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:044.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/044.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:045.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/045.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:046.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/046.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:047.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/047.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:048.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/048.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:049.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/049.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:050.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/050.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:051.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/051.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:052.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/052.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:053.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/053.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:054.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/054.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:055.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/055.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:056.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/056.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:057.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/057.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:058.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/058.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:059.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/059.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:060.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/060.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:061.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/061.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:062.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/062.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:063.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/063.png">
            <img class="emoticon-monkey-img" data-emoticon="[face]monkey2:064.png[/face]" src="https://g.csdnimg.cn/static/face/monkey2/064.png">
        </div>
      </div>
      <div class="opt-box">
				<div id="ubbtools" class="add_code">
					<a href="#insertcode" code="code" target="_self"><i class="icon iconfont icon-daima"></i></a>
				</div>
				<input type="hidden" id="comment_replyId" name="comment_replyId">
				<input type="hidden" id="article_id" name="article_id" value="86529883">
				<input type="hidden" id="comment_userId" name="comment_userId" value="">
				<input type="hidden" id="commentId" name="commentId" value="">
				<div class="dropdown" id="myDrap">
					<a class="dropdown-face d-flex align-items-center" data-toggle="dropdown" role="button"
						aria-haspopup="true" aria-expanded="false">
						<div class="txt-selected text-truncate">添加代码片</div>
						<svg class="icon d-block" width="200px" height="100.00px" viewBox="0 0 2048 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"><path  d="M597.33333292 298.666667h853.333334L1023.99999992 725.333333 597.33333292 298.666667z"  /></svg>
					</a>
					<ul class="dropdown-menu" id="commentCode" aria-labelledby="drop4">
						<li><a data-code="html">HTML/XML</a></li>
						<li><a data-code="objc">objective-c</a></li>
						<li><a data-code="ruby">Ruby</a></li>
						<li><a data-code="php">PHP</a></li>
						<li><a data-code="csharp">C</a></li>
						<li><a data-code="cpp">C++</a></li>
						<li><a data-code="javascript">JavaScript</a></li>
						<li><a data-code="python">Python</a></li>
						<li><a data-code="java">Java</a></li>
						<li><a data-code="css">CSS</a></li>
						<li><a data-code="sql">SQL</a></li>
						<li><a data-code="plain">其它</a></li>
					</ul>
				</div>
				<div class="right-box" id="rightBox" data-type="2">
							<span id="tip_comment" class="tip">还能输入<em>1000</em>个字符</span>
							<a data-report-click='{"mod":"1582594662_003","spm":"1001.2101.3001.4227","ab":"new"}'><input type="submit"
									class="btn btn-sm btn-comment" value="发表评论"></a>
				</div>
			</div>
		</form>
		<input type="button" class="bt-comment-show" value="评论">
	</div>
	<div class="comment-list-container">
		<a id="comments"></a>
		<div class="comment-list-box">
		</div>
		<div id="commentPage" class="pagination-box d-none"></div>
		<div class="opt-box text-center">
			<div class="btn btn-sm btn-link-blue" id="btnMoreComment"></div>
		</div>
	</div>
</div>            <div class="recommend-tit-mod">相关推荐</div>
            <div class="recommend-box insert-baidu-box">
                <div class="recommend-item-box clearfix" style="display:none"></div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_26717681/article/details/108497003"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-2.baidujs\"}","dist_request_id":"","index":"2","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_26717681/article/details/108497003"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_26717681/article/details/108497003" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-2.baidujs\"}","dist_request_id":"","index":"2","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_26717681/article/details/108497003"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.baidujs'>
					<em>风变</em><em>编程</em>第18关 <em>编程</em>思维_动态<em>编程</em>变得容易
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_26717681" target="_blank"><span class="blog-title">weixin_26717681的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">08-25</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					339
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_26717681/article/details/108497003" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-2.baidujs\"}","dist_request_id":"","index":"2","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_26717681/article/details/108497003"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1"><em>风变</em><em>编程</em>第18关 <em>编程</em>思维Imagine you have a bag of coins where each coin is of value 5 dollars and you have to find the total amount of money available in that bag, What would you do to find the total amount in t...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42641395/article/details/87987802"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-3.baidujs\"}","dist_request_id":"","index":"3","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42641395/article/details/87987802"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42641395/article/details/87987802" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-3.baidujs\"}","dist_request_id":"","index":"3","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42641395/article/details/87987802"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.baidujs'>
					【学习<em>笔记</em>】python实现excel数据处理
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42641395" target="_blank"><span class="blog-title">凌bb的笔记本</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">02-27</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					5万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42641395/article/details/87987802" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-3.baidujs\"}","dist_request_id":"","index":"3","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42641395/article/details/87987802"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-3.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">概述
Excel固然功能强大，也有许多函数实现数据处理功能，但是Excel仍需大量人工操作，虽然能嵌入VB脚本宏，但也容易染上宏病毒。python作为解释性语言，在数据处理方面拥有强大的函数库以及第三方库，excel作为主要基础数据源之一，在利用数据进行分析前往往需要预先对数据进行整理。因此，本文就python处理excel数据进行了学习，主要分为python对excel数据处理的常用数据类型以及...</div>
			</a>
		</div>
	</div>
</div>
		<dl id="recommend-item-box-tow" class="recommend-item-box type_blog clearfix">
			
		</dl>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42159233/article/details/86516196"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-4.baidujs\"}","dist_request_id":"","index":"4","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86516196"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86516196" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-4.baidujs\"}","dist_request_id":"","index":"4","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86516196"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-4.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-4.baidujs'>
					【<em>风变</em><em>编程</em>】第三、四课<em>笔记</em>
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42159233" target="_blank"><span class="blog-title">weixin_42159233的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-16</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42159233/article/details/86516196" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-4.baidujs\"}","dist_request_id":"","index":"4","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86516196"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-4.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-4.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">python基础语法第三课一、条件判断（一）if...else...（一定要加冒号）（二）if...elif...else...（一定要加冒号）
第三课
一、条件判断
（一）if&hellip;else&hellip;（一定要加冒号）
想要让else生效，一定需要一个平级的前提条件，但这个前提条件却不一定是条件判断语句
下面这种写法也成立
for i in range(10):
    if i == 11:
       ...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/qq_42434162/article/details/88321139"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-5.baidujs\"}","dist_request_id":"","index":"5","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/qq_42434162/article/details/88321139"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/qq_42434162/article/details/88321139" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-5.baidujs\"}","dist_request_id":"","index":"5","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/qq_42434162/article/details/88321139"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.baidujs'>
					<em>风变</em><em>编程</em>，第十关，石头剪刀布
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/qq_42434162" target="_blank"><span class="blog-title">qq_42434162的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">03-07</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					7070
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/qq_42434162/article/details/88321139" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-5.baidujs\"}","dist_request_id":"","index":"5","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/qq_42434162/article/details/88321139"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-5.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">import random

# 出拳
punches = [&#39;石头&#39;,&#39;剪刀&#39;,&#39;布&#39;]
computer_choice = random.choice(punches)
user_choice = &#39;&#39;
user_choice = input(&#39;请出拳：（石头、剪刀、布）&#39;)  # 请用户输入选择
while user_choice not in punches:  # 当用户输入错误，提示错...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/sihan_kanglin/article/details/90604196"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-6.baidujs\"}","dist_request_id":"","index":"6","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/sihan_kanglin/article/details/90604196"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/sihan_kanglin/article/details/90604196" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-6.baidujs\"}","dist_request_id":"","index":"6","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/sihan_kanglin/article/details/90604196"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-6.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-6.baidujs'>
					<em>风变</em><em>编程</em>&middot;第5关<em>笔记</em>  for循环和while循环-消灭该死的重复
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/sihan_kanglin" target="_blank"><span class="blog-title">sihan_kanglin的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">05-27</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					5850
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/sihan_kanglin/article/details/90604196" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-6.baidujs\"}","dist_request_id":"","index":"6","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/sihan_kanglin/article/details/90604196"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-6.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-6.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">@[TOC]<em>风变</em><em>编程</em>&middot;第5关  for循环和while循环-消灭该死的重复
课程目标

List item 掌握for&hellip;in&hellip;循环的格式与特点，了解其数据传递
熟练掌握for&hellip;in&hellip;与range()函数的结合使用
掌握while循环的格式与特点
区别for&hellip;in&hellip;循环与while循环

课程难点

List item range()函数各个参数的含义
for&hellip;in&hellip;循环与while循环的变量更迭
...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_44678387/article/details/101014594"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-7.baidujs\"}","dist_request_id":"","index":"7","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_44678387/article/details/101014594"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_44678387/article/details/101014594" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-7.baidujs\"}","dist_request_id":"","index":"7","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_44678387/article/details/101014594"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-7.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-7.baidujs'>
					<em>风变</em><em>编程</em>课后习题答案
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_44678387" target="_blank"><span class="blog-title">weixin_44678387的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">09-19</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_44678387/article/details/101014594" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-7.baidujs\"}","dist_request_id":"","index":"7","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_44678387/article/details/101014594"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-7.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-7.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1"><em>风变</em><em>编程</em>课后习题答案

不用修改代码，直接运行即可，尝试多输入几次非数字
print(&rsquo;\n欢迎使用除法计算器！\n&rsquo;)
while True:
try:
x = input(&lsquo;请你输入除数：&rsquo;)
y = input(&lsquo;请你输入被除数：&rsquo;)
z = float(x)/float(y)
print(x,&rsquo;/&rsquo;,y,&rsquo;=&rsquo;,z)
print(x/y)
break  # 默认每次只计算一次，所以在这里写...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42464054/article/details/94323922"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-8.baidujs\"}","dist_request_id":"","index":"8","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_42464054/article/details/94323922"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42464054/article/details/94323922" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-8.baidujs\"}","dist_request_id":"","index":"8","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_42464054/article/details/94323922"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-8.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-8.baidujs'>
					Y05 - 999、Python - <em>风变</em><em>编程</em>
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42464054" target="_blank"><span class="blog-title">吾心持剑，剑锋披靡</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">06-30</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					2966
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42464054/article/details/94323922" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-8.baidujs\"}","dist_request_id":"","index":"8","strategy":"2~default~BlogCommendFromBaidu~default","dest":"https://blog.csdn.net/weixin_42464054/article/details/94323922"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-8.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-8.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">初学耗时：999h
注：CSDN手机端暂不支持章节内链跳转，但外链可用，更好体验还请上电脑端。


『&nbsp;&nbsp;&nbsp;因为要去见那个不一般的人，所以我就不能是一般人。』

&emsp;Y99、专找免费随心学 - Y系列总纲

&emsp;ギ 舒适区ゾ&emsp;||&emsp;♂ 累觉无爱 ♀





 Y05系列、Python - <em>风变</em><em>编程</em>
 
 第 0 章：千寻的名字
 
Y05 - 001：
Y05 - ...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/PyhtonChen/article/details/102658222"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-9.baidujs\"}","dist_request_id":"","index":"9","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/PyhtonChen/article/details/102658222"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/PyhtonChen/article/details/102658222" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-9.baidujs\"}","dist_request_id":"","index":"9","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/PyhtonChen/article/details/102658222"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-9.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-9.baidujs'>
					<em>风变</em><em>编程</em>Python小课学习之旅
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/PyhtonChen" target="_blank"><span class="blog-title">PyhtonChen的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">10-21</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/PyhtonChen/article/details/102658222" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-9.baidujs\"}","dist_request_id":"","index":"9","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/PyhtonChen/article/details/102658222"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-9.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-9.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">先说说我是怎样与Python结缘的吧，我之前一直就职在互联网公司，是负责公司品牌设计的，已从事设计工作十余年了，也是到了一个瓶颈期，过去的知识已经快跟不上时代的发展，想给自己充充电，拓展一下知识。在今年我读了《人类简史》和《未来简史》这两本书，我突然就受启发了，作者认为未来发展的两大方向是生物科技和人工智能，而且发现书里面用了很多<em>编程</em>思维，这是我后来发现的。再者，发现Python是如今最火的<em>编程</em>语...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_download clearfix" data-url="https://download.csdn.net/download/mumuabiubiubiu/13211668"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-download-2~default~BlogCommendFromMachineLearnPai2~default-10.baidujs\"}","dist_request_id":"","index":"10","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://download.csdn.net/download/mumuabiubiubiu/13211668"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://download.csdn.net/download/mumuabiubiubiu/13211668" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-download-2~default~BlogCommendFromMachineLearnPai2~default-10.baidujs\"}","dist_request_id":"","index":"10","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://download.csdn.net/download/mumuabiubiubiu/13211668"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-download-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-10.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-download-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-10.baidujs'>
					<em>风变</em><em>编程</em>python体验课-第0关 千寻的名字（print()函数与变量）
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info display-flex">
					<span class="info-block">12-01</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://download.csdn.net/download/mumuabiubiubiu/13211668" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-download-2~default~BlogCommendFromMachineLearnPai2~default-10.baidujs\"}","dist_request_id":"","index":"10","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://download.csdn.net/download/mumuabiubiubiu/13211668"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-download-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-10.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-download-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-10.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">小白体验课<em>笔记</em>分享，共4关。8.9元小课体验心得：闯关式学习的软件、app和网站我都体验过，本次<em>风变</em><em>编程</em>学习还是非常愉快的，每天按时完成，大约20分钟，自己做<em>笔记</em>比发的<em>笔记</em>更加高效。奈何价格太贵，遂选择在CSDN上蹲大佬们的随手帖嘻嘻</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42159233/article/details/86513509"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-11.baidujs\"}","dist_request_id":"","index":"11","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86513509"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86513509" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-11.baidujs\"}","dist_request_id":"","index":"11","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86513509"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-11.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-11.baidujs'>
					【<em>风变</em><em>编程</em>】第二课<em>笔记</em>
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42159233" target="_blank"><span class="blog-title">weixin_42159233的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-16</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					8274
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42159233/article/details/86513509" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-11.baidujs\"}","dist_request_id":"","index":"11","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86513509"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-11.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-11.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">python基础语法第二课一、数据类型（一）字符串string(str)（二）整数integer(int)、浮点数float二、数据拼接（一）栗子（二）type()函数三、数据转换
第二课
一、数据类型

（一）字符串string(str)

单引号&ldquo; &rsquo; &rdquo;、双引号&ldquo; &amp;amp;quot; &rdquo;、三个单引号&ldquo; &lsquo;&rsquo;&rsquo; &rdquo;均能表示字符串
&amp;amp;amp;nbsp;

（二）整数integer(int)、浮点数float

a**b...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_39713763/article/details/110735026"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-12.baidujs\"}","dist_request_id":"","index":"12","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39713763/article/details/110735026"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_39713763/article/details/110735026" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-12.baidujs\"}","dist_request_id":"","index":"12","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39713763/article/details/110735026"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-12.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-12.baidujs'>
					<em>风变</em><em>编程</em>的python8.9元_如何看待<em>风变</em><em>编程</em>的 Python 网课？
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_39713763" target="_blank"><span class="blog-title">weixin_39713763的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">12-04</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					747
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_39713763/article/details/110735026" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-12.baidujs\"}","dist_request_id":"","index":"12","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39713763/article/details/110735026"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-12.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-12.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">我也是刚学phton<em>编程</em>，属于python的小白。看到<em>风变</em><em>编程</em>的广告，体验只要8.9元，而且用python可以做很多事情，例如：自动化办公，数据分析，人工智能等等。可以完成这么多的事情，深深的吸引了我，而且主要还是很便宜的吗，我就抱着试着学一学，进入了我的课程。打开<em>风变</em><em>编程</em>的网页，进入到我的课程，每一关都是关卡回合。在这一点来说有点像游戏，每完成一关，心里都会有小惊喜，小小的成就感。明天可能又会一...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_42159233/article/details/86545593"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-13.baidujs\"}","dist_request_id":"","index":"13","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86545593"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86545593" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-13.baidujs\"}","dist_request_id":"","index":"13","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86545593"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-13.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-13.baidujs'>
					【<em>风变</em><em>编程</em>】第七课<em>笔记</em>
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_42159233" target="_blank"><span class="blog-title">weixin_42159233的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-18</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1万+
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_42159233/article/details/86545593" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-13.baidujs\"}","dist_request_id":"","index":"13","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_42159233/article/details/86545593"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-13.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-13.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">python基础语法第七课一、布尔值与布尔运算（一）bool()函数（二）and、or、not、in、not in五种运算（略）二、break、continue、pass、else语句（一）else
&amp;amp;nbsp;
第七课
一、布尔值与布尔运算


（一）bool()函数
判断真假
bool(False)

输出：
False

&amp;amp;nbsp;
（二）and、or、not、in、not in五种运算（...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/leianuo123/article/details/102656625"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-14.baidujs\"}","dist_request_id":"","index":"14","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/leianuo123/article/details/102656625"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/leianuo123/article/details/102656625" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-14.baidujs\"}","dist_request_id":"","index":"14","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/leianuo123/article/details/102656625"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-14.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-14.baidujs'>
					<em>风变</em><em>编程</em>Python9 函数的学习
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/leianuo123" target="_blank"><span class="blog-title">leianuo123的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">10-21</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					3859
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/leianuo123/article/details/102656625" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-14.baidujs\"}","dist_request_id":"","index":"14","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/leianuo123/article/details/102656625"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-14.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-14.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">那么在进行函数学习之前，我们首先得来了解一下什么是函数
简单地说，函数就是<em>编程</em>语言中存在的一个模块，他是组织好的，可以重复使用的，用来实现单一功能的代码。
函数function()括号里跟的是函数的参数。参数指向的是函数要接受，要处理的数据，除了Python自带的常见的函数之外，比如input(),print(),range()等等，还包括有我们根据我们自身的需要设计出来的能解决我们自身问题的函数...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_39371691/article/details/103827942"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-15.baidujs\"}","dist_request_id":"","index":"15","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39371691/article/details/103827942"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_39371691/article/details/103827942" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-15.baidujs\"}","dist_request_id":"","index":"15","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39371691/article/details/103827942"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-15.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-15.baidujs'>
					<em>风变</em><em>编程</em>：python第0关，千寻的名字
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_39371691" target="_blank"><span class="blog-title">weixin_39371691的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-03</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					1881
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_39371691/article/details/103827942" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-15.baidujs\"}","dist_request_id":"","index":"15","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39371691/article/details/103827942"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-15.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-15.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">1.print函数：

print()内不带引号：让计算机读懂括号内的内容并输出结果



 print()内带引号：让计算机无需理解，原样复述引号内的内容。其中，又分为单引号，双引号，三引号：

正常使用单引号和双引号都是可以的，三引号可以打印出换行字符串，ji将引号内所有的内容打印出来。

例如：


print(&#39;我愿意留在汤婆婆的澡堂里工作两年，
第一年在锅炉房和锅炉爷爷一起烧锅炉水，...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/weixin_39568781/article/details/110590112"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-16.baidujs\"}","dist_request_id":"","index":"16","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39568781/article/details/110590112"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/weixin_39568781/article/details/110590112" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-16.baidujs\"}","dist_request_id":"","index":"16","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39568781/article/details/110590112"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-16.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-16.baidujs'>
					msb600已退出代码为5_【<em>风变</em><em>编程</em>】第7关学习<em>笔记</em>及代码扩展
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/weixin_39568781" target="_blank"><span class="blog-title">weixin_39568781的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">11-20</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					2
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/weixin_39568781/article/details/110590112" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-16.baidujs\"}","dist_request_id":"","index":"16","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/weixin_39568781/article/details/110590112"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-16.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-16.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">第七关的重点知识点函数为（计时属性）time模块 和（随机属性） random模块通过前面几关的学习，我们脑海中定然是有了以下这些函数的用法：列表、字典、for循环、while循环以及 if 函数、input函数那么，既然是第七关了，以上函数必定是都会用到的。所以，我们先来看最简单的重复利用来运行一个简单的重复pk游戏。这里用到的就是for循环，简单2次循环下的print运行：了解了大概的游戏循...</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/Hendersonobrien/article/details/113066073"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-17.baidujs\"}","dist_request_id":"","index":"17","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/Hendersonobrien/article/details/113066073"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/Hendersonobrien/article/details/113066073" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-17.baidujs\"}","dist_request_id":"","index":"17","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/Hendersonobrien/article/details/113066073"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.baidujs'>
					【<em>风变</em><em>编程</em>】Python基础语法 练习题答案
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/Hendersonobrien" target="_blank"><span class="blog-title">Hendersonobrien的博客</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">01-28</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					533
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/Hendersonobrien/article/details/113066073" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-17.baidujs\"}","dist_request_id":"","index":"17","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/Hendersonobrien/article/details/113066073"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">【<em>风变</em><em>编程</em>】Python基础语法 练习题答案【壹】print()函数与变量【1】打印皮卡丘【2】进阶练习-打印无脸男【贰】数据类型与转换
点击这里前往 Python基础语法 用法查询<em>笔记</em>。
点击这里前往 Python基础语法 深度理解<em>笔记</em>。
点击这里前往 Python基础语法 课堂<em>笔记</em>。
点击这里前往 Python基础语法 练习题答案。
【壹】print()函数与变量
【1】打印皮卡丘
&gt;&gt;&gt;print(
    &#39;&#39;&#39; へ　　　　　／|
　　/＼7　　　 &ang;＿/
　 /　│　　 ／　／
</div>
			</a>
		</div>
	</div>
</div>
<div class="recommend-item-box type_blog clearfix" data-url="https://blog.csdn.net/aixiangfei2/article/details/32932185"  data-report-view='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-18.baidujs\"}","dist_request_id":"","index":"18","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/aixiangfei2/article/details/32932185"}'>
	<div class="content-box">
		<div class="content-blog display-flex">
			<div class="title-box">
				<a href="https://blog.csdn.net/aixiangfei2/article/details/32932185" class="tit ellipsis-online ellipsis-online-1" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-18.baidujs\"}","dist_request_id":"","index":"18","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/aixiangfei2/article/details/32932185"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-18.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-18.baidujs'>
					7-7 <em>编程</em>练习题答案
				</a>
			</div>
			<div class="info-box display-flex">
				<div class="info">
					<a href="https://blog.csdn.net/aixiangfei2" target="_blank"><span class="blog-title">aixiangfei2的专栏</span></a>
				</div>
				<div class="info display-flex">
					<span class="info-block time">06-21</span>
					<span class="info-block read"><img class="read-img" src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					383
					</span>
				</div>
			</div>
		</div>
		<div class="desc-box">
			<a href="https://blog.csdn.net/aixiangfei2/article/details/32932185" target="_blank"  data-report-click='{"ab":"new","mod":"popu_387","extra":"{\"utm_medium\":\"distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromMachineLearnPai2~default-18.baidujs\"}","dist_request_id":"","index":"18","strategy":"2~default~BlogCommendFromMachineLearnPai2~default","dest":"https://blog.csdn.net/aixiangfei2/article/details/32932185"}'  data-report-query='utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-18.baidujs&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-18.baidujs'>
				<div class="desc ellipsis-online ellipsis-online-1">import java.util.Scanner;

public class Test
{
	public static void main(String[] args)
	{
		double[][] points = {
			{-1, 0, 3}, {-1, -1, -1}, {4, 1, 1}, 
			{2, 0.5, 9}, {3.5, 2, -1}, {3, 1.5, 3}, 
	</div>
			</a>
		</div>
	</div>
</div>
            </div>
            <div class="template-box">
                <span>©️2020 CSDN</span>
                <span>皮肤主题: 精致技术</span>
                <span> 设计师:CSDN官方博客</span>
                <span>
                    <a href="https://blog.csdn.net/" class="back-home c-blue c-blue-hover c-blue-focus">返回首页</a>
                </span>
            </div>
<div class="blog-footer-bottom" style="margin-top:10px;"></div>
<script src="https://g.csdnimg.cn/common/csdn-footer/csdn-footer.js" data-isfootertrack="false" type="text/javascript"></script>
<script type="text/javascript">
    window.csdn.csdnFooter.options = {
        el: '.blog-footer-bottom',
        type: 2
    }
</script>        </main>
<aside class="blog_container_aside">
	<div id="asideProfile" class="aside-box">
    <div class="profile-intro d-flex">
        <div class="avatar-box d-flex justify-content-center flex-column">
            <a href="https://blog.csdn.net/weixin_42159233" data-report-click='{"mod":"popu_379","spm":"1001.2101.3001.4121","dest":"https://blog.csdn.net/weixin_42159233","ab":"new"}'>
                <img src="https://profile.csdnimg.cn/5/A/6/3_weixin_42159233" class="avatar_pic">
            </a>
        </div>
        <div class="user-info d-flex flex-column profile-intro-name-box">
            <div class="profile-intro-name-boxTop">
                <a href="https://blog.csdn.net/weixin_42159233" class="" id="uid" title="ArtlexKylin" data-report-click='{"mod":"popu_379","spm":"1001.2101.3001.4122","dest":"https://blog.csdn.net/weixin_42159233","ab":"new"}'>
                    <span class="name " username="weixin_42159233">ArtlexKylin</span>
                </a>
                <span>
                </span>
                <span class="flag expert-blog">
                <span class="bubble">CSDN认证博客专家</span>
                </span>
                <span class="flag company-blog">
                <span class="bubble">CSDN认证企业博客</span>
                </span>
            </div>
            <div class="profile-intro-name-boxFooter">
                <span class="personal-home-page personal-home-years">码龄3年</span>
                    <span class="personal-home-page">
                    <a class="personal-home-certification" href="https://i.csdn.net/#/uc/profile?utm_source=14998968" target="_blank" title="暂无认证">
                    <img src="https://csdnimg.cn/identity/nocErtification.png" alt="">
                    暂无认证
                    </a>
                    </span>
            </div>
        </div>
    </div>
    <div class="data-info d-flex item-tiling">
        <dl class="text-center" title="36">
            <a href="https://blog.csdn.net/weixin_42159233" data-report-click='{"mod":"1598321000_001","spm":"1001.2101.3001.4310"}' data-report-query="t=1">  
                <dt><span class="count">36</span></dt>
                <dd class="font">原创</dd>
            </a>
        </dl>
        <dl class="text-center" data-report-click='{"mod":"1598321000_002","spm":"1001.2101.3001.4311"}' title="46931">
            <a href="https://blog.csdn.net/rank/list/weekly" target="_blank">
                <dt><span class="count">4万+</span></dt>
                <dd class="font">周排名</dd>
            </a>
        </dl>
        <dl class="text-center" title="65796">
            <a href="https://blog.csdn.net/rank/list/total" data-report-click='{"mod":"1598321000_003","spm":"1001.2101.3001.4312"}' target="_blank">
                <dt><span class="count">6万+</span></dt>
                <dd class="font">总排名</dd>
            </a>
        </dl>
        <dl class="text-center" style="min-width:58px" title="99291">  
            <dt><span class="count">9万+</span></dt>
            <dd>访问</dd>
        </dl>
        <dl class="text-center" title="4级,点击查看等级说明">
            <dt><a href="https://blog.csdn.net/blogdevteam/article/details/103478461" target="_blank">
                <img class="level" src="https://csdnimg.cn/identity/blog4.png">
            </a>
            </dt>
            <dd>等级</dd>
        </dl>
    </div>
    <div class="item-rank"></div>
    <div class="data-info d-flex item-tiling">
        <dl class="text-center" title="1404">
            <dt><span class="count">1404</span></dt>
            <dd>积分</dd>
        </dl>
         <dl class="text-center" id="fanBox" title="602">
            <dt><span class="count" id="fan">602</span></dt>
            <dd>粉丝</dd>
        </dl>
        <dl class="text-center" title="165">
            <dt><span class="count">165</span></dt>
            <dd>获赞</dd>
        </dl>
        <dl class="text-center" title="36">
            <dt><span class="count">36</span></dt>
            <dd>评论</dd>
        </dl>
        <dl class="text-center" title="423">
            <dt><span class="count">423</span></dt>
            <dd>收藏</dd>
        </dl>
    </div>
    <div class="profile-intro-name-boxOpration">
        <div class="opt-letter-watch-box">
        <a class="bt-button personal-letter" href="https://im.csdn.net/chat/weixin_42159233" target="_blank" rel="noopener">私信</a>
        </div>
        <div class="opt-letter-watch-box"> 
            <a class="personal-watch bt-button" id="btnAttent" >关注</a>  
        </div>
    </div>
</div>
<div id="asideSearchArticle" class="aside-box">
	<div class="aside-content search-comter">
    <div class="aside-search aside-search-blog">         
        <input type="text" class="input-serch-blog" name="" autocomplete="off" value="" id="search-blog-words" placeholder="搜博主文章">
        <a class="btn-search-blog">
                    <img src="//csdnimg.cn/cdn/content-toolbar/csdn-sou.png?v=1587021042">
        </a>
    </div>
    </div>
</div>


<div id="asideHotArticle" class="aside-box">
	<h3 class="aside-title">热门文章</h3>
	<div class="aside-content">
		<ul class="hotArticle-list">
			<li>
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86529883" target="_blank"  data-report-click='{"mod":"popu_541","spm":"1001.2101.3001.4139","dest":"https://blog.csdn.net/weixin_42159233/article/details/86529883","ab":"new"}'>
				【风变编程】第五课笔记
					<img src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					<span class="read">15475</span>
                </a>
			</li>
			<li>
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86516196" target="_blank"  data-report-click='{"mod":"popu_541","spm":"1001.2101.3001.4139","dest":"https://blog.csdn.net/weixin_42159233/article/details/86516196","ab":"new"}'>
				【风变编程】第三、四课笔记
					<img src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					<span class="read">14427</span>
                </a>
			</li>
			<li>
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86609827" target="_blank"  data-report-click='{"mod":"popu_541","spm":"1001.2101.3001.4139","dest":"https://blog.csdn.net/weixin_42159233/article/details/86609827","ab":"new"}'>
				【风变编程】第八、九课笔记
					<img src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					<span class="read">12311</span>
                </a>
			</li>
			<li>
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86545593" target="_blank"  data-report-click='{"mod":"popu_541","spm":"1001.2101.3001.4139","dest":"https://blog.csdn.net/weixin_42159233/article/details/86545593","ab":"new"}'>
				【风变编程】第七课笔记
					<img src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					<span class="read">12164</span>
                </a>
			</li>
			<li>
				<a href="https://blog.csdn.net/weixin_42159233/article/details/86680847" target="_blank"  data-report-click='{"mod":"popu_541","spm":"1001.2101.3001.4139","dest":"https://blog.csdn.net/weixin_42159233/article/details/86680847","ab":"new"}'>
				【目录】博客分类，方便查找
					<img src="https://csdnimg.cn/release/blogv2/dist/pc/img/readCountWhite.png" alt="">
					<span class="read">9045</span>
                </a>
			</li>
		</ul>
	</div>
</div>
<div id="asideCategory" class="aside-box flexible-box">
    <h3 class="aside-title">分类专栏</h3>
    <div class="aside-content">
        <ul>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10486012.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10486012.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">前端</span>
                    </span>
                    <span class="count float-right">6篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10387053.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10387053.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756916.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">SSM</span>
                    </span>
                    <span class="count float-right">9篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10471431.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10471431.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756927.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">Java</span>
                    </span>
                </a>
            </li>
            <li class="indentation">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10387054.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10387054.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20190927151043371.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">SpringMVC</span>
                    </span>
                    <span class="count float-right">2篇</span>
                </a>
            </li>
            <li class="indentation">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10356932.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10356932.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20190918135101160.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">Spring</span>
                    </span>
                    <span class="count float-right">3篇</span>
                </a>
            </li>
            <li class="indentation">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10372179.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10372179.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20190927151043371.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">MyBatis</span>
                    </span>
                    <span class="count float-right">2篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9885305.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9885305.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756925.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">C语言</span>
                    </span>
                    <span class="count float-right">1篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9851252.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9851252.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">linux</span>
                    </span>
                    <span class="count float-right">4篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9903680.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9903680.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">hadoop</span>
                    </span>
                    <span class="count float-right">5篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8651692.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8651692.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">统计学习方法</span>
                    </span>
                    <span class="count float-right">4篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9695348.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9695348.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756923.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">NLP自然语言处理</span>
                    </span>
                    <span class="count float-right">2篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8617267.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8617267.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756930.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">风变编程</span>
                    </span>
                    <span class="count float-right">5篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8647377.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8647377.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756754.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">杂项</span>
                    </span>
                    <span class="count float-right">3篇</span>
                </a>
            </li>
            <li class="">
                <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8797584.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8797584.html","ab":"new"}'>
                    <img src="https://img-blog.csdnimg.cn/20201014180756925.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                    <span class="title oneline">
                        <span class="text">课程设计</span>
                    </span>
                    <span class="count float-right">2篇</span>
                </a>
            </li>
        </ul>
    </div>
    <p class="text-center">
        <a class="flexible-btn" data-fbox="aside-archive"><img class="look-more" src="https://csdnimg.cn/release/blogv2/dist/pc/img/arrowDownWhite.png" alt=""></a>
    </p>
</div>
<div id="asideNewComments" class="aside-box">
    <h3 class="aside-title">最新评论</h3>
    <div class="aside-content">
        <ul class="newcomment-list">
            <li>
                <a class="title text-truncate" target="_blank" href="https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_15280376" data-report-click='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_15280376","ab":"new"}' data-report-view='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_15280376","ab":"new"}'>【C语言】c语言基础知识梳理（超全）</a>
                <p class="comment ellipsis">
                    <a href="https://blog.csdn.net/qq_52149275" class="user-name" target="_blank">Vale la pena: </a>
                    <span class="code-comments">正在准备c语言补考，很有帮助，太感人了呜哇哇</span>
                </p>
            </li>
            <li>
                <a class="title text-truncate" target="_blank" href="https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14924508" data-report-click='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14924508","ab":"new"}' data-report-view='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14924508","ab":"new"}'>【C语言】c语言基础知识梳理（超全）</a>
                <p class="comment ellipsis">
                    <a href="https://blog.csdn.net/weixin_44434568" class="user-name" target="_blank">fym_me: </a>
                    <span class="code-comments">正在学C，感谢分享！</span>
                </p>
            </li>
            <li>
                <a class="title text-truncate" target="_blank" href="https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14414335" data-report-click='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14414335","ab":"new"}' data-report-view='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105349932#comments_14414335","ab":"new"}'>【C语言】c语言基础知识梳理（超全）</a>
                <p class="comment ellipsis">
                    <a href="https://kaven.blog.csdn.net" class="user-name" target="_blank">ITKaven: </a>
                    <span class="code-comments">很不错分享～进步的路上一起努力！也期待您的点赞支持!</span>
                </p>
            </li>
            <li>
                <a class="title text-truncate" target="_blank" href="https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124030" data-report-click='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124030","ab":"new"}' data-report-view='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124030","ab":"new"}'>【LINUX】Linux使用JDK替换OpenJDK流程</a>
                <p class="comment ellipsis">
                    <a href="https://blog.csdn.net/FiyaZ" class="user-name" target="_blank">天亮又要起床Fiiii: </a>
                    <span class="code-comments">补个贴啊哈哈哈哈哈</span>
                </p>
            </li>
            <li>
                <a class="title text-truncate" target="_blank" href="https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124023" data-report-click='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124023","ab":"new"}' data-report-view='{"mod":"popu_542","spm":"1001.2101.3001.4231","dest":"https://blog.csdn.net/weixin_42159233/article/details/105245017#comments_14124023","ab":"new"}'>【LINUX】Linux使用JDK替换OpenJDK流程</a>
                <p class="comment ellipsis">
                    <a href="https://blog.csdn.net/FiyaZ" class="user-name" target="_blank">天亮又要起床Fiiii: </a>
                    <span class="code-comments">centos下对应8，9步操作是：
[code=plain]
alternatives --install /usr/bin/java java （jdk目录）/bin/java 500  
alternatives --config java 
[/code]</span>
                </p>
            </li>
        </ul>
    </div>
</div>
<div id="asideArchive" class="aside-box" style="display:block!important; width:300px;">
    <h3 class="aside-title">最新文章</h3>
    <div class="aside-content">
        <ul class="inf_list clearfix">
            <li class="clearfix">
            <a href="https://blog.csdn.net/weixin_42159233/article/details/114581411" target="_blank" data-report-click='{"mod":"popu_382","spm":"1001.2101.3001.4136","dest":"https://blog.csdn.net/weixin_42159233/article/details/114581411","ab":"new"}' data-report-view='{"mod":"popu_382","dest":"https://blog.csdn.net/weixin_42159233/article/details/114581411","ab":"new"}'>【杂记】DO、DTO、BO、Query、VO</a>
            </li>
            <li class="clearfix">
            <a href="https://blog.csdn.net/weixin_42159233/article/details/113872942" target="_blank" data-report-click='{"mod":"popu_382","spm":"1001.2101.3001.4136","dest":"https://blog.csdn.net/weixin_42159233/article/details/113872942","ab":"new"}' data-report-view='{"mod":"popu_382","dest":"https://blog.csdn.net/weixin_42159233/article/details/113872942","ab":"new"}'>【React】React学习笔记4（Redux、React-Redux）</a>
            </li>
            <li class="clearfix">
            <a href="https://blog.csdn.net/weixin_42159233/article/details/113818686" target="_blank" data-report-click='{"mod":"popu_382","spm":"1001.2101.3001.4136","dest":"https://blog.csdn.net/weixin_42159233/article/details/113818686","ab":"new"}' data-report-view='{"mod":"popu_382","dest":"https://blog.csdn.net/weixin_42159233/article/details/113818686","ab":"new"}'>【React】React学习笔记3（React路由、Ant Design）</a>
            </li>
        </ul>
        <div class="archive-bar"></div>
        <div class="archive-box">
                <div class="archive-list-item"><a href="https://blog.csdn.net/weixin_42159233/article/month/2021/03" target="_blank" data-report-click='{"mod":"popu_538","spm":"1001.2101.3001.4138","ab":"new","dest":""}'><span class="year">2021年</span><span class="num">5篇</span></a></div>
                <div class="archive-list-item"><a href="https://blog.csdn.net/weixin_42159233/article/month/2020/12" target="_blank" data-report-click='{"mod":"popu_538","spm":"1001.2101.3001.4138","ab":"new","dest":""}'><span class="year">2020年</span><span class="num">24篇</span></a></div>
                <div class="archive-list-item"><a href="https://blog.csdn.net/weixin_42159233/article/month/2019/05" target="_blank" data-report-click='{"mod":"popu_538","spm":"1001.2101.3001.4138","ab":"new","dest":""}'><span class="year">2019年</span><span class="num">12篇</span></a></div>
        </div>
    </div>
</div>
	<div id="footerRightAds" class="isShowFooterAds">
		<div class="aside-box">
			<div id="kp_box_57" data-pid="57"><iframe  src="https://kunpeng-sc.csdnimg.cn/?timestamp=1623163941/#/preview/7165?positionId=57&queryWord=&spm=1001.2101.3001.5001" frameborder="0" width= "300px"  height= "600px" scrolling="no" ></iframe><img class="pre-img-lasy"  data-src="https://kunyu.csdn.net/1.png?p=57&a=3910&c=7165&k=&spm=1001.2101.3001.5001&d=1&t=3&u=d72947c887264253a6316536fa519e1a" style="display: block;width: 0px;height: 0px;"></div>
		</div>
	</div>
    <!-- 详情页显示目录 -->
<!--文章目录-->
<div id="asidedirectory" class="aside-box">
    <div class='groupfile' id="directory">
        <h3 class="aside-title">目录</h3>
        <div class="align-items-stretch group_item">
            <div class="pos-box">
            <div class="scroll-box">
                <div class="toc-box"></div>
            </div>
            </div>
        </div>
    </div>
</div>
</aside>
<script>
	$("a.flexible-btn").click(function(){
		$(this).parents('div.aside-box').removeClass('flexible-box');
		$(this).parents("p.text-center").remove();
	})
</script>
<script type="text/javascript"  src="https://g.csdnimg.cn/user-tooltip/2.4/user-tooltip.js"></script>
<script type="text/javascript"  src="https://g.csdnimg.cn/user-medal/1.0.6/user-medal.js"></script>    </div>
<div class="recommend-right  align-items-stretch clearfix" id="rightAside" data-type="recommend">
    <aside class="recommend-right_aside">
        <div id="recommend-right" >
                        <div class='flex-column aside-box groupfile' id="groupfile">
                <div class="groupfile-div">
                <h3 class="aside-title">目录</h3>
                <div class="align-items-stretch group_item">
                    <div class="pos-box">
                        <div class="scroll-box">
                            <div class="toc-box"></div>
                        </div>
                    </div>
                </div>
                </div>
            </div>
                <div id="recommendAdBox">
                    <div id="kp_box_479" data-pid="479"><iframe  src="https://kunpeng-sc.csdnimg.cn/?timestamp=1623163941/#/preview/7165?positionId=479&queryWord=&spm=1001.2101.3001.4834" frameborder="0" width= "300px"  height= "600px" scrolling="no" ></iframe><img class="pre-img-lasy"  data-src="https://kunyu.csdn.net/1.png?p=479&a=3910&c=7165&k=&spm=1001.2101.3001.4834&d=1&t=3&u=85a8444213984b88a40a81847111fc49" style="display: block;width: 0px;height: 0px;"></div>
                </div>
            <div class='aside-box kind_person d-flex flex-column'>
                    <h3 class="aside-title">分类专栏</h3>
                    <div class="align-items-stretch kindof_item" id="kind_person_column">
                        <div class="aside-content">
                            <ul>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10486012.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10486012.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">前端</span>
                                        </span>
                                        <span class="count float-right">6篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10387053.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10387053.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756916.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">SSM</span>
                                        </span>
                                        <span class="count float-right">9篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10471431.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10471431.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756927.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">Java</span>
                                        </span>
                                    </a>
                                </li>
                                <li class="indentation">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10387054.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10387054.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20190927151043371.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">SpringMVC</span>
                                        </span>
                                        <span class="count float-right">2篇</span>
                                    </a>
                                </li>
                                <li class="indentation">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10356932.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10356932.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20190918135101160.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">Spring</span>
                                        </span>
                                        <span class="count float-right">3篇</span>
                                    </a>
                                </li>
                                <li class="indentation">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_10372179.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_10372179.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20190927151043371.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">MyBatis</span>
                                        </span>
                                        <span class="count float-right">2篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9885305.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9885305.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756925.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">C语言</span>
                                        </span>
                                        <span class="count float-right">1篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9851252.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9851252.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">linux</span>
                                        </span>
                                        <span class="count float-right">4篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9903680.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9903680.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">hadoop</span>
                                        </span>
                                        <span class="count float-right">5篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8651692.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8651692.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756919.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">统计学习方法</span>
                                        </span>
                                        <span class="count float-right">4篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_9695348.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_9695348.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756923.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">NLP自然语言处理</span>
                                        </span>
                                        <span class="count float-right">2篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8617267.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8617267.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756930.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">风变编程</span>
                                        </span>
                                        <span class="count float-right">5篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8647377.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8647377.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756754.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">杂项</span>
                                        </span>
                                        <span class="count float-right">3篇</span>
                                    </a>
                                </li>
                                <li class="">
                                    <a class="clearfix" target="_blank" href="https://blog.csdn.net/weixin_42159233/category_8797584.html" data-report-click='{"mod":"popu_537","spm":"1001.2101.3001.4137","strategy":"pc付费专栏左侧入口","dest":"https://blog.csdn.net/weixin_42159233/category_8797584.html","ab":"new"}'>
                                        <img src="https://img-blog.csdnimg.cn/20201014180756925.png?x-oss-process=image/resize,m_fixed,h_64,w_64" alt="" onerror="this.src='https://img-blog.csdnimg.cn/20201014180756922.png?x-oss-process=image/resize,m_fixed,h_64,w_64'">
                                        <span class="title oneline">
                                            <span class="text">课程设计</span>
                                        </span>
                                        <span class="count float-right">2篇</span>
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
            </div>
        </div>
    </aside>
</div>

</div>
<div class="mask-dark"></div>
<script>
    var articleId = 86529883;
    var commentscount = 4;
    var curentUrl = "https://blog.csdn.net/weixin_42159233/article/details/86529883";
    var myUrl = "https://my.csdn.net/";
    var highlight = ["风变","编程","第五课","笔记"];//高亮数组
    var isRecommendModule = true;
    var isBaiduPre = true;
    var baiduCount = 3;
    var share_card_url = "https://blog.csdn.net/weixin_42159233/article/shareArticleCardPage?article_id=86529883"
	var articleType = 2;
    var baiduKey = "风变编程python第五关答案";
    var needInsertBaidu = true;
    var recommendRegularDomainArr = ["blog.csdn.net/.+/article/details/","download.csdn.net/download/","edu.csdn.net/course/detail/","ask.csdn.net/questions/","bbs.csdn.net/topics/","www.csdn.net/gather_.+/"]
    var codeStyle = "";
    var baiduSearchType = "utm_term";
    var canRead = true;
    var blogMoveHomeArticle = false;
    var showPcWindowAd = false;
    var showSearchText = "";
    var linkPage = true;
    var articleSource = 1;
    var articleReport = '{"pid": "blog", "spm":"1001.2101"}';
</script>
<script src="https://csdnimg.cn/public/sandalstrap/1.4/js/sandalstrap.min.js"></script>
<div class="skin-boxshadow"></div>
<div style="display:none;">
	<img src="" onerror='setTimeout(function(){if(!/(csdn.net|iteye.com|baiducontent.com|googleusercontent.com|360webcache.com|sogoucdn.com|bingj.com|baidu.com)$/.test(window.location.hostname)){window.location.href="\x68\x74\x74\x70\x73\x3a\x2f\x2f\x77\x77\x77\x2e\x63\x73\x64\x6e\x2e\x6e\x65\x74"}},3000);'>
</div>
</body>
<script src="https://csdnimg.cn/release/blogv2/dist/components/js/pc_wap_highlight-db1e81323a.min.js" type="text/javascript"></script>
<script src="https://csdnimg.cn/release/blogv2/dist/components/js/pc_wap_common-906586e915.min.js" type="text/javascript"></script>
<link rel="stylesheet" href="https://csdnimg.cn/release/blog_editor_html/release1.6.12/ckeditor/plugins/codesnippet/lib/highlight/styles/atom-one-light.css">
<script>
 // 全局声明
 if (window.csdn === undefined) {
      window.csdn = {};
    }
    window.csdn.sideToolbar = {
        options: {
            report:{
                isShow: true,
            },
            qr: {
                isShow: false,
            },
            guide: {
                isShow: true
            }
        }
    }
    $(function(){
        $(document).on('click',"a.option-box[data-type='report']",function() {
            window.csdn.userLogin.loadAjax(function(res){
                showReport(false,articleTitles);
            })
        });
    })
</script>
    <script src="https://g.csdnimg.cn/baidu-search/1.0.9/baidu-search.js"  type="text/javascript"></script>
<script src="https://csdnimg.cn/release/download/old_static/js/qrcode.js"></script>
<script src="https://csdnimg.cn/release/blogv2/dist/pc/js/common-b286f966c8.min.js" type="text/javascript"></script>
<script src="https://csdnimg.cn/release/blogv2/dist/pc/js/detail-0c65cbe223.min.js" type="text/javascript"></script>
<script src="https://g.csdnimg.cn/user-ordercart/1.0.6/user-ordercart.js" type="text/javascript"></script>
<script src="https://csdnimg.cn/release/blogv2/dist/pc/js/column-78261cfea6.min.js" type="text/javascript"></script>
<script src="https://g.csdnimg.cn/side-toolbar/3.0/side-toolbar.js" type="text/javascript"></script>
<script src="https://g.csdnimg.cn/copyright/1.0.3/copyright.js" type="text/javascript"></script>
<script>
    $(".MathJax").remove();
    if ($('div.markdown_views pre.prettyprint code.hljs').length > 0) {
        $('div.markdown_views')[0].className = 'markdown_views';
    }
</script>
<script type="text/javascript" src="https://csdnimg.cn/release/blog_mathjax/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
            "HTML-CSS": {
                    linebreaks: { automatic: true, width: "94%container" },
                    imageFont: null
            },
            tex2jax: {
                preview: "none"
            },
            mml2jax: {
                preview: 'none'
            }
    });
</script>
<script type="text/javascript" crossorigin src="https://g.csdnimg.cn/user-login/2.3.2/user-login.js"></script>
<script type="text/javascript" crossorigin src="https://g.csdnimg.cn/login-box/1.1.4/login-box.js"></script></html>
