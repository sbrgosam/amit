
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head><script async='async' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
<ins class='adsbygoogle' data-ad-client='ca-pub-4974651546853754' data-ad-slot='1491889926' style='display:inline-block;width:336px;height:280px'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>

    
    <script async='async' data-ad-client='ca-pub-4974651546853754' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
    
    <!--[if IE]><script type="text/javascript" src="https://www.blogger.com/static/v1/jsbin/3382421118-ieretrofit.js"></script>
<![endif]-->
    <meta charset='utf-8'/>
    <meta content='IE=edge' http-equiv='X-UA-Compatible'/>
    <meta content='width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0' name='viewport'/>
    <link href='//fonts.googleapis.com/css?family=Montserrat:400,700|Arimo:400,400i,700' rel='stylesheet' type='text/css'/>
    <link href='//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css' rel='stylesheet'/>
    <b:include data='blog' name='all-head-content'/>
    <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
    <title>
		<b:if cond='data:blog.pageType == &quot;index&quot;'>
			<data:blog.pageTitle/>
		<b:else/>
			<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
				<data:blog.pageName/> - <data:blog.title/>
			<b:else/>
				ERROR 404 - <data:blog.title/> 
			</b:if>
		</b:if>
    </title>
    <!-- Description and Keywords (start) -->
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <meta content='YOUR DESCRIPTION HERE' name='description'/>
    </b:if>
    <meta content='YOUR KEYWORDS HERE' name='keywords'/>
    <!-- Description and Keywords (end) -->
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <meta expr:content='data:blog.pageName' property='og:title'/>
        <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
        <meta content='article' property='og:type'/>
    </b:if>
    <b:if cond='data:blog.postImageUrl'>
        <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <b:else/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
    </b:if></b:if>
    <b:if cond='data:blog.metaDescription != &quot;&quot;'>
        <meta expr:content='data:blog.metaDescription' name='og:description'/>
    </b:if>
    <meta expr:content='data:blog.title' property='og:site_name'/>
    <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.postImageUrl'>
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
    <b:else/>
      <meta content='summary' name='twitter:card'/>
      <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/> 
      </b:if>
    </b:if>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.metaDescription'>
      <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
    </b:if>
    <!-- Social Media meta tag need customer customization -->
    <meta content='Facebook App ID here' property='fb:app_id'/> 
    <meta content='Facebook Admin ID here' property='fb:admins'/> 
    <meta content='@username' name='twitter:site'/>
    <meta content='@username' name='twitter:creator'/>   

    <script type='text/javascript'>
      var blog = document.location.hostname.split(&quot;.&quot;);
      if (window.location.href.indexOf(&quot;.blogspot&quot;) &gt; -1) {
          if (blog[blog.length - 1] != &quot;com&quot;) {
              var ncr = &quot;http://&quot; + blog[0] + &quot;.blogspot.com/ncr&quot;;
              window.location.replace(ncr + document.location.pathname);
          }
      }
    </script> 

<b:skin><![CDATA[/
-----------------------------------------------
Blogger Template Style
Name:        Sora Front
Author :     http://www.soratemplates.com
License:     Premium Version
----------------------------------------------- */

/* Variable definitions
-----------------------
<Variable name="keycolor" description="Main Color" type="color" default="#1e87f0" value="#1e87f0"/>
<Variable name="body.background" description="Background" type="background" color="#999" default="$(color) url() repeat scroll top left" value="$(color) url() repeat scroll top left"/>
<Variable name="color.menu" description="Menu Background Color" type="color" default="#2A5A8E" value="#D52C1F"/>
<Variable name="color.theme" description="Color Theme" type="color" default="#2A5A8E" value="#D52C1F"/>
-----------------------
*/
a,abbr,acronym,address,applet,b,big,blockquote,body,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,h1,h2,h3,h4,h5,h6,html,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{
    padding:0;
    border:0;
    outline:0;
    vertical-align:baseline;
    background:0 0;
    margin:0
}
 ins{
    text-decoration:underline
}
 del{
    text-decoration:line-through
}
 dl,ul{
    list-style-position:inside;
    font-weight:700;
    list-style:none;
}
 ul li{
    list-style:none
}
 caption,th{
    text-align:center
}
 img{
    border:none;
    position:relative
}
 .clear{
    clear:both
}
 .section,.widget,.widget ul{
    margin:0;
    padding:0
}
 body{
    background:$(body.background);
    color:#010101;
    font-size:14px;
    font-family:'Montserrat',sans-serif;
    line-height:22px;
    word-wrap:break-word
}
 h1,h2,h3,h4,h5,h6{
    padding:0;
    margin:0
}
 h2{
    color:#010101;
    margin:1.5em 0 .75em
}
 h4 a{
    color:#4285f4!important
}
 a:link,a:hover,a:visited{
    color:$(color.theme);
    text-decoration:none
}
 :focus{
    outline:0
}
 a img{
    border:0
}
 brc{
    color:#bdbdbd
}
 select{
    -webkit-appearance:none!important;
    -moz-appearance:none!important;
    appearance:none!important
}
 .separator a{
    clear:none!important;
    float:none!important;
    margin-left:0!important;
    margin-right:0!important
}
 #navbar-iframe{
    display:none;
    height:0;
    visibility:hidden
}
 span.item-control,a.quickedit{
    display:none!important
}
 .archive .home-link,.index .home-link,.home-link{
    display:none!important
}
 *{
    outline:0;
    transition:all .3s ease;
    -webkit-transition:all .3s ease;
    -moz-transition:all .3s ease;
    -o-transition:all .3s ease
}
 #outer-wrapper{
    max-width:1113px;
    margin:0 auto;
    background-color:#FFF;
border:1px solid #010101;
border-width:0px 1px;
}
 .row{
    width:1073px
}
 #topnav{
    width:100%;
    height:30px;
    background-color:#010101;
    margin:0
}
 .tm-head{
    margin:0 auto;
    height:30px;
    line-height:30px;
    overflow:hidden
}
 .tm-menu{
    float:left
}
#menu .widget {
    display: none;
}
 #nav1 li{
    float:left;
    display:inline-block;
    line-height:30px;
    padding:0
}
 #nav1 li a{
    color:#fff;
    font-size:12px;
    font-weight:400
}
 #nav1 li a:hover,.tn-head #social-top ul li a:hover{
    color:$(color.theme)
}
 #nav1 li+li:before{
    content:"|";
    padding:0 7px;
    color:#ddd;
    font-weight:100
}
 .social-area{
    float:right
}
 .tm-head #social-top{
    position:relative;
    display:block;
    margin-right:0
}
 .tm-head #social-top ul{
    overflow:hidden
}
 .tm-head #social-top ul li{
    line-height:32px;
    display:block;
    float:left;
    margin-left:20px;
    padding:0
}
 .tm-head #social-top ul li a{
    display:block;
    float:left;
    color:#fff;
    text-decoration:none;
    font-size:13px
}
 .tm-head #social-top ul li a:before{
    display:inline-block;
    font-family:FontAwesome;
    font-style:normal;
    font-weight:400;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale
}
 .tm-head #social-top ul li a:hover{
    color:$(color.theme)
}
 #social-top .facebook:before{
    content:"\f230"
}
 #social-top .twitter:before{
    content:"\f099"
}
 #social-top .gplus:before{
    content:"\f0d5"
}
 #social-top .rss:before{
    content:"\f09e"
}
 #social-top .youtube:before{
    content:"\f167"
}
 #social-top .skype:before{
    content:"\f17e"
}
 #social-top .stumbleupon:before{
    content:"\f1a4"
}
 #social-top .tumblr:before{
    content:"\f173"
}
 #social-top .vine:before{
    content:"\f1ca"
}
 #social-top .stack-overflow:before{
    content:"\f16c"
}
 #social-top .linkedin:before{
    content:"\f0e1"
}
 #social-top .dribbble:before{
    content:"\f17d"
}
 #social-top .soundcloud:before{
    content:"\f1be"
}
 #social-top .behance:before{
    content:"\f1b4"
}
 #social-top .digg:before{
    content:"\f1a6"
}
 #social-top .instagram:before{
    content:"\f16d"
}
 #social-top .pinterest:before{
    content:"\f0d2"
}
 #social-top .delicious:before{
    content:"\f1a5"
}
 #social-top .codepen:before{
    content:"\f1cb"
}
 #header-blog{
    height:130px;
    background-color:#fff;
    position:relative;
    overflow:hidden
}
 .header-content{
    margin:0 auto;
    overflow:hidden;
    height:130px
}
 .header-logo{
    max-width:300px;
    height:auto;
    float:left
}
 .header-logo img{
    height:auto;
    margin:34px 0 0;
    max-width:100%
}
 .Header h1{
    color:#010101;
    margin-bottom:10px;
    margin-top:40px
}
 .header-ads{
    width:729px;
    max-width:100%;
    max-height:90px;
    float:right;
    margin:15px 0 0
}
 #header-navigation{
    margin:0 auto;
    top:0;
    height:40px;
background:$(color.menu);
}
 .nav-wrapper{
    margin:0 auto;
    box-sizing:border-box;
    min-height:40px
}
 .header-menu li.home-child{
    float:left;
    height:40px;
    display:inline-block;
    padding:0
}
 .header-menu li.home-child a{
    height:40px;
    line-height:40px;
    font-size:13px;
    font-weight:700;
    color:#FFF;
    text-transform:uppercase;
    padding:12px
}
 #menu ul li{
    float:left;
    height:40px;
    display:inline-block;
    padding:0;
    margin-right:1px;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 #menu ul li:hover a{
    color:#FFF
}
 #menu ul li a{
    height:40px;
    line-height:40px;
    padding:12px;
    font-size:13px;
    text-transform:uppercase;
    font-weight:700;
    color:#E4E4E4;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 #menu ul li.hasSub a{
    padding-right:22px
}
 #menu ul li.hasSub a:after{
    color:#fff;
    margin-left:3px;
    margin-top:1px;
    position:absolute;
    display:inline-block;
    content:'\f107';
    font-family:FontAwesome;
    font-weight:400;
    font-size:15px;
    text-rendering:auto;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 #menu ul li.hasSub ul li a:after{
    display:none!important
}
 #menu ul li:hover ul, #menu ul li ul li:hover ul{
    left:auto;
    z-index:9999
}
 #menu ul li ul{
    position:absolute;
    left:-9999px;
    z-index:9999;
    width:170px;
    margin:0;
    padding:0
}
 #menu ul li ul li ul {
    display:none;
     transition: all 0 ease!important;
     -webkit-transition: all 0 ease!important;
     -moz-transition: all 0 ease!important;
     -o-transition: all 0 ease!important;
}
 #menu ul li ul li:hover ul {
     left: 170px;
     top: 0;
     display:block;
}
 #menu ul li ul li{
    background-color:#010101;
    float:none!important;
    display:block;
    padding:0;
    margin-right:0;
    height:auto
}
 #menu ul li ul li:hover{
    background-color:#212121
}
 #menu ul li ul#sub-menu li a{
    padding:10px;
    font-size:11px;
    line-height:36px;
    text-transform:uppercase;
    text-decoration:none;
    color:#E4E4E4!important;
    font-weight:700;
    height:auto
}
 #menu ul li ul#sub-menu li:hover a{
    color:#FFF!important
}
 #menu ul li,#menu ul li ul{
    outline:0;
    transition:all 0 ease!important;
    -webkit-transition:all 0 ease!important;
    -moz-transition:all 0 ease!important;
    -o-transition:all 0 ease!important
}
 .selectnav{
    display:none
}
 #selectnav1{
    background:#212121 url(http://4.bp.blogspot.com/-XmVTbf5RQLY/VmT4NfoMGOI/AAAAAAAACSI/F2sRS-yCpPI/s1600-r/menu.png) no-repeat right top;
    margin-top:0
}
 select.selectnav option:fist-child{
    text-transform:uppercase
}
 select.selectnav{
    color:#E4E4E4;
    padding:0 5px 0 10px;
    border:0;
    font:14px Montserrat, sans-serif;
    cursor:pointer;
    width:100%;
    height:40px;
    line-height:40px;
    border-radius:0
}
 .header-search{
    position:relative;
    float:right
}
 .header-search li{
    list-style:none
}
 .header-search a.search{
    -webkit-transition:all .3s ease-out 0;
    -moz-transition:all .3s ease-out 0;
    transition:all .3s ease-out 0;
    cursor:pointer;
    display:block;
    height:40px;
    text-align:center;
    position:relative;
    right:0;
    top:0;
    width:40px;
    border-radius:0
}
 .header-search a.search:hover{
    background-color:$(color.theme)
}
 .header-search a.search:before{
    color:#E4E4E4;
    content:'\f002';
    font:normal normal normal 22px/1 FontAwesome;
    font-size:inherit;
    text-rendering:auto;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    line-height:40px
}
 .header-search a.active:before,.header-search a.search:hover:before{
    color:#FFF
}
 .header-search a.search.active{
    background-color:$(color.theme);
    border-left:0;
    border-radius:0
}
 .header-search a.search.active form{
    display:block
}
 .header-search a.search form{
    display:none;
    position:absolute;
    right:40px;
    top:0;
    z-index:2
}
 .header-search a.search form input{
    box-shadow:none;
    height:40px;
    padding:0 12px;
    width:160px;
    background-color:#212121;
    font-family:'Montserrat', sans-serif;
    color:#fff;
    margin-top:0;
    border-radius:0;
    border:0;
    line-height:40px
}
 #header-navigation .header-search li a{
    cursor:pointer;
    -webkit-transition:all .3s ease-out 0;
    -moz-transition:all .3s ease-out 0;
    transition:all .3s ease-out 0
}
 #content-wrapper{
    margin:25px auto 5px;
background:#fff;
}
 #main-wrapper{
    float:left;
    margin-right:25px;
    width:728px;
    word-wrap:break-word;
background:#fff;
}
 .m-rec{
    margin-bottom:0;
    padding-bottom:3px
}
 .m-rec h2{
    display:inline-block
}
 .m-rec h2 a{
    color:#CBCBCB;
    font-weight:700;
    line-height:normal;
    font-size:13px;
    text-transform:uppercase;
    display:block
}
 #ads-blog{
    display:none
}
 .home #ads-blog{
    display:block
}
 .home-ad .widget{
    width:728px;
    max-height:90px;
    padding:5px 0 20px;
    margin:0 auto
}
 .ads-posting .home-ad .widget{
    width:728px;
    max-height:90px;
    margin:0 auto;
    padding:20px 0 5px
}
#feat-layout {
    padding: 15px;
    border: 1px solid #555;
    border-top: 6px solid #2A5A8E;
    box-shadow: 0 0 2px #333;
    margin: 0 0 10px;
    box-sizing: border-box;
}
 .feat-layout .feat-title h2.title{
    font-size:13px;
    font-weight:500;
    display:inline-block
}
 .feat-title{
    margin:0
}
 .feat-title h2{
    padding:0 0 10px;
    display:inline-block
}
 .feat-title h2 a{
    color:#CBCBCB;
    font-weight:700;
    line-height:normal;
    font-size:13px;
    text-transform:uppercase;
    display:block
}
 .p-date{
    color:#bdbdbd;
    font-weight:400;
    font-size:12px
}
 .p-date:before{
    content:'\f133';
    font-family:fontawesome;
    color:#bdbdbd
}
 .p-author:before{
    content:'\f007';
    font-family:fontawesome;
    color:#bdbdbd
}
 .p-author{
    color:#bdbdbd;
    font-weight:400;
    font-size:12px
}
 .feat .primeiro-thumb,.feat .mag-thumb,.carousel.recent-block .mag-thumb{
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .feat .primeiro-thumb:hover,.feat .mag-thumb:hover{
    -webkit-transform:scale(1.1)important;
    -moz-transform:scale(1.1)!important;
    transform:scale(1.1)!important;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .feat .primeiro .feat-thumb{
    width:55%;
    height:250px;
    float: left;
margin-right:15px;
}
 .feat .primeiro-thumb{
    width:100%;
    height:250px;
    display:block
}
 .feat .primeiro{
    overflow:hidden
}
 .feat-thumb{
    overflow:hidden
}
 .feat1 ul{
    overflow:hidden
}
 .feat ul li .feat-thumb{
    width:100%;
    height:150px;
    margin-bottom:10px
}
 .feat ul li .mag-thumb{
    width:100%;
    height:150px;
    display:block
}
 .feat ul li .mag-content{
    display:block
}
 .feat .feat-headline a{
    font-weight:700;
    color:#010101;
    display:inline-block
}
 .feat ul li .mag-content .feat-headline a{
    font-size:16px;
    padding:6px 5px 0 0;
    line-height:1.33;
    font-weight:400;
    letter-spacing:-0.6px
}
 .feat .primeiro-content .feat-headline a{
    font-size:22px;
    line-height:1.33em;
    letter-spacing:-0.6px
}
 .feat .recent-des{
    margin:10px 0px 0px;
    color:#919191;
    font-size:13.3px;
    line-height:1.65;
    font-weight:400
}
 .feat1{
    padding-bottom:20px
}
 .feat1 .primeiro{
    width: 100%;
    clear:both;
    margin-bottom:15px;
}
 .feat1 .primeiro .feat-thumb{
    display:block
}
 .feat1 .primeiro-thumb{
    display:block
}
 .feat1 .primeiro-content{
  overflow:hidden;
    display:block
}
 .feat1 ul li{
   display: block;
    float: left;
    width: 50%;
    padding-right: 5px;
    height: auto;
    box-sizing: border-box;
}
 .feat1 ul li:last-child{
   padding-right: 0;
    padding-left: 5px;
}
 .feat-headline a:hover{
    color:$(color.theme)
}
 .p-date:before{
    margin-right:5px
}
 .p-author:before{
    margin-right:5px
}
 .p-date{
    margin-left:10px
}
 .feat1 .primeiro-content .feat-headline {
    padding:10px 0
}
 .feat-layout .widget-content,.feat-layout h2.title{
    display:none
}
 .label,.search-query{
    padding:0 0 6px
}
 .label span,.search-query span{
    color:#CBCBCB;
    font-weight:700;
    line-height:normal;
    font-size:13px;
    text-transform:uppercase;
    display:inline-block
}
 .post{
    display:block;
    overflow:hidden;
    word-wrap:break-word;
font-family: 'Arimo', sans-serif;
}
 .index .post,.archive .post{
    padding:15px;
 border: 1px solid #555;
border-top: 6px solid #2A5A8E;
    box-shadow: 0 0 2px #333;
    margin: 0 0 10px;
box-sizing: border-box;
}
 
 .block-image{
    float:left;
    width:270px;
    height:168px;
    margin-right:20px
}
 .block-image .thumb{
    width:100%;
    height:168px;
    position:relative;
    display:block;
    z-index:2;
    overflow:hidden
}
 .block-image a{
    width:100%;
    height:168px;
    display:block;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .block-image a:hover{
    -webkit-transform:scale(1.1)!important;
    -moz-transform:scale(1.1)!important;
    transform:scale(1.1)!important;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
#meta-post {
    margin: 0 0 10px;
}
 .retitle h2{
    margin:8px 0;
    display:block
}
 .post h2 a,.post h2 a:visited,.post h2 strong{
    color:#010101;
    font-weight:700;
    text-decoration:none;
    font-size:24px;
    line-height:1.33em;
    letter-spacing:-0.6px
}
 .post h2 a:hover{
    color:$(color.theme)
}
 .post_author_date{
    color:#C4C4C4;
    font-size:13px;
    font-weight:400;
    line-height:23px;
    margin:0 0 25px;
    text-transform:uppercase
}
 .post_author{
    font-weight:600;
    margin-right:5px
}
 div.post_author_date a{
    text-decoration:none
}
 .resumo{
    color:#303030;
    font-size:14px;
   line-height: 1.55;
}
 .resumo span{
    display:block;
    margin-bottom:8px
}
 .widget iframe,.widget img{
    max-width:100%
}
 .index .post-footer,.archive .post-footer{
    display:none!important
}
 .index .post h2,.archive .post h2{
    margin:0 0 10px;
    padding:0
}
 .item .post,.static_page .post{
    padding:0 0 25px
}
 .date-header{
    color:#bdbdbd;
    display:block;
    overflow:hidden;
    font-size:12px;
    font-weight:400;
    line-height:1.3em;
    margin:0!important;
    padding:0
}
 .date-header a{
    color:#bdbdbd
}
 #meta-post .fa-calendar-o{
    margin-left:8px
}
 .post-meta{
    color:#bdbdbd;
    display:block;
    font-size:13px;
    font-weight:400;
    line-height:21px;
    margin:0;
    padding:0
}
 .hreview{
    display:none!important
}
 .postags{
    position:absolute;
    top:5px
}
 .postags a{
    padding:5px;
    display:inline-block;
    background:#FFC000;
    margin:0;
    color:#fff
}
 .postags a:nth-child(2){
    background-color:#444
}
 .postags a{
    display:none
}
 .postags a:first-child,.postags a:nth-child(2){
    display:inline-block
}
 .postags a:hover{
    background:#aaa
}
 .breadcrumbs .fa-angle-right:before{
    margin:0 5px
}
 .breadcrumbs{
    margin:0;
    font-size:13px
}
 .breadcrumbs span a.bhome{
    color:$(color.theme)
}
 .breadcrumbs span,.breadcrumbs span a{
    color:#010101
}
 .breadcrumbs span a:hover{
    color:$(color.theme)
}
 .item article{
    margin-top:20px
}
 .item .post-head,.static_page .post-head{
    margin:15px 0 5px;
    position:relative
}
 .item .post-title,.static_page .post-title{
    color:#010101;
    display:inline-block;
    padding-bottom:5px;
    font-size:31px;
    line-height:1.33;
    font-weight:700;
    position:relative
}
 .item .post-body,.static_page .post-body{
    width:100%;
    color:#5E5E5E;
    font-size:15px;
    line-height:1.5em;
    overflow:hidden;
    box-sizing:border-box;
}
 .item .post-outer{
    padding:0
}
 .item .post-body img{
    max-width:100%
}
 .post-meta a,.post-meta i{
    color:#CBCBCB
}
 .post-timestamp{
    margin-left:5px
}
 .label-head{
    margin-left:5px
}
 .label-head a{
    padding-left:2px
}
 .label-head a:hover{
    color:$(color.theme)
}
 .main .widget{
    margin:0
}
 .main .Blog{
    border-bottom-width:0
}
 #ads-post10{
    display:none
}
 .ads-post .widget{
    width:728px;
    max-height:90px;
    margin:0 auto 25px
}
 .share-box{
    margin:20px 0 25px;
    border-bottom:3px solid #EEE;
    position:relative
}
 .share-title{
    color:#010101;
    display:inline-block;
    padding-bottom:10px;
    font-size:13px;
    font-weight:700;
    position:relative;
    top:5px;
    text-transform:uppercase
}
 .share-art{
    float:right;
    padding:0;
    padding-top:0;
    font-size:13px;
    font-weight:400;
    text-transform:capitalize
}
 .share-art a{
    color:#fff;
    padding:3px 8px;
    margin-left:4px;
    border-radius:2px;
    display:inline-block;
    margin-right:0
}
 .share-art a:hover{
    color:#fff
}
 .share-art .fac-art{
    background:#3b5998
}
 .share-art .fac-art:hover{
    background:rgba(49,77,145,0.7)
}
 .share-art .twi-art{
    background:#00acee
}
 .share-art .twi-art:hover{
    background:rgba(7,190,237,0.7)
}
 .share-art .goo-art{
    background:#db4a39
}
 .share-art .goo-art:hover{
    background:rgba(221,75,56,0.7)
}
 .share-art .pin-art{
    background:#CA2127
}
 .share-art .pin-art:hover{
    background:rgba(202,33,39,0.7)
}
 .share-art .lin-art{
    background:#0077B5
}
 .share-art .lin-art:hover{
    background:rgba(0,119,181,0.7)
}
.share-art .wat-art{background:#25d266;display:none;}
.share-art .wat-art:hover{background:rgba(37, 210, 102, 0.73)}
@media only screen and (max-width: 768px) {
.share-art .wat-art{display:inline-block;}
}
.index .post .share-box, .archive .post .share-box {
padding:0;
margin-top:8px;
}
 #related-posts{
    margin-bottom:10px
}
 .related li{
    width:30.835%;
    display:inline-block;
    height:auto;
    min-height:184px;
    float:left;
    margin-right:24px;
    overflow:hidden;
    position:relative
}
 .related-thumb{
    width:100%;
    height:120px;
    overflow:hidden
}
 .related li .related-img{
    width:100%;
    height:120px;
    display:block;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .related li .related-img:hover{
    -webkit-transform:scale(1.1)!important;
    -moz-transform:scale(1.1)!important;
    transform:scale(1.1)!important;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .related-title a{
    font-size:14px;
    line-height:1.33em;
    padding:10px 5px 10px 0;
    font-weight:400;
    color:#010101;
    display:block
}
 .related-title a:hover{
    color:$(color.theme)
}
 .related li:nth-of-type(3),.related li:nth-of-type(6),.related li:nth-of-type(9){
    margin-right:0
}
 .static_page .post-meta,.static_page .old_new{
    display:none
}
 .error_page #main-wrapper{
    width:100%!important;
    margin:0!important
}
 #errr{
    margin:60px auto;
    text-align:center;
    padding:0;
    line-height:4em
}
 .error_page a.homepage{
    padding:10px 20px;
    color:#fff;
    background-color:#010101;
    border-radius:2px
}
 .error_page a.homepage:hover{
    background-color:$(color.theme)
}
 #errr .error{
    font-size:20px;
    text-align:center;
    font-weight:700
}
 #errr .nerrr{
    font-size:150px;
    text-align:center;
    color:$(color.theme);
    font-weight:700
}
 #errr .nerrr span.fa{
    font-size:135px;
    margin:0 10px;
    color:#010101;
    font-weight:700
}
 #errr .fa-frown-o:before{
    content:&quot
}
 .error_page .sidebar-wrapper,.error_page .old_new{
    display:none
}
 @media only screen and (max-width: 768px) {
     #errr{
        margin:50px auto 50px
    }
     #errr p{
        line-height:2.5em
    }
}
 @media only screen and (max-width: 359px) {
     #errr .nerrr{
        font-size:100px
    }
     #errr .nerrr span.fa {
        font-size:75px
    }
}
 @media only screen and (max-width: 319px) {
     #errr .nerrr{
        font-size:80px
    }
     #errr span.fa.fa-frown-o{
        font-size:65px
    }
     #errr p{
        line-height:2.5em
    }
}
 .firstcharacter{
    float:left;
    color:$(color.theme);
    font-size:75px;
    line-height:60px;
    padding-top:4px;
    padding-right:8px;
    padding-left:3px
}
 .post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{
    margin-bottom:15px;
    color:#010101
}
 blockquote{
    font-style:italic;
    color:#999;
    border-left:5px solid $(color.theme);
    margin-left:0;
    padding:10px 15px
}
 blockquote:before{
    content:'\f10d';
    display:inline-block;
    font-family:FontAwesome;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    margin-right:10px;
    color:#999
}
 blockquote:after{
    content:'\f10e';
    display:inline-block;
    font-family:FontAwesome;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    margin-left:10px;
    color:#999
}
 .widget .post-body ul,.widget .post-body ol{
    line-height:1.5;
    font-weight:400
}
 .widget .post-body li{
    margin:5px 0;
    padding:0;
    line-height:1.5
}
 .post-body ul li:before{
    content:"\f105";
    margin-right:5px;
    font-family:fontawesome
}
 .blogger-tab{
    display:block
}
 .comments{
    clear:both;
    margin-top:0;
    margin-bottom:0;
    color:#010101
}
 .comments h4{
    font-size:13px;
    text-transform:capitalize;
    font-weight:400;
    padding:10px 0;
    margin:0;
    border-bottom:1px solid #eee
}
 .comments .comments-content{
    padding:10px 0
}
 .comments .comments-content .comment{
    margin-bottom:0;
    padding-bottom:8px
}
 .comments .comments-content .comment:first-child{
    padding-top:0
}
 .cmm-tabs .content-tab{
    background-color:transparent;
    padding:0
}
 .cmm-tabs-header{
    background:#010101;
    height:32px;
    margin-bottom:0px;
    position:relative
}
 .cmm-tabs-header h3 {
    display:inline-block;
    margin:0;
    color:#E4E4E4;
    font-weight:700;
    text-transform:uppercase;
    font-size:13px;
    height:32px;
    line-height:32px;
    padding-left:10px
}
 .cmm-tabs-header h3 h9{
    display:none
}
 .simplyTab .cmm-tabs-header .wrap-tab{
    float:right
}
 .cmm-tabs-header .wrap-tab a{
    height:auto;
    line-height:32px;
    padding:0px 10px;
    font-size:14px;
    display:inline-block
}
 .cmm-tabs-header .wrap-tab li{
    float:left;
    width:auto
}
 .facebook-tab,.fb_iframe_widget_fluid span,.fb_iframe_widget iframe{
    width:100%!important
}
 .comments .item-control{
    position:static
}
 .comments .avatar-image-container{
    float:left
}
 .comments .avatar-image-container,.comments .avatar-image-container img{
    height:35px;
    max-height:35px;
    width:35px;
    max-width:35px;
    border-radius:2px
}
 .comments .comment-block{
    padding:10px;
    box-shadow:none;
    border:1px solid #eee;
    border-radius:2px
}
 .comments .comment-block,.comments .comments-content .comment-replies{
    margin-left:47px;
    margin-top:0
}
 .comments .comments-content .inline-thread{
    padding:0
}
 .comments .comments-content .comment-header{
    font-size:14px;
    border-bottom:1px solid #eee;
    padding:0 0 3px
}
 .comments .comments-content .user{
    font-style:normal;
    font-weight:400
}
 .comments .comments-content .icon.blog-author{
    font-weight:400
}
 .comments .comments-content .comment-content{
    text-align:justify;
    font-size:14px;
    line-height:1.4em
}
 .comments .comment .comment-actions a{
    margin-right:5px;
    padding:2px 5px;
    color:#010101;
    font-weight:400;
    background-color:#f0f0f0;
    font-size:10px;
    letter-spacing:1px
}
 .comments .comment .comment-actions a:hover{
    color:$(color.theme);
    text-decoration:none
}
 .comments .comments-content .datetime{
    margin-left:0;
    float:right;
    font-size:11px
}
 .comments .comments-content .comment-header a{
    color:inherit
}
 .comments .comments-content .comment-header a:hover{
    color:$(color.theme)
}
 .comments .comments-content .icon.blog-author:before{
    content:"\f007";
    font-size:12px;
    font-family:FontAwesome
}
 .comments .thread-toggle{
    margin-bottom:4px
}
 .comments .comments-content .comment-thread{
    margin:4px 0
}
 .comments .continue a{
    padding:0;
    padding-top:10px;
    padding-left:47px;
    font-weight:500
}
 .comments .comments-content .loadmore.loaded{
    margin:0;
    padding:0
}
 .comments .comment-replybox-thread{
    margin:0
}
 iframe.blogger-iframe-colorize,iframe.blogger-comment-from-post{
    height:243px!important
}
 .cmm-tabs.simplyTab .content-tab{
    background-color:transparent;
    padding:0;
    margin-top:0
}
 .cmm-tabs.simplyTab .wrap-tab li a{
    text-transform:uppercase;
    color:#E4E4E4;
    font-weight:400;
    background-color:#171717;
    height:32px;
    font-size:10px;
    letter-spacing:1px
}
 .cmm-tabs.simplyTab .wrap-tab li a.activeTab{
    background-color:$(color.theme);
    color:#fff
}
 .posts-title h2 a:before{
    margin-right:10px
}
 .cmm-tabs.simplyTab .wrap-tab{
    float:right
}
 .cmm-tabs.simplyTab .wrap-tab li{
    padding:0;
    line-height: 0;
    margin-left:0
}
 .wrap-tab{
    list-style:none
}
 .content-tab{
    transition:all 0 ease;
    -webkit-transition:all 0 ease;
    -moz-transition:all 0 ease;
    -o-transition:all 0 ease
}
 #blog-pager{
    clear:both;
    text-align:center;
    margin:0
}
 .index .blog-pager,.index #blog-pager{
    display:block
}
 .index .blog-pager,.index #blog-pager,.archive .blog-pager,.archive #blog-pager{
    padding:10px 0 25px;
    text-align:left
}
 #blog-pager-newer-link a,#blog-pager-older-link a{
    display:block;
    float:left;
    margin-right:6px;
    padding:0 13px;
    border:1px solid #010101;
    text-transform:uppercase;
    line-height:32px;
    font-weight:700;
    color:#010101
}
 #blog-pager-newer-link a:hover,#blog-pager-older-link a:hover{
    background-color:#010101;
    color:#fff!important
}
 .showpageNum a,.showpage a,.showpagePoint{
    display:block;
    float:left;
    margin-right:6px;
    padding:0 12px;
    border:1px solid #010101;
    text-transform:uppercase;
    line-height:32px;
    font-weight:700;
    color:#010101
}
 .showpageNum a:hover,.showpage a:hover{
    background-color:#010101;
    color:#fff!important
}
 .showpageNum a i,.showpage a i{
    transition:all .0s ease;
    -webkit-transition:all .0s ease;
    -moz-transition:all .0s ease;
    -o-transition:all .0s ease
}
 .showpagePoint{
    background-color:#010101;
    color:#FFF
}
 .showpageOf{
    display:none!important
}
 .feed-links{
    clear:both;
    display:none;
    line-height:2.5em
}
 .sidebar-wrapper{
    float:right;
    width:300px;
    padding-top:0;
    padding-bottom:20px;
    word-wrap:break-word;
    color:#666;
    line-height:1.5em
}
 .sidebar-wrapper .widget{
    padding:0;
    background:#FFF;
    margin-bottom:20px;
    overflow:hidden;
border: 1px solid #555;
    box-shadow: 0 0 2px #333;
}
 .sidebar h2{
    color:#fff;
    background-color:#2A5A8E;
    font-size:11px;
    text-transform:uppercase;
    letter-spacing:1px;
    height:32px;
    line-height:32px;
    padding-left:10px;
    margin-bottom:10px
}
 .sidebar ul{
    list-style:none
}
 .sidebar li{
    margin:0;
    padding-bottom:.25em;
    padding-right:0;
    padding-top:0
}
 .sidebar .widget-content{
    margin:0;
    padding: 8px;
box-sizing:border-box;
}
 .list-label-widget-content li{
    display:block;
    padding:8px 0;
    border-bottom:1px solid #f3f3f3;
    position:relative
}
 .list-label-widget-content li a:before{
    content:'\203a';
    position:absolute;
    left:0px;
    top:2px;
    font-size:22px;
    color:#010101
}
 .list-label-widget-content li a{
    color:#010101;
    font-size:12px;
    padding-left: 20px;
    font-weight:400;
    text-transform:uppercase
}
 .list-label-widget-content li a:hover{
    color:$(color.theme)
}
 .list-label-widget-content li span:last-child{
    color:#dbdbdb;
    font-size:12px;
    font-weight:700;
    position:absolute;
    top:9px;
    right:0
}
 .cloud-label-widget-content{
    margin-top:10px
}
 .cloud-label-widget-content span a{
    font-size:13px;
    color:#999;
    background-color:#f4f4f4;
    padding:7px 14px;
    float:left;
    position:relative;
    display:inline-block;
    margin:0 5px 5px 0;
    text-transform:capitalize
}
 .cloud-label-widget-content span a:hover{
    color:#fff;
    background-color:$(color.theme)
}
 .cloud-label-widget-content span span{
    font-size:13px;
    color:#757575;
    background-color:#f9f9f9;
    padding:7px 14px;
    float:left;
    position:relative;
    display:inline-block;
    margin:0 5px 5px 0;
    text-transform:capitalize;
    -webkit-border-radius:3px;
    -moz-border-radius:3px;
    border-radius:3px
}
 .label-size-1,.label-size-2{
    opacity:100
}
 .FollowByEmail td{
    width:100%;
    float:left
}
 .FollowByEmail .follow-by-email-inner .follow-by-email-submit{
    margin-left:0;
    width:100%;
    border-radius:0;
    height:30px;
    font-size:11px;
     font-family:inherit;
    color:#fff;
    background-color:$(color.theme);
    text-transform:uppercase;
    letter-spacing:1px
}
 .FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover{
    background-color:#333;
    color:#FFF
}
 .FollowByEmail .follow-by-email-inner .follow-by-email-address{
    padding-left:10px;
    height:35px;
    border:1px solid #EEE;
    margin-bottom:5px;
    font:normal normal 13px Montserrat, sans-serif;
    font-size:12px;
    box-sizing:border-box
}
 .FollowByEmail .follow-by-email-inner .follow-by-email-address:focus{
    border:1px solid #EEE
}
 .FollowByEmail .widget-content:before{
    content:"Enter your email address to subscribe to this blog and receive notifications of new posts by email.";
    font-size:12px;
    color:#666;
    line-height:1.4em;
    margin-bottom:5px;
    display:block
}
 .flickr_widget .flickr_badge_image{
    float:left;
    margin-bottom:5px;
    margin-right:10px;
    overflow:hidden;
    display:inline-block
}
 .flickr_widget .flickr_badge_image:nth-of-type(4),.flickr_widget .flickr_badge_image:nth-of-type(8),.flickr_widget .flickr_badge_image:nth-of-type(12){
    margin-right:0
}
 .flickr_widget .flickr_badge_image img{
    max-width:67px;
    height:auto
}
 .flickr_widget .flickr_badge_image img:hover{
    opacity:.5
}
 #ArchiveList select{
    border:1px solid #EEE;
    border-radius:2px;
    padding:8px;
    width:100%;
    cursor:pointer;
    font:normal normal 13px Montserrat, sans-serif
}
 .PopularPosts .item-thumbnail{
    margin:0 10px 0 0 !important;
    width:80px;
    height:60px;
    float:left;
    overflow:hidden
}
 .PopularPosts ul li img{
    padding:0;
    width:80px;
    height:60px;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .PopularPosts ul li img:hover{
    -webkit-transform:scale(1.1)!important;
    -moz-transform:scale(1.1)!important;
    transform:scale(1.1)!important;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .PopularPosts .widget-content ul li{
    overflow:hidden;
    border-top:1px solid #EEE;
    padding:10px 0
}
 .sidebar .PopularPosts .widget-content ul li:first-child,.sidebar .roma-widget li:first-child{
    padding-top:0;
    border-top:0
}
 .PopularPosts ul li a{
    color:#010101;
    font-weight:400;
    font-size:14px;
    line-height:1.4em
}
 .PopularPosts ul li a:hover{
    color:$(color.theme)
}
 .PopularPosts .item-title{
    margin:0;
    padding:0
}
 .PopularPosts .item-title .popular_span{
    color:#C4C4C4;
    font-size:13px;
    font-style:normal;
    line-height:21px;
    margin-top:3px
}
 .sidebar .roma-widget li{
    overflow:hidden;
    border-top:1px solid #eee;
    padding:10px 0
}
 .roma-widget .wid-thumb{
    width:80px;
    height:60px;
    float:left;
    margin-right:10px;
    overflow:hidden
}
 .roma-widget .mag-thumb{
    display:block;
    width:80px;
    height:60px;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .roma-widget .mag-thumb:hover{
    -webkit-transform:scale(1.1)!important;
    -moz-transform:scale(1.1)!important;
    transform:scale(1.1)!important;
    transition:all .3s ease-out!important;
    -webkit-transition:all .3s ease-out!important;
    -moz-transition:all .3s ease-out!important;
    -o-transition:all .3s ease-out!important
}
 .roma-widget .wrp-titulo{
    font:normal normal 15px;
    margin:0 0 5px;
    overflow:hidden
}
 .roma-widget .wrp-titulo a{
    color:#010101;
    font-weight:400;
    font-size:14px;
    line-height:1.4em
}
 .roma-widget .wrp-titulo a:hover{
    color:$(color.theme)
}
 .post-nav li{
    padding:0;
    display:inline-block;
    width:50%
}
 .post-nav li strong{
    display:block;
    padding:0 0 5px;
    font-weight:700;
    letter-spacing:1px;
    text-transform:uppercase;
    font-size:13px
}
 .post-nav li strong i{
    transition:all .0s ease;
    -webkit-transition:all .0s ease;
    -moz-transition:all .0s ease;
    -o-transition:all .0s ease
}
 ul.post-nav{
    background-color:#FFF;
    border-bottom:3px solid #EEE;
    border-top:3px solid #EEE;
    display:block;
    width:100%;
    overflow:hidden
}
 .post-nav li a{
    color:#010101;
    line-height:1.33;
    display:block;
    padding:15px 0;
    transition:all .0s ease;
    -webkit-transition:all .0s ease;
    -moz-transition:all .0s ease;
    -o-transition:all .0s ease
}
 .post-nav li:hover a{
    color:$(color.theme)
}
 ul.post-nav span{
    font-weight:400
}
 .post-nav .previous{
    float:left;
    min-height:80px;
    border-right:3px solid #EEE;
    box-sizing:border-box;
    padding-right:10px
}
 .post-nav .next{
    text-align:right
}
 h2{
    margin:0
}
 #footer-wrapper{
    background-color:#010101
}
 #footer{
    display:block;
    overflow:hidden;
    width:100%
}
 .footer-sections{
    overflow:hidden;
    margin:0 auto;
    padding:15px 0 10px
}
 .sect-left{
    display:inline-block;
    float:left;
    width:31.655%;
    margin-right:25px
}
 .sect-left:nth-child(3){
    margin-right:0
}
 .sect-left .widget-title{
    position:relative;
    margin-bottom:10px;
    border-bottom:1px solid #171717
}
 .sect-left h2{
    display:inline-block;
    font-weight:700;
    font-size:11px;
    color:#E4E4E4;
    text-transform:uppercase;
    margin-bottom:5px;
    letter-spacing:1px
}
 .sect-left h2 a{
    color:#E4E4E4
}
 .sect-left .PopularPosts ul li a{
    color:#E4E4E4
}
 .sect-left .PopularPosts .widget-content ul li{
    border-top:1px solid #171717
}
 .sect-left .PopularPosts .widget-content ul li:first-child{
    padding-top:0;
    border-top:0
}
 .footer-column .roma-widget li{
    overflow:hidden;
    border-bottom:1px solid #eee;
    padding:10px 0
}
 .sect-left .roma-widget .wrp-titulo a{
    color:#E4E4E4
}
 .sect-left .roma-widget li{
    overflow:hidden;
    border-top:1px solid #171717;
    padding:10px 0
}
 .sect-left .PopularPosts .widget-content ul li:first-child,.sect-left .roma-widget li:first-child{
    padding-top:0;
    border-top:0
}
 .sect-left .roma-widget .wrp-titulo a:hover,.sect-left .PopularPosts ul li a:hover{
    color:$(color.theme)
}
 .footer-wrapper{
    background-color:rgba(0,0,0,0.24);
    color:#E4E4E4;
    display:block;
    padding:15px 0 13px;
    width:100%;
    border-top:1px solid #171717;
    overflow:hidden
}
 .footer-wrapper .footer-sec{
    margin:0 auto
}
 .footer-wrapper .copyright{
    font-size:12px
}
 .footer-wrapper .copyright a{
    color:#fff
}
 .footer-wrapper .copyright a:hover{
    color:$(color.theme)
}
 .footer-wrapper #social-footer{
    float:right;
    position:relative;
    display:block;
    margin-right:-12px
}
 .footer-wrapper #social-footer ul{
    overflow:hidden
}
 .footer-wrapper #social-footer ul li{
    display:block;
    float:left;
    margin-right:10px;
    margin-left:10px
}
 .footer-wrapper #social-footer ul li a{
    display:block;
    float:left;
    text-decoration:none;
    color:#E4E4E4
}
 .footer-wrapper #social-footer ul li a:hover{
    color:$(color.theme)
}
 .footer-wrapper #social-footer ul li a:before{
    display:inline-block;
    font-family:FontAwesome;
    font-style:normal;
    font-weight:400;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale
}
 .footer-wrapper a:active,.footer-wrapper #social-footer ul li a:active{
    color:$(color.theme)
}
 #social-footer .facebook:before{
    content:"\f230"
}
 #social-footer .twitter:before{
    content:"\f099"
}
 #social-footer .gplus:before{
    content:"\f0d5"
}
 #social-footer .rss:before{
    content:"\f09e"
}
 #social-footer .youtube:before{
    content:"\f167"
}
 #social-footer .skype:before{
    content:"\f17e"
}
 #social-footer .stumbleupon:before{
    content:"\f1a4"
}
 #social-footer .tumblr:before{
    content:"\f173"
}
 #social-footer .vine:before{
    content:"\f1ca"
}
 #social-footer .stack-overflow:before{
    content:"\f16c"
}
 #social-footer .linkedin:before{
    content:"\f0e1"
}
 #social-footer .dribbble:before{
    content:"\f17d"
}
 #social-footer .soundcloud:before{
    content:"\f1be"
}
 #social-footer .behance:before{
    content:"\f1b4"
}
 #social-footer .digg:before{
    content:"\f1a6"
}
 #social-footer .instagram:before{
    content:"\f16d"
}
 #social-footer .pinterest:before{
    content:"\f0d2"
}
 #social-footer .delicious:before{
    content:"\f1a5"
}
 #social-footer .codepen:before{
    content:"\f1cb"
}
 .sect-left .FollowByEmail .widget-content:before{
    color:#ddd;
    margin-top:5px
}
 .sect-left .FollowByEmail .follow-by-email-inner .follow-by-email-submit{
    background-color:rgba(255,255,255,0.1);
}
 .sect-left .FollowByEmail .follow-by-email-inner .follow-by-email-submit:hover{
    background-color:$(color.theme)
}
 .sect-left .widget:nth-of-type(2) .widget-title {
    margin-top:10px
}
 .sect-left #ArchiveList select{
    border:1px solid rgba(255,255,255,0.1);
    background:rgba(255,255,255,0.1);
    color:#ddd
}
 .sect-left #ArchiveList select option{
    color:#010101
}
 .sect-left .cloud-label-widget-content span a{
    color:#ddd;
    background-color:rgba(255,255,255,0.1)
}
 .sect-left .cloud-label-widget-content span a:hover{
    color:#fff;
    background-color:$(color.theme)
}
 #back-to-top{
    background-color:#010101;
    color:#fff;
    padding:7px 10px;
    border-radius:3px;
    font-size:16px;
    line-height:1;
    text-align:center;
    transition:all .0s ease;
    -webkit-transition:all .0s ease;
    -moz-transition:all .0s ease;
    -o-transition:all .0s ease
}
 #back-to-top:hover{
    background-color:$(color.theme);
    transition:all .3s ease;
    -webkit-transition:all .3s ease;
    -moz-transition:all .3s ease;
    -o-transition:all .3s ease
}
 .back-to-top{
    position:fixed!important;
    position:absolute;
    bottom:70px;
    right:50px;
    z-index:9999
}
 .sect-left .list-label-widget-content li {
    border-bottom: 0;
    border-top: 1px solid #171717;
}
 .sect-left .list-label-widget-content li:first-child{
    border-top:0;
    padding-top:0;
}
 .sect-left .list-label-widget-content li a {
    color: #E4E4E4;
}
 .sect-left .list-label-widget-content li a:before {
    color: #E4E4E4;
}
 .sect-left .list-label-widget-content li:first-child a:before {
    top: -6px;
}


]]></b:skin>
  <style>
/*-------Typography and ShortCodes-------*/
.firstcharacter{float:left;color:#27ae60;font-size:75px;line-height:60px;padding-top:4px;padding-right:8px;padding-left:3px}.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{margin-bottom:15px;color:#2c3e50}blockquote{font-style:italic;color:#888;border-left:5px solid #27ae60;margin-left:0;padding:10px 15px}blockquote:before{content:&#39;\f10d&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-right:10px;color:#888}blockquote:after{content:&#39;\f10e&#39;;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;margin-left:10px;color:#888}.button{background-color:#2c3e50;float:left;padding:5px 12px;margin:5px;color:#fff;text-align:center;border:0;cursor:pointer;border-radius:3px;display:block;text-decoration:none;font-weight:400;transition:all .3s ease-out !important;-webkit-transition:all .3s ease-out !important}a.button{color:#fff}.button:hover{background-color:#27ae60;color:#fff}.button.small{font-size:12px;padding:5px 12px}.button.medium{font-size:16px;padding:6px 15px}.button.large{font-size:18px;padding:8px 18px}.small-button{width:100%;overflow:hidden;clear:both}.medium-button{width:100%;overflow:hidden;clear:both}.large-button{width:100%;overflow:hidden;clear:both}.demo:before{content:&quot;\f06e&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.download:before{content:&quot;\f019&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.buy:before{content:&quot;\f09d&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.visit:before{content:&quot;\f14c&quot;;margin-right:5px;display:inline-block;font-family:FontAwesome;font-style:normal;font-weight:400;line-height:normal;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.widget .post-body ul,.widget .post-body ol{line-height:1.5;font-weight:400}.widget .post-body li{margin:5px 0;padding:0;line-height:1.5}.post-body ul li:before{content:&quot;\f105&quot;;margin-right:5px;font-family:fontawesome}pre{font-family:Monaco, &quot;Andale Mono&quot;, &quot;Courier New&quot;, Courier, monospace;background-color:#2c3e50;background-image:-webkit-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-moz-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-ms-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:-o-linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);background-image:linear-gradient(rgba(0, 0, 0, 0.05) 50%, transparent 50%, transparent);-webkit-background-size:100% 50px;-moz-background-size:100% 50px;background-size:100% 50px;line-height:25px;color:#f1f1f1;position:relative;padding:0 7px;margin:15px 0 10px;overflow:hidden;word-wrap:normal;white-space:pre;position:relative}pre:before{content:&#39;Code&#39;;display:block;background:#F7F7F7;margin-left:-7px;margin-right:-7px;color:#2c3e50;padding-left:7px;font-weight:400;font-size:14px}pre code,pre .line-number{display:block}pre .line-number a{color:#27ae60;opacity:0.6}pre .line-number span{display:block;float:left;clear:both;width:20px;text-align:center;margin-left:-7px;margin-right:7px}pre .line-number span:nth-child(odd){background-color:rgba(0, 0, 0, 0.11)}pre .line-number span:nth-child(even){background-color:rgba(255, 255, 255, 0.05)}pre .cl{display:block;clear:both}#contact{background-color:#fff;margin:30px 0 !important}#contact .contact-form-widget{max-width:100% !important}#contact .contact-form-name,#contact .contact-form-email,#contact .contact-form-email-message{background-color:#FFF;border:1px solid #eee;border-radius:3px;padding:10px;margin-bottom:10px !important;max-width:100% !important}#contact .contact-form-name{width:47.7%;height:50px}#contact .contact-form-email{width:49.7%;height:50px}#contact .contact-form-email-message{height:150px}#contact .contact-form-button-submit{max-width:100%;width:100%;z-index:0;margin:4px 0 0;padding:10px !important;text-align:center;cursor:pointer;background:#27ae60;border:0;height:auto;-webkit-border-radius:2px;-moz-border-radius:2px;-ms-border-radius:2px;-o-border-radius:2px;border-radius:2px;text-transform:uppercase;-webkit-transition:all .2s ease-out;-moz-transition:all .2s ease-out;-o-transition:all .2s ease-out;-ms-transition:all .2s ease-out;transition:all .2s ease-out;color:#FFF}#contact .contact-form-button-submit:hover{background:#2c3e50}#contact .contact-form-email:focus,#contact .contact-form-name:focus,#contact .contact-form-email-message:focus{box-shadow:none !important}.alert-message{position:relative;display:block;background-color:#FAFAFA;padding:20px;margin:20px 0;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;color:#2f3239;border:1px solid}.alert-message p{margin:0 !important;padding:0;line-height:22px;font-size:13px;color:#2f3239}.alert-message span{font-size:14px !important}.alert-message i{font-size:16px;line-height:20px}.alert-message.success{background-color:#f1f9f7;border-color:#e0f1e9;color:#1d9d74}.alert-message.success a,.alert-message.success span{color:#1d9d74}.alert-message.alert{background-color:#DAEFFF;border-color:#8ED2FF;color:#378FFF}.alert-message.alert a,.alert-message.alert span{color:#378FFF}.alert-message.warning{background-color:#fcf8e3;border-color:#faebcc;color:#8a6d3b}.alert-message.warning a,.alert-message.warning span{color:#8a6d3b}.alert-message.error{background-color:#FFD7D2;border-color:#FF9494;color:#F55D5D}.alert-message.error a,.alert-message.error span{color:#F55D5D}.fa-check-circle:before{content:&quot;\f058&quot;}.fa-info-circle:before{content:&quot;\f05a&quot;}.fa-exclamation-triangle:before{content:&quot;\f071&quot;}.fa-exclamation-circle:before{content:&quot;\f06a&quot;}.post-table table{border-collapse:collapse;width:100%}.post-table th{background-color:#eee;font-weight:bold}.post-table th,.post-table td{border:0.125em solid #333;line-height:1.5;padding:0.75em;text-align:left}@media (max-width: 30em){.post-table thead tr{position:absolute;top:-9999em;left:-9999em}.post-table tr{border:0.125em solid #333;border-bottom:0}.post-table tr + tr{margin-top:1.5em}.post-table tr,.post-table td{display:block}.post-table td{border:none;border-bottom:0.125em solid #333;padding-left:50%}.post-table td:before{content:attr(data-label);display:inline-block;font-weight:bold;line-height:1.5;margin-left:-100%;width:100%}}@media (max-width: 20em){.post-table td{padding-left:0.75em}.post-table td:before{display:block;margin-bottom:0.75em;margin-left:0}}
.FollowByEmail {
    clear: both;
}
.widget .post-body ol {
    padding: 0 0 0 15px;
}
.post-body ul li {
    list-style: none;
}
</style>
<b:template-skin><![CDATA[
/*------Layout (No Edit)----------*/
body#layout #outer-wrapper{padding: 0;
    width: 800px;
    max-width: 800px;
    margin: 0;}
body#layout .theme-opt {
    display: block !important;
}
body#layout .row {
    width: 800px;
}
body#layout #menu .widget {
display: block;
}
body#layout .section h4{color:#333!important}
body#layout #option{overflow:hidden}
body#layout #option h4{font-size:16px;padding:4px 0 7px}
body#layout #option .widget{float:left;width:33.33%}
body#layout #option .widget.locked-widget .widget-content{background-color:#333!important;border-color:#333!important;color:#fff!important}
body#layout #option .widget.locked-widget .widget-content a.editlink{color:#fff!important;border:1px solid;border-radius:2px;padding:2px 5px}
body#layout #topnav,body#layout .tm-head{height:auto}
body#layout .tm-menu{margin:0;width:70%}
body#layout .tm-menu #menu .widget {
    display: block;
}
body#layout .social-area{margin:0;width:30%}
body#layout .header-content,body#layout #header-blog{height:160px}
body#layout .header-logo{float:left;width:30%;margin:0;padding:0}
body#layout .header-ads{width:70%;margin:0}
body#layout .header-menu li.home-child{display:none}
body#layout .header-search,body#layout .m-rec{display:none}
body#layout .header-menu{float:left;width:100%;margin:4px 0 0;padding:0}
body#layout #content-wrapper{margin:0 auto}
body#layout .feat-layout .widget-content,body#layout .feat-layout h2.title,body#layout #ads-blog{display:block}
body#layout #main-wrapper{float:left;width:70%;margin:0;padding:0}
body#layout #ads-post10{display:block}
body#layout .sidebar-wrapper{float:right;width:30%;margin:0;padding:0}
body#layout #footer-wrapper{overflow:hidden}
body#layout .sect-left{width:28.065%;float:left}
body#layout #social-footer{width:30%;float:right}
body#layout #unwanted{display:none!important}
body#layout .theme-opt .layout-widget-description {
    color: #ddd;
}
/*------Layout (end)----------*/
]]></b:template-skin>

<style type='text/css'>
/*----Responsive Design----*/
@media only screen and (max-width: 1099px) {
.row{width:960px}
#main-wrapper{width:615px}
.ads-post .widget,.home-ad .widget{max-width:100%}
.sect-left{width:31.55%}
.related li{width:30.55%;}
.back-to-top{display:none}
}

/*----Portrait----*/
@media only screen and (max-width: 979px) {
.row{width:740px;padding:0 20px;box-sizing:border-box}
#header-blog,.header-content{height:auto}
.header-logo{width:auto;float:none;margin:0 auto 34px}
.header-logo img{margin: 34px auto 0;}
.header-ads{float:none;margin:0 auto 20px}
#main-wrapper{width:100%;margin-right:0}
.sidebar-wrapper{float:none;width:100%;max-width: 300px;
    margin: 0 auto;}
.item .sidebar-wrapper{padding-top:10px}
.footer-sections{padding:15px 20px 10px}
.sect-left{width:100%;margin-right:0;margin-bottom:20px}
.sect-left:last-child{margin-bottom:0}
.flickr_widget .flickr_badge_image:nth-of-type(4),.flickr_widget .flickr_badge_image:nth-of-type(8),.flickr_widget .flickr_badge_image:nth-of-type(12){margin-right:10px}
}

/*----Portrait 800----*/
@media only screen and (max-width: 800px) {
.block-image{width:247px;height:158px}
.block-image .thumb,.block-image a{height:158px}  
}

/*----Landscape----*/
@media only screen and (max-width: 767px) {
.row{width:100%;}
.header-menu{width:50%;overflow:hidden}
.nav-wrapper{padding-left:0}
#nav1,#nav,.header-menu li.home-child{display:none}
.tm-menu{width:35%}
#selectnav2{background:#010101 url(http://1.bp.blogspot.com/-V1pByIzy63Y/VmT858RDg8I/AAAAAAAACS4/j5RFxjKKbnY/s1600-r/menu2.png) no-repeat right top;height:22px;line-height:22px;padding:2px 5px;font-size:12px;box-sizing:border-box;margin-top:4px}
.selectnav{display:block}
}

/*----Landscape 640----*/
@media only screen and (max-width: 640px) {
.resp_del4,.resp_del5{display:none}
.related li{width:47%}
.related li:nth-of-type(3),.related li:nth-of-type(9){margin-right:24px}
.related li:nth-of-type(2),.related li:nth-of-type(4),.related li:nth-of-type(6),.related li:nth-of-type(8){margin-right:0}
}

/*----Mobile Portrait----*/
@media only screen and (max-width: 579px) {
.feat1 .primeiro {width:100%;margin-right:0}
.feat .primeiro-content .feat-headline a{font-size:24px}
.feat .primeiro .feat-thumb,.feat .primeiro-thumb{height:270px}
.feat1 ul li{width:48%;margin-top:20px;margin-bottom:0}
.feat1 ul li:nth-of-type(1){margin-right:4%}
.retitle{clear: both;display: block}
.block-image .thumb, .block-image, .block-image a {width: 100%;height: 230px;margin-right: 0; margin-bottom: 15px;float: none;}
.feat .primeiro .feat-thumb {
    width: 100%;
    margin: 0 auto 10px;
    float: none;
}
.feat1 ul li {
    float: none;
    width: 100%;
    padding: 0;
}
.feat1 ul li:last-child {
    padding-right: 0;
    padding-left: 0;
    margin-top: 10px;
}
.index .post .share-box, .archive .post .share-box {
    text-align: center;
    padding-bottom: 10px;
    }
.index .post .share-box .share-art, .archive .post .share-box .share-art {
    float: none;
    }
}

/*----Mobile Portrait 479----*/
@media only screen and (max-width: 479px) {
#selectnav1{width:99%;}
.tm-menu{width:25%}
.header-menu{width:80%}
.feat .primeiro-content .feat-headline a,.post h2 a,.post h2 a:visited,.post h2 strong{font-size:22px}
.feat .primeiro .feat-thumb,.feat .primeiro-thumb,.block-image .thumb,.block-image,.block-image a{height:180px}
.feat1 ul li{width:100%}
.feat1 ul li:nth-of-type(1){margin-right:0}
.item .post-title,.static_page .post-title{font-size:24px}
.resp_del,.resp_del2,.resp_del3{display:none}
.share-art .fac-art{padding:3px 10px}
.related li{width:100%;margin-right:0;min-height:auto}
.related-thumb{height:130px}
.related li .related-img{height:100%}
.cmm-tabs-header h3 h8,.comments .comments-content .datetime{display:none}
.cmm-tabs-header h3 h9{display:inline-block}
.cmm-tabs.simplyTab .wrap-tab li a{letter-spacing:0px}
.cmm-tabs-header .wrap-tab a{padding:0px 7px}
.footer-wrapper #social-footer{margin-right:0;width:100%;text-align:center}
.footer-wrapper #social-footer ul li {display:inline-block;float:none}
.footer-wrapper .copyright{text-align:center;float:left;width:100%;margin-top:5px}
}

/*----Mobile Portrait 340----*/
@media only screen and (max-width: 340px) {
.row {padding:0 10px} 
.footer-sections{padding:15px 10px 10px}
.flickr_widget .flickr_badge_image:nth-of-type(4),.flickr_widget .flickr_badge_image:nth-of-type(8),.flickr_widget .flickr_badge_image:nth-of-type(12){margin-right:0}
}

/*----Mobile Portrait MINI 240----*/
@media only screen and (max-width: 319px) {
.tm-menu{width:100%}
.social-area{display:none}
.header-logo{float:none;text-align:center;margin:0 auto;min-width:inherit}
.header-logo img{margin:15px auto 0px}
.header-ads{margin:10px auto 10px}
.header-menu{width:100%}
.nav-wrapper{padding-left:0px;padding-right:0px}
#selectnav1{background:#010101 url(http://4.bp.blogspot.com/-XmVTbf5RQLY/VmT4NfoMGOI/AAAAAAAACSI/F2sRS-yCpPI/s1600-r/menu.png) no-repeat right top;width:100%}
.header-search,.showpageOf{display:none}
.block-image .thumb, .block-image, .block-image a{height:140px}
.feat .primeiro-content .feat-headline a,.post h2 a,.post h2 a:visited,.post h2 strong {font-size:17px}
.index .post h2,.archive .post h2{margin:0}
.index .date-header{display:none}
.item .post-head,.static_page .post-head {margin:0px 0 5px}
.item .post-title,.static_page .post-title {font-size:18px}
.cmm-tabs-header{overflow:hidden}
.cmm-tabs.simplyTab .wrap-tab{float:left;width:100%;overflow:hidden;}
.cmm-tabs-header .wrap-tab li a{letter-spacing:0px;width:100%;box-sizing:border-box;padding:0}
.cmm-tabs-header .wrap-tab li{float:left;text-align:center;display:inline-block;box-sizing:border-box;width:33.33%}
.breadcrumbs,.share-art a:nth-of-type(4),.share-art a:nth-of-type(5),.cmm-tabs-header h3,.sidebar-wrapper,#footer{display:none}
.footer-wrapper #social-footer ul li a{margin-right:5px;margin-left:5px}
}
</style>

<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js' type='text/javascript'/>

<script type='text/javascript'>
//<![CDATA[
$(document).ready(function(){var dimension=150;$('#PopularPosts1,#PopularPosts2,#PopularPosts3').find('img').each(function(n,image){var image=$(image);image.attr({src:image.attr('src').replace(/s72-c/,'s'+dimension)})})});
//]]>
</script>
<script type='text/javascript'>
snippet_count = 320;

//<![CDATA[
function removeHtmlTag(strx,chop){
if(strx.indexOf("<")!=-1)
{
var s = strx.split("<");
for(var i=0;i<s.length;i++){
if(s[i].indexOf(">")!=-1){
s[i] = s[i].substring(s[i].indexOf(">")+1,s[i].length);
}
}
strx = s.join("");
}
chop = (chop < strx.length-1) ? chop : strx.length-2;
while(strx.charAt(chop-1)!=' ' && strx.indexOf(' ',chop)!=-1) chop++;
strx = strx.substring(0,chop-1);
return strx+'...';
}
function createSnippet(pID){
var div = document.getElementById(pID);
var summ = snippet_count;
var summary = '<div class="snippets">' + removeHtmlTag(div.innerHTML,summ) + '</div>';
div.innerHTML = summary;
}

//]]>
</script>

<script type='text/javascript'> 
//<![CDATA[
var text_month = [, "Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sept", "Oct", "Nov", "Dec"];
var no_image_url = "http://2.bp.blogspot.com/-IO-XEI1LgEs/VmPNKFp0BhI/AAAAAAAACOg/_JrYHMBXV5w/s1600-r/nothumb.jpg";
var feat1_number = 3;
var related_number = 3;

// Plugin: Sticky jQuery ~ BY: http://stickyjs.com
(function(e){var t={topSpacing:0,bottomSpacing:0,className:"is-sticky",wrapperClassName:"sticky-wrapper",center:false,getWidthFrom:"",responsiveWidth:false},n=e(window),r=e(document),i=[],s=n.height(),o=function(){var t=n.scrollTop(),o=r.height(),u=o-s,a=t>u?u-t:0;for(var f=0;f<i.length;f++){var l=i[f],c=l.stickyWrapper.offset().top,h=c-l.topSpacing-a;if(t<=h){if(l.currentTop!==null){l.stickyElement.css("width","").css("position","").css("top","");l.stickyElement.trigger("sticky-end",[l]).parent().removeClass(l.className);l.currentTop=null}}else{var p=o-l.stickyElement.outerHeight()-l.topSpacing-l.bottomSpacing-t-a;if(p<0){p=p+l.topSpacing}else{p=l.topSpacing}if(l.currentTop!=p){l.stickyElement.css("width",l.stickyElement.width()).css("position","fixed").css("top",p);if(typeof l.getWidthFrom!=="undefined"){l.stickyElement.css("width",e(l.getWidthFrom).width())}l.stickyElement.trigger("sticky-start",[l]).parent().addClass(l.className);l.currentTop=p}}}},u=function(){s=n.height();for(var t=0;t<i.length;t++){var r=i[t];if(typeof r.getWidthFrom!=="undefined"&&r.responsiveWidth===true){r.stickyElement.css("width",e(r.getWidthFrom).width())}}},a={init:function(n){var r=e.extend({},t,n);return this.each(function(){var n=e(this);var s=n.attr("id");var o=s?s+"-"+t.wrapperClassName:t.wrapperClassName;var u=e("<div></div>").attr("id",s+"-sticky-wrapper").addClass(r.wrapperClassName);n.wrapAll(u);if(r.center){n.parent().css({width:n.outerWidth(),marginLeft:"auto",marginRight:"auto"})}if(n.css("float")=="right"){n.css({"float":"none"}).parent().css({"float":"right"})}var a=n.parent();a.css("height",n.outerHeight());i.push({topSpacing:r.topSpacing,bottomSpacing:r.bottomSpacing,stickyElement:n,currentTop:null,stickyWrapper:a,className:r.className,getWidthFrom:r.getWidthFrom,responsiveWidth:r.responsiveWidth})})},update:o,unstick:function(t){return this.each(function(){var t=e(this);var n=-1;for(var r=0;r<i.length;r++){if(i[r].stickyElement.get(0)==t.get(0)){n=r}}if(n!=-1){i.splice(n,1);t.unwrap();t.removeAttr("style")}})}};if(window.addEventListener){window.addEventListener("scroll",o,false);window.addEventListener("resize",u,false)}else if(window.attachEvent){window.attachEvent("onscroll",o);window.attachEvent("onresize",u)}e.fn.sticky=function(t){if(a[t]){return a[t].apply(this,Array.prototype.slice.call(arguments,1))}else if(typeof t==="object"||!t){return a.init.apply(this,arguments)}else{e.error("Method "+t+" does not exist on jQuery.sticky")}};e.fn.unstick=function(t){if(a[t]){return a[t].apply(this,Array.prototype.slice.call(arguments,1))}else if(typeof t==="object"||!t){return a.unstick.apply(this,arguments)}else{e.error("Method "+t+" does not exist on jQuery.sticky")}};e(function(){setTimeout(o,0)})})(jQuery);
//]]>
</script>

</head>
<body expr:class='data:blog.pageType'>

  <div class='theme-opt' style='display:none'>
    <b:section class='option' id='option' maxwidgets='1' name='Theme Option' showaddelement='yes'>
      <b:widget id='HTML102' locked='true' title='Internal ADS Below Title (yes/no)' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'>yes</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          &lt;script type=&#39;text/javascript&#39;&gt; 
            //&lt;![CDATA[
            $(document).ready(function() {
              var ynoad = &quot;<data:content/>&quot;;
              var Fynoad = ynoad.replace(/(\r\n|\n|\r)/gm,&quot; &quot;);
              if ( Fynoad === &quot;no&quot; ) {
                $(&#39;body&#39;).addClass(&#39;ynoad&#39;);
              }
            });
            //]]&gt;
          &lt;/script&gt;
          <style>.item.ynoad .home-ad{display:none!important}</style>
        </b:includable>
      </b:widget>
      <b:widget id='HTML103' locked='true' title='Widget Recent Post No.' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
         <b:if cond='data:content == &quot;&quot;'>
         <script type='text/javascript'> 
          //<![CDATA[
          var recentposts_number = 4;
          //]]>
         </script>
         <b:else/>
&lt;script type=&#39;text/javascript&#39;&gt; 
          //&lt;![CDATA[
          var recentposts_number = <data:content/>;
          //]]&gt;
         &lt;/script&gt;
         </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='HTML104' locked='true' title='Widget Random Post No.' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
         <b:if cond='data:content == &quot;&quot;'>
         <script type='text/javascript'> 
          //<![CDATA[
          var randomposts_number = 4;
          //]]>
         </script>
         <b:else/>
&lt;script type=&#39;text/javascript&#39;&gt; 
          //&lt;![CDATA[
          var randomposts_number = <data:content/>;
          //]]&gt;
         &lt;/script&gt;
         </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='HTML105' locked='true' title='PageNavi Results No.' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>  
         <b:if cond='data:content == &quot;&quot;'>       
         <script type='text/javascript'>
          var postperpage=7;
         </script>
         <b:else/>
         &lt;script type=&#39;text/javascript&#39;&gt;
          var postperpage=<data:content/>;
         &lt;/script&gt;
         </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='HTML106' locked='true' title='Labels Max-Results No.' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>  
         <b:if cond='data:content == &quot;&quot;'>       
         <script type='text/javascript'>
//<![CDATA[
$(window).bind("load",function(){$('.Label a,.postags a,.m-rec h2 a,.breadcrumbs span a,.label-head a').each(function(){var labelPage=$(this).attr('href');$(this).attr('href',labelPage+'?&max-results=7')})});
 //]]>
</script>
         <b:else/>
         &lt;script type=&#39;text/javascript&#39;&gt;
//&lt;![CDATA[
$(window).bind(&quot;load&quot;,function(){$(&#39;.Label a,.postags a,.m-rec h2 a,.breadcrumbs span a,.label-head a&#39;).each(function(){var labelPage=$(this).attr(&#39;href&#39;);$(this).attr(&#39;href&#39;,labelPage+&#39;?&amp;max-results=<data:content/>&#39;)})});
 //]]&gt;
&lt;/script&gt;
         </b:if>
        </b:includable>
      </b:widget>
    </b:section>
    </div>

&lt;div id=&quot;pages-wrapper&quot; class=&quot;<data:blog.pageType/><b:if cond='data:blog.url == data:blog.homepageUrl'> home</b:if><b:if cond='data:blog.pageType == &quot;static_page&quot;'>item</b:if><b:if cond='data:blog.pageType == &quot;archive&quot;'>index</b:if>&quot;&gt;

<div id='outer-wrapper'>

<div id='topnav'>
<div class='tm-head row'>
<div class='tm-menu'>
<b:section class='menu1' id='menu1' maxwidgets='1' name='Top Navigation' showaddelement='yes'>
  <b:widget id='LinkList210' locked='true' title='Menu' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='text-1'>About Us</b:widget-setting>
      <b:widget-setting name='link-1'>https://24livekhabar.sbrgroup.org/p/about-us.html</b:widget-setting>
      <b:widget-setting name='text-0'>Home</b:widget-setting>
      <b:widget-setting name='link-0'>/</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
          <div class='widget-content'>
            <ul id='nav1'>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target'><data:link.name/></a></li>
              </b:loop>
           </ul> 
          </div>
        </b:includable>
  </b:widget>
</b:section>
</div>

<!-- Top Social --> 
<div class='social-area'>
<b:section class='social-top' id='social-top' maxwidgets='1' name='Social Top' showaddelement='yes'>
  <b:widget id='LinkList50' locked='true' title='Social Media Icons' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='link-3'>#</b:widget-setting>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='link-4'>#</b:widget-setting>
      <b:widget-setting name='text-1'>facebook</b:widget-setting>
      <b:widget-setting name='link-1'>#</b:widget-setting>
      <b:widget-setting name='text-0'>rss</b:widget-setting>
      <b:widget-setting name='link-2'>#</b:widget-setting>
      <b:widget-setting name='text-3'>gplus</b:widget-setting>
      <b:widget-setting name='link-0'>#</b:widget-setting>
      <b:widget-setting name='text-2'>twitter</b:widget-setting>
      <b:widget-setting name='text-4'>instagram</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
            <div class='widget-content'>
              <ul>
                <b:loop values='data:links' var='link'>
                  <li><a expr:class='data:link.name' expr:href='data:link.target' expr:title='data:link.name'/></li>
                </b:loop>
              </ul>
            </div>
    </b:includable>
  </b:widget>
</b:section>
</div>
</div>
</div>

<div id='header-blog'>
<div class='header-content row'>
<div class='header-logo'>
<b:section id='logo_blog' maxwidgets='1' name='Logo' showaddelement='yes'>
  <b:widget id='Header1' locked='true' title='24Live Khabar (Header)' type='Header' version='1'>
    <b:widget-settings>
      <b:widget-setting name='displayUrl'>http://1.bp.blogspot.com/-WEvnkdLAVXc/YApxH6Y1RJI/AAAAAAAAVv0/TQDdHYRckR8xufyNu-0Fqk7enODIouVeQCK4BGAYYCw/s284/24live-logo.png</b:widget-setting>
      <b:widget-setting name='displayHeight'>80</b:widget-setting>
      <b:widget-setting name='sectionWidth'>284</b:widget-setting>
      <b:widget-setting name='useImage'>true</b:widget-setting>
      <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
      <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
      <b:widget-setting name='displayWidth'>284</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'><h1 style='display:none;'/>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
    <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
    <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
  </b:widget>
</b:section>
</div>

<div class='header-ads'>
<b:section id='ads-content' maxwidgets='1' name='Ads 728x90' showaddelement='yes'>
  <b:widget id='AdSense2' locked='false' title='' type='AdSense'>
    <b:widget-settings>
      <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
      <b:widget-setting name='style.textcolor'>#d52c1f</b:widget-setting>
      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
      <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
      <b:widget-setting name='style.urlcolor'>#1e87f0</b:widget-setting>
      <b:widget-setting name='style.linkcolor'>#1e87f0</b:widget-setting>
      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>

</div>
</div>

      <nav id='header-navigation'>  
        <div class='row nav-wrapper'>

        <div class='nav-menu'>

<div class='header-search'>
          <li>
<a class='search'>
  <form action='/search/max-results=7' method='get'>
<input id='s' name='q' placeholder='Type and hit enter...' type='text'/>
</form>
</a>
          </li>

          </div>

          <div class='header-menu'>

<li class='home-child'><a expr:href='data:blog.homepageUrl'>Home</a></li>
<b:section class='menu' id='menu' maxwidgets='1' name='Main Menu' showaddelement='yes'>
  <b:widget id='LinkList110' locked='true' title='Menu' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='link-5'>https://www.youtube.com/c/24livekhabar</b:widget-setting>
      <b:widget-setting name='link-6'>https://24livekhabar.sbrgroup.org/search/label/Write-Up</b:widget-setting>
      <b:widget-setting name='link-3'>https://24livekhabar.sbrgroup.org/search/label/Religion</b:widget-setting>
      <b:widget-setting name='link-4'>https://24livekhabar.sbrgroup.org/search/label/Entertainment</b:widget-setting>
      <b:widget-setting name='text-1'>National </b:widget-setting>
      <b:widget-setting name='text-0'>Himachal</b:widget-setting>
      <b:widget-setting name='text-3'>RELIGION </b:widget-setting>
      <b:widget-setting name='text-2'>World</b:widget-setting>
      <b:widget-setting name='text-5'>VIDEOS</b:widget-setting>
      <b:widget-setting name='text-4'>POLITICS </b:widget-setting>
      <b:widget-setting name='text-6'>WRITE-UP</b:widget-setting>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='link-1'>https://24livekhabar.sbrgroup.org/search/label/National</b:widget-setting>
      <b:widget-setting name='link-2'>https://24livekhabar.sbrgroup.org/search/label/World</b:widget-setting>
      <b:widget-setting name='link-0'>https://24livekhabar.sbrgroup.org/search/label/Himachal</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
          <div class='widget-content'>
            <ul itemscope='' itemtype='http://schema.org/SiteNavigationElement'>
              <b:loop values='data:links' var='link'>
                <li itemprop='name'><a expr:href='data:link.target' itemprop='url'><data:link.name/></a></li>
              </b:loop>
           </ul> 
        
          </div>
        </b:includable>
  </b:widget>
</b:section>
              
     </div>
       </div>
        </div>
      </nav>

<div class='clear'/>

        <div class='row' id='content-wrapper'>

          <div id='main-wrapper'>

    <b:if cond='data:blog.canonicalUrl == data:blog.canonicalHomepageUrl'>
<div class='feat-layout' id='feat-layout'>
    <b:section class='feat-sec' id='feat-sec1' maxwidgets='1' name='Feat Section' showaddelement='yes'>
      <b:widget id='HTML3' locked='false' title='Featured Posts' type='HTML'>
        <b:widget-settings>
          <b:widget-setting name='content'>[Write-Up][feat1]</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
      </b:widget>
    </b:section>
</div>  

    </b:if>

<div id='ads-blog'>
  <b:section class='home-ad' id='ads-home' maxwidgets='1' name='Ads Home/Post (728x90)' showaddelement='yes'>
    <b:widget id='AdSense3' locked='false' title='' type='AdSense'>
      <b:widget-settings>
        <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
        <b:widget-setting name='style.textcolor'>#d52c1f</b:widget-setting>
        <b:widget-setting name='style.layout'>1x1</b:widget-setting>
        <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
        <b:widget-setting name='style.urlcolor'>#1e87f0</b:widget-setting>
        <b:widget-setting name='style.linkcolor'>#1e87f0</b:widget-setting>
        <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
      </b:widget-settings>
      <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
    </b:widget>
  </b:section>
</div>

   

    <b:section class='main' id='main' maxwidgets='2' name='Main Wrapper' showaddelement='yes'>
      <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='1'>
        <b:widget-settings>
          <b:widget-setting name='showDateHeader'>true</b:widget-setting>
          <b:widget-setting name='style.textcolor'>#d52c1f</b:widget-setting>
          <b:widget-setting name='showShareButtons'>true</b:widget-setting>
          <b:widget-setting name='authorLabel'>By</b:widget-setting>
          <b:widget-setting name='showCommentLink'>true</b:widget-setting>
          <b:widget-setting name='style.urlcolor'>#d52c1f</b:widget-setting>
          <b:widget-setting name='showAuthor'>true</b:widget-setting>
          <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
          <b:widget-setting name='style.linkcolor'>#d52c1f</b:widget-setting>
          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
          <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
          <b:widget-setting name='showLabels'>true</b:widget-setting>
          <b:widget-setting name='showLocation'>false</b:widget-setting>
          <b:widget-setting name='showTimestamp'>false</b:widget-setting>
          <b:widget-setting name='postsPerAd'>3</b:widget-setting>
          <b:widget-setting name='showBacklinks'>true</b:widget-setting>
          <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
          <b:widget-setting name='showInlineAds'>true</b:widget-setting>
          <b:widget-setting name='showReactions'>false</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main' var='top'>

      <b:include data='top' name='status-message'/>
                <!-- posts -->
                <div class='blog-posts hfeed'>
                  <b:loop values='data:posts' var='post'>
        <div class='post-outer'>
        <b:include data='post' name='post'/>
        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
        </div>
                    <b:if cond='data:post.includeAd'>
          <b:if cond='data:post.isFirstPost'>
            <data:defaultAdEnd/>
          <b:else/>
            <data:adEnd/>
          </b:if>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
          <data:adStart/>
        </b:if>
          </b:loop>
            <data:adEnd/>
             </div>
                <!-- navigation -->
                <b:if cond='data:blog.pageType == &quot;index&quot;'>
                <b:include name='nextprev'/>
                 <b:else/>
                <b:if cond='data:blog.pageType == &quot;archive&quot;'>
                <b:include name='nextprev'/>
                </b:if>
                </b:if>               
                <!-- feed links -->
                <b:include name='feedLinks'/>
                <b:if cond='data:top.showStars'>
                  <script src='http://www.google.com/jsapi' type='text/javascript'/>
                  <script type='text/javascript'>
                    google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
                    function initialize() {
                      google.annotations.setApplicationId(<data:top.blogspotReviews/>);
                      google.annotations.createAll();
                      google.annotations.fetch();
                    }
                    google.setOnLoadCallback(initialize);
                  </script>
                </b:if>

<b:if cond='data:top.showDummy'>
    <data:top.dummyBootstrap/>
  </b:if>
              </b:includable>
        <b:includable id='backlinkDeleteIcon' var='backlink'>
                <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                  <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                    <img src='http://www.blogger.com/img/icon_delete13.gif'/>
                  </a>
                </span>
              </b:includable>
        <b:includable id='backlinks' var='post'>
                <a name='links'/>
                <h4>
                  <data:post.backlinksLabel/>
                </h4>
                <b:if cond='data:post.numBacklinks != 0'>
                  <dl class='comments-block' id='comments-block'>
                    <b:loop values='data:post.backlinks' var='backlink'>
                      <div class='collapsed-backlink backlink-control'>
                        <dt class='comment-title'>
                          <span class='backlink-toggle-zippy'>
                            &#160;
                          </span>
                          <a expr:href='data:backlink.url' rel='nofollow'>
                            <data:backlink.title/>
                          </a>
                          <b:include data='backlink' name='backlinkDeleteIcon'/>
                        </dt>
                        <dd class='comment-body collapseable'>
                          <data:backlink.snippet/>
                        </dd>
                        <dd class='comment-footer collapseable'>
                          <span class='comment-author'>
                            <data:post.authorLabel/>
                            <data:backlink.author/>
                          </span>
                          <span class='comment-timestamp'>
                            <data:post.timestampLabel/>
                            <data:backlink.timestamp/>
                          </span>
                        </dd>
                      </div>
                    </b:loop>
                  </dl>
                </b:if>
                <p class='comment-footer'>
                  <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                    <data:post.createLinkLabel/>
                  </a>
                </p>
              </b:includable>
        <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
        <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
        <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
        <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:else/>
    <b:if cond='data:post.showThreadedComments'>
      <b:include data='post' name='threaded_comments'/>
    <b:else/>
      <b:include data='post' name='comments'/>
    </b:if>
  </b:if>
</b:includable>
        <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <abbr class='timeago' expr:title='data:post.timestampISO8601'><data:comment.timestamp/></abbr>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
        <b:includable id='feedLinks'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <!-- Blog feed links -->
                  <b:if cond='data:feedLinks'>
                    <div class='blog-feeds'>
                      <b:include data='feedLinks' name='feedLinksBody'/>
                    </div>
                  </b:if>
                  <b:else/>
                  <!--Post feed links -->
                  <div class='post-feeds'>
                    <b:loop values='data:posts' var='post'>
                      <b:if cond='data:post.allowComments'>
                        <b:if cond='data:post.feedLinks'>
                          <b:include data='post.feedLinks' name='feedLinksBody'/>
                        </b:if>
                      </b:if>
                    </b:loop>
                  </div>
                </b:if>
              </b:includable>
        <b:includable id='feedLinksBody' var='links'>
                <div class='feed-links'>
                  <data:feedLinksMsg/>
                  <b:loop values='data:links' var='f'>
                    <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                      <data:f.name/>
                      (
                      <data:f.feedType/>
                      )
                    </a>
                  </b:loop>
                </div>
              </b:includable>
        <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
        <b:includable id='mobile-index-post' var='post'>
                <div class='mobile-date-outer date-outer'>
                  <b:if cond='data:post.dateHeader'>
                    <div class='date-header'>
                      <span>
                        <data:post.dateHeader/>
                      </span>
                    </div>
                  </b:if>
                  <div class='mobile-post-outer'>
                    <a expr:href='data:post.url'>
                      <h3 class='mobile-index-title entry-title' itemprop='name'>
                        <data:post.title/>
                      </h3>
                      <div class='mobile-index-arrow'>
                        &amp;rsaquo;
                      </div>
                      <div class='mobile-index-contents'>
                        <b:if cond='data:post.thumbnailUrl'>
                          <div class='mobile-index-thumbnail'>
                            <div class='Image'>
                              <img expr:src='data:post.thumbnailUrl'/>
                            </div>
                          </div>
                        </b:if>
                        <div class='post-body'>
                          <b:if cond='data:post.snippet'>
                            <data:post.snippet/>
                          </b:if>
                        </div>
                      </div>
                      <div style='clear: both;'/>
                    </a>
                    <div class='mobile-index-comment'>
                      <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                        <b:if cond='data:post.allowComments'>
                          <b:if cond='data:post.numComments != 0'>
                            <b:include data='post' name='comment_count_picker'/>
                          </b:if>
                        </b:if>
                      </b:if>
                    </div>
                  </div>
                </div>
              </b:includable>
        <b:includable id='mobile-main' var='top'>
                <!-- posts -->
                <div class='blog-posts hfeed'>
                  <b:include data='top' name='status-message'/>
                  <b:if cond='data:blog.pageType == &quot;index&quot;'>
                    <b:loop values='data:posts' var='post'>
                      <b:include data='post' name='mobile-index-post'/>
                    </b:loop>
                    <b:else/>
                    <b:loop values='data:posts' var='post'>
                      <b:include data='post' name='mobile-post'/>
                    </b:loop>
                  </b:if>
                </div>
                <b:include name='mobile-nextprev'/>
              </b:includable>
        <b:includable id='mobile-nextprev'>
                <div class='blog-pager' id='blog-pager'>
                  <b:if cond='data:newerPageUrl'>
                    <div class='mobile-link-button' id='blog-pager-newer-link'>
                      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>
                        &amp;lsaquo;
                      </a>
                    </div>
                  </b:if>
                  <b:if cond='data:olderPageUrl'>
                    <div class='mobile-link-button' id='blog-pager-older-link'>
                      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>
                        &amp;rsaquo;
                      </a>
                    </div>
                  </b:if>
                  <div class='mobile-link-button' id='blog-pager-home-link'>
                    <a class='home-link' expr:href='data:blog.homepageUrl'>
                      <data:homeMsg/>
                    </a>
                  </div>
                  <div class='mobile-desktop-link'>
                    <a class='home-link' expr:href='data:desktopLinkUrl'>
                      <data:desktopLinkMsg/>
                    </a>
                  </div>
                </div>
                <div class='clear'/>
              </b:includable>
        <b:includable id='mobile-post' var='post'>
                <div class='date-outer'>
                  <b:if cond='data:post.dateHeader'>
                    <h2 class='date-header'>
                      <span>
                        <data:post.dateHeader/>
                      </span>
                    </h2>
                  </b:if>
                  <div class='date-posts'>
                    <div class='post-outer'>
                      <div class='post hentry uncustomized-post-template' itemscope='' itemtype='http://schema.org/BlogPosting'>
                        <b:if cond='data:post.thumbnailUrl'>
                          <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                        </b:if>
                        <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                        <meta expr:content='data:post.id' itemprop='postId'/>
                        <a expr:name='data:post.id'/>
                        <b:if cond='data:post.title'>
                          <h3 class='post-title entry-title' itemprop='name'>
                            <b:if cond='data:post.link'>
                              <a expr:href='data:post.link'>
                                <data:post.title/>
                              </a>
                              <b:else/>
                              <b:if cond='data:post.url'>
                                <b:if cond='data:blog.url != data:post.url'>
                                  <a expr:href='data:post.url'>
                                    <data:post.title/>
                                  </a>
                                  <b:else/>
                                  <data:post.title/>
                                </b:if>
                                <b:else/>
                                <data:post.title/>
                              </b:if>
                            </b:if>
                          </h3>
                        </b:if>
                        <div class='post-header'>
                          <div class='post-header-line-1'/>
                        </div>
                        <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                          <data:post.body/>
                          <div style='clear: both;'/>
                          <!-- clear for photos floats -->
                        </div>
                        <div class='post-footer'>
                          <div class='post-footer-line post-footer-line-1'>
                            <span class='post-author vcard'>
                              <b:if cond='data:top.showAuthor'>
                                <b:if cond='data:post.authorProfileUrl'>
                                  <span class='fn' itemprop='author' itemscope='' itemtype='http://schema.org/Person'>
                                    <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                    <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                      <span itemprop='name'>
                                        <data:post.author/>
                                      </span>
                                    </a>
                                  </span>
                                  <b:else/>
                                  <span class='fn' itemprop='author' itemscope='' itemtype='http://schema.org/Person'>
                                    <span itemprop='name'>
                                      <data:post.author/>
                                    </span>
                                  </span>
                                </b:if>
                              </b:if>
                            </span>
                            <span class='post-timestamp'>
                              <b:if cond='data:top.showTimestamp'>
                                <data:top.timestampLabel/>
                                <b:if cond='data:post.url'>
                                  <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                                  <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
                                    <abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'>
                                      <data:post.timestamp/>
                                    </abbr>
                                  </a>
                                </b:if>
                              </b:if>
                            </span>
                            <span class='post-comment-link'>
                              <b:if cond='data:blog.pageType != &quot;item&quot;'>
                                <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                                  <b:if cond='data:post.allowComments'>
                                    <b:include data='post' name='comment_count_picker'/>
                                  </b:if>
                                </b:if>
                              </b:if>
                            </span>
                          </div>
                          <div class='post-footer-line post-footer-line-2'>
                            <b:if cond='data:top.showMobileShare'>
                              <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                                <a href='javascript:void(0);'>
                                  <data:shareMsg/>
                                </a>
                              </div>
                            </b:if>
                            <b:if cond='data:top.showDummy'>
                              <div class='goog-inline-block dummy-container'>
                                <data:post.dummyTag/>
                              </div>
                            </b:if>
                          </div>
                        </div>
                      </div>
                      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                        <b:include data='post' name='comment_picker'/>
                      </b:if>
                      <b:if cond='data:blog.pageType == &quot;item&quot;'>
                        <b:include data='post' name='comment_picker'/>
                      </b:if>
                    </div>
                  </div>
                </div>
              </b:includable>
        <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
        <b:includable id='post' var='post'>
          <div class='post'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'>
         <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.title'>
              <font class='retitle'>
                <h2 class='post-title entry-title'>
                   <b:if cond='data:post.link'>
                    <a expr:href='data:post.link'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                      <b:if cond='data:post.url'>
                       <a expr:href='data:post.url'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                     <data:post.title/>
                     </b:if>
                   </b:if>
                  </h2>
                    </font>
                </b:if>
                  <div class='date-header'>
                     <div id='meta-post'>
                       <i class='fa fa-user'/> <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span></a> <i class='fa fa-calendar-o'/>
<abbr class='published timeago' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></div>
           </div>
    </b:if>
            </b:if>
            <b:if cond='data:blog.pageType == &quot;index&quot;'>
              <b:if cond='data:post.thumbnailUrl'>
                <div class='block-image'><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.thumbnailUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
              <b:if cond='data:post.firstImageUrl'>
                <div class='block-image'><div class='thumb'>
                  &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.firstImageUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
                <div class='block-image'><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(http://2.bp.blogspot.com/-IO-XEI1LgEs/VmPNKFp0BhI/AAAAAAAACOg/_JrYHMBXV5w/s1600-r/nothumb.jpg) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
             </b:if></b:if>
            </b:if>
            <b:if cond='data:blog.pageType == &quot;archive&quot;'>
              <b:if cond='data:post.thumbnailUrl'>
                <div class='block-image'><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.thumbnailUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
              <b:if cond='data:post.firstImageUrl'>
                <div class='block-image'><div class='thumb'>
                  &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.firstImageUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
                <div class='block-image'><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(http://2.bp.blogspot.com/-IO-XEI1LgEs/VmPNKFp0BhI/AAAAAAAACOg/_JrYHMBXV5w/s1600-r/nothumb.jpg) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
             </b:if></b:if>
            </b:if>
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
    &lt;div itemprop=&#39;blogPost&#39; itemscope=&#39;itemscope&#39; itemtype=&#39;http://schema.org/BlogPosting&#39;&gt;
      <meta expr:content='data:post.firstImageUrl' itemprop='image'/>
    </b:if>
    <div class='post-header'>
      <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <div class='breadcrumbs' xmlns:v='http://rdf.data-vocabulary.org/#'>
    <span typeof='v:Breadcrumb'><a class='bhome' expr:href='data:blog.homepageUrl' property='v:title' rel='v:url'>Home</a></span> <brc>/</brc>
    <b:loop values='data:posts' var='post'>
      <b:if cond='data:post.labels'>
      <b:loop values='data:post.labels' var='label'>
        <span typeof='v:Breadcrumb'>
        <a expr:href='data:label.url' property='v:title' rel='v:url'><data:label.name/></a></span>
        <b:if cond='data:label.isLast != &quot;true&quot;'><brc>/</brc></b:if>
      </b:loop>
      <b:else/>
         Unlabelled
      </b:if>
      <brc>/</brc> <span><data:post.title/></span>
    </b:loop>
  </div>
        <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name headline'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
        <div class='post-meta'>
<span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <i class='fa fa-user'/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span></a>
              </span>
            </b:if>
        </b:if>
      </span>
 <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <i class='fa fa-calendar-o'/>
        <b:if cond='data:post.url'>
          <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span>
<span class='label-head'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span>
        </div>
<div class='ads-posting'>
  <a name='ad-post'/>
</div>
   </b:if>
  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
    </b:if>
    </div>
     <article>
         <b:if cond='data:blog.pageType != &quot;item&quot;'>
         <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
         
                  <div class='date-header'>
                   
<div class='resumo'>
<span><div expr:id='&quot;summary&quot; + data:post.id'><data:post.body/></div>
<script type='text/javascript'>createSnippet(&quot;summary<data:post.id/>&quot;);</script></span></div>
                      <div style='clear: both;'/>
<div class='share-box'>
 
          <h8 class='share-title'>Share This:</h8>
               <div class='share-art'> 
<a class='fac-art' expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-facebook'/></a>

<a class='twi-art' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-twitter'/></a>

<a class='goo-art' expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-google-plus'/></a>

<a class='pin-art' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.firstImageUrl + &quot;&amp;description=&quot; + data:post.snippet' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-pinterest'/></a>  

<a class='lin-art' expr:href='&quot;http://www.linkedin.com/shareArticle?url=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-linkedin-square'/></a>

<whatsapp expr:href='data:post.url' expr:text='data:post.title'/>
<a class='wat-art' expr:href='&quot;whatsapp://send?text=&quot; + data:post.title + &quot; &gt;&gt; &quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-whatsapp'/></a>

</div>
         </div>
                 
      <div style='clear:both'/> 
                      </div>
            <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>
       </div>
          </b:if>
          <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>
       </div>
         </b:if>
     </article>

      <div class='hreview'>
        <span class='item'>
          <span class='fn'><data:post.title/></span>
          <img class='photo' expr:alt='data:post.title' expr:src='data:post.thumbnailUrl'/>
        </span> 
        Reviewed by <span class='reviewer'><data:post.author/></span>
        on 
        <span class='dtreviewed'>
          <data:post.timestamp/>
          <span class='value-title' expr:title='data:post.timestamp'/>
        </span> 
        Rating: <span class='rating'>5</span> 
      </div>
<div style='clear:both'/>  
    <div class='post-footer'>
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <div class='share-box'>
 
          <h8 class='share-title'>Share This:</h8>
               <div class='share-art'> 
<a class='fac-art' expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-facebook'/><span class='resp_del'> Facebook</span></a>

<a class='twi-art' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-twitter'/><span class='resp_del2'> Twitter</span></a>

<a class='goo-art' expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-google-plus'/><span class='resp_del3'> Google+</span></a>

<a class='pin-art' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.firstImageUrl + &quot;&amp;description=&quot; + data:post.snippet' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-pinterest'/><span class='resp_del4'> Pinterest</span></a>  

<a class='lin-art' expr:href='&quot;http://www.linkedin.com/shareArticle?url=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, left=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-linkedin-square'/><span class='resp_del5'> Linkedin</span></a>

<whatsapp expr:href='data:post.url' expr:text='data:post.title'/>
<a class='wat-art' expr:href='&quot;whatsapp://send?text=&quot; + data:post.title + &quot; &gt;&gt; &quot; + data:post.url' rel='nofollow' target='_blank'><i class='fa fa-whatsapp'/><span class='resp_del5'> Whatsapp</span></a>
</div>
         </div>
                 
      <div style='clear:both'/>  

           <!-- Ads Post - Author Box --> 
               <div class='ads-post'>
                <a name='ads-post-in'/>
               </div>

<div id='related-posts'>
        <b:if cond='data:post.labels'>
          <b:loop values='data:post.labels' var='label'>
            <b:if cond='data:label.isLast == &quot;true&quot;'>
              <data:label.name/>
            </b:if>
          </b:loop>
        </b:if>
      </div>
                  
               <div class='clear'/>  

          <ul class='post-nav'>
              <li class='next'> 
               <b:if cond='data:newerPageUrl'> 
                <a class='newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' rel='next'/> 
              <b:else/> 
                <a rel='next'><strong>Next <i class='fa fa-arrow-circle-o-right'/></strong><span>You are viewing Most Recent Post</span></a> 
              </b:if> 
                </li>
          <li class='previous'> 
          <b:if cond='data:olderPageUrl'> 
            <a class='older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' rel='previous'/> 
          <b:else/> 
            <a rel='previous'><strong><i class='fa fa-arrow-circle-o-left'/> Previous</strong><span>You are viewing Last Post</span></a> 
          </b:if> 
        </li>
    </ul>

      </b:if>
    </div>
                 
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
      &lt;/div&gt;
    </b:if>
  </div>
                </b:includable>
        <b:includable id='postQuickEdit' var='post'>
                      <b:if cond='data:post.editUrl'>
                        <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                          <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                            <!-- <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/> -->
                            <b style='color: #dd4b39;margin-left: 5px;'>
                              <i class='fa fa-pencil'/>
                              Edit
                            </b>
                          </a>
                        </span>
                      </b:if>
                    </b:includable>
        <b:includable id='shareButtons' var='post'>
                <b:if cond='data:top.showEmailButton'>
                  <a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.emailThisMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showBlogThisButton'>
                  <a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.blogThisMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showTwitterButton'>
                  <a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToTwitterMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showFacebookButton'>
                  <a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToFacebookMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showOrkutButton'>
                  <a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'>
                    <span class='share-button-link-text'>
                      <data:top.shareToOrkutMsg/>
                    </span>
                  </a>
                </b:if>
                <b:if cond='data:top.showDummy'>
                  <div class='goog-inline-block dummy-container'>
                    <data:post.dummyTag/>
                  </div>
                </b:if>
              </b:includable>
        <b:includable id='status-message'>
                <b:if cond='data:blog.pageType == &quot;error_page&quot;'>    
                <div id='errr'>
                  <h1 class='nerrr'>4<span class='fa fa-exclamation-circle'/>4</h1>
<h2 class='error'>Page Not Found!</h2>
<p>Sorry, the page you were looking for in this blog does not exist.</p>
<p>Go To Homepage by Button Below</p>
                  <span class='fa fa-hand-o-down'/>
<div class='clear'/>
<a class='homepage' href='/'>Home Page</a>
</div>    
              </b:if>
              <b:if cond='data:blog.searchQuery'>
                <div class='search-query'>
                <span>                   
                 <data:blog.pageName/>
                </span>
                </div>
                <b:else/>
                <!-- page index sela besides home -->
                <b:if cond='data:blog.pageType == &quot;index&quot;'>
                  <b:if cond='data:blog.pageName == &quot;&quot;'>
                    <b:else/>
                    <!-- label page -->
                    <div class='label'>
                      <span>
                        Results for
                      </span>
                      <span><data:blog.pageName/></span>
                    </div>
                  </b:if>
                </b:if>
              </b:if>
            </b:includable>
        <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
        <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
        <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='HTML901' locked='true' title='Comments system' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'>[blogger][disqus][facebook]</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
            <b:if cond='data:content == &quot;[blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>    
            </b:if>
            <b:if cond='data:content == &quot;[disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][facebook][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][disqus][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][blogger][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][disqus][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][blogger][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][facebook][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <div id='fb-root'/><script>(function(d, s, id){var js, fjs = d.getElementsByTagName(s)[0];if (d.getElementById(id)) return;js = d.createElement(s); js.id = id;js.src = &quot;//connect.facebook.net/en_US/sdk.js#xfbml=1&amp;version=v2.0&quot;;fjs.parentNode.insertBefore(js, fjs);}(document, &#39;script&#39;, &#39;facebook-jssdk&#39;));</script>&lt;script&gt;$(&quot;.facebook-tab&quot;).append(&quot;&lt;div class=&#39;fb-comments&#39; data-href=&#39;<data:blog.canonicalUrl/>&#39; data-width=&#39;100%&#39; data-numposts=&#39;5&#39; data-colorscheme=&#39;light&#39;&gt;&lt;/div&gt;&quot;);&lt;/script&gt;
          </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='HTML902' locked='true' title='Disqus Shortname' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'>barcelona-24Live Khabar</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:if cond='data:blog.pageType == &quot;item&quot;'>
            &lt;script type=&#39;text/javascript&#39;&gt;
            var disqus_shortname = &#39;<data:content/>&#39;;
             (function() {
              var dsq = document.createElement(&#39;script&#39;); dsq.type = &#39;text/javascript&#39;; dsq.async = true;
              dsq.src = &#39;//&#39; + disqus_shortname + &#39;.disqus.com/embed.js&#39;;
              (document.getElementsByTagName(&#39;head&#39;)[0] || document.getElementsByTagName(&#39;body&#39;)[0]).appendChild(dsq);
              })();
            &lt;/script&gt;
          </b:if>
        </b:includable>
      </b:widget>
    </b:section>         
         
<div id='ads-post10'>
<b:section id='ads-post-468' maxwidgets='1' name='ADS Inner Footer 728x90' showaddelement='yes'>
  <b:widget id='AdSense5' locked='false' title='' type='AdSense'>
    <b:widget-settings>
      <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
      <b:widget-setting name='style.textcolor'>#d52c1f</b:widget-setting>
      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
      <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
      <b:widget-setting name='style.urlcolor'>#1e87f0</b:widget-setting>
      <b:widget-setting name='style.linkcolor'>#1e87f0</b:widget-setting>
      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section>
    </div>
      </div>
      <div class='sidebar-wrapper'>
    <b:section class='sidebar' id='sidebar' name='Sidebar Right' showaddelement='yes'>
      <b:widget id='HTML5' locked='false' title='JOIN US ON TELEGRAM:' type='HTML'>
        <b:widget-settings>
          <b:widget-setting name='content'><![CDATA[<div class="separator" style="clear: both; text-align: center;"><a href="http://t.me/livekhabarhindi" imageanchor="1" style="margin-left: 1em; margin-right: 1em;" target="_blank"><img border="0" data-original-height="200" data-original-width="400" src="https://1.bp.blogspot.com/-kxJ5tL0F-oE/YBuBoMfE4zI/AAAAAAAAWKo/a3HoWkk5kdogXy3b_VaeSdKf7ZBX5ogzgCLcBGAsYHQ/s16000/20210102_105214_0000.png" /></a></div><br />]]></b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
      </b:widget>
      <b:widget id='LinkList1' locked='false' title='Send Your News' type='LinkList'>
        <b:widget-settings>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='text-0'>24livekhabar@gmail.com</b:widget-setting>
          <b:widget-setting name='link-0'/>
        </b:widget-settings>
        <b:includable id='main'>

<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
 <div class='widget-content'>
   <ul>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
</b:includable>
      </b:widget>
      <b:widget id='HTML8' locked='false' title='Facebook' type='HTML'>
        <b:widget-settings>
          <b:widget-setting name='content'>&lt;center&gt;&lt;div id=&quot;fb-root&quot;&gt;&lt;/div&gt;
&lt;script&gt;(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = &quot;//connect.facebook.net/pt_BR/sdk.js#xfbml=1&amp;version=v2.5&amp;appId=1760806057479925&quot;;
  fjs.parentNode.insertBefore(js, fjs);
}(document, &#39;script&#39;, &#39;facebook-jssdk&#39;));&lt;/script&gt;
&lt;div class=&quot;fb-page&quot; data-href=&quot;https://www.facebook.com/24livekhabar.india/&quot; data-width=&quot;300&quot; data-height=&quot;230&quot; data-hide-cover=&quot;false&quot; data-show-facepile=&quot;true&quot; data-show-posts=&quot;false&quot;&gt;&lt;div class=&quot;fb-xfbml-parse-ignore&quot;&gt;&lt;/div&gt;&lt;/div&gt;&lt;/center&gt;</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
      </b:widget>
      <b:widget id='PopularPosts2' locked='false' title='Trending News' type='PopularPosts' version='1'>
        <b:widget-settings>
          <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
          <b:widget-setting name='showThumbnails'>true</b:widget-setting>
          <b:widget-setting name='showSnippets'>true</b:widget-setting>
          <b:widget-setting name='timeRange'>LAST_WEEK</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <img border='0' expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='AdSense1' locked='false' title='' type='AdSense'>
        <b:widget-settings>
          <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
          <b:widget-setting name='style.textcolor'>#d52c1f</b:widget-setting>
          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
          <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
          <b:widget-setting name='style.urlcolor'>#1e87f0</b:widget-setting>
          <b:widget-setting name='style.linkcolor'>#1e87f0</b:widget-setting>
          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
      </b:widget>
      <b:widget id='Stats1' locked='false' title='Visitors' type='Stats'>
        <b:widget-settings>
          <b:widget-setting name='showGraphicalCounter'>true</b:widget-setting>
          <b:widget-setting name='showAnimatedCounter'>true</b:widget-setting>
          <b:widget-setting name='showSparkline'>false</b:widget-setting>
          <b:widget-setting name='sparklineStyle'>BLACK_TRANSPARENT</b:widget-setting>
          <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <!-- Content is going to be visible when data will be fetched from server. -->
    <div expr:id='data:widget.instanceId + &quot;_content&quot;' style='display: none;'>
      <!-- Counter and image will be injected later via AJAX call. -->
      <b:if cond='data:showSparkline'>
        <script src='https://www.gstatic.com/charts/loader.js' type='text/javascript'/>
        <span expr:id='data:widget.instanceId + &quot;_sparklinespan&quot;' style='display:inline-block; width:75px; height:30px'/>
      </b:if>
      <span expr:class='&quot;counter-wrapper &quot; + (data:showGraphicalCounter ? &quot;graph-counter-wrapper&quot; : &quot;text-counter-wrapper&quot;)' expr:id='data:widget.instanceId + &quot;_totalCount&quot;'>
      </span>
      <b:include name='quickedit'/>
    </div>
  </div>
</b:includable>
      </b:widget>
    </b:section>
      </div>
  <div class='clear'/>
    </div>
    <!-- end content-wrapper -->


 <div class='clear'/><!-- Footer wrapper -->


<div id='footer-wrapper'> 

<div class='footer-wrapper'>
<div class='footer-sec row'>

<!-- Footer Social --> 
<b:section class='social-footer' id='social-footer' maxwidgets='1' name='Social Footer' showaddelement='yes'>
   <b:widget id='LinkList20' locked='true' title='Social Media Icons 2' type='LinkList' version='1'>
     <b:widget-settings>
       <b:widget-setting name='link-3'>#</b:widget-setting>
       <b:widget-setting name='sorting'>NONE</b:widget-setting>
       <b:widget-setting name='link-4'>#</b:widget-setting>
       <b:widget-setting name='text-1'>facebook</b:widget-setting>
       <b:widget-setting name='link-1'>#</b:widget-setting>
       <b:widget-setting name='text-0'>rss</b:widget-setting>
       <b:widget-setting name='link-2'>#</b:widget-setting>
       <b:widget-setting name='text-3'>gplus</b:widget-setting>
       <b:widget-setting name='link-0'>#</b:widget-setting>
       <b:widget-setting name='text-2'>twitter</b:widget-setting>
       <b:widget-setting name='text-4'>instagram</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
            <div class='widget-content'>
              <ul>
                <b:loop values='data:links' var='link'>
                  <li><a expr:class='data:link.name' expr:href='data:link.target' expr:title='data:link.name'/></li>
                </b:loop>
              </ul>
            </div>
    </b:includable>
   </b:widget>
 </b:section>
   
<!-- Footer Copyright --> 
<div class='copyright'>Copyright &#169; <script>document.write(new Date().getFullYear())</script> <a expr:href='data:blog.homepageUrl'><data:blog.title/></a></div>
</div>
</div>
</div>

<!-- unwanted widgets -->
  <div style='display: none'>
    <b:section class='unwanted' id='unwanted' showaddelement='no' style='display: none'>
      <b:widget id='Attribution1' locked='true' title='' type='Attribution'>
        <b:widget-settings>
          <b:widget-setting name='copyright'/>
        </b:widget-settings>
        <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
      </b:widget>
      <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar' version='1'>
        <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d2869859802965108333\x26blogName\x3d24Live+Khabar\x26publishMode\x3dPUBLISH_MODE_HOSTED\x26navbarType\x3dBLUE\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://24livekhabar.sbrgroup.org/search\x26blogLocale\x3den\x26v\x3d2\x26homepageUrl\x3dhttp://24livekhabar.sbrgroup.org/\x26vt\x3d601812721216012699&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
      </b:widget>
    </b:section>
  </div>

&lt;/div&gt;


<script type='text/javascript'>
//<![CDATA[

// JQuery hover event with timeout by Taufik Nurrohman - https://plus.google.com/108949996304093815163/about
(function(c){c.fn.hoverTimeout=function(d,e,f,g){return this.each(function(){var a=null,b=c(this);b.hover(function(){clearTimeout(a);a=setTimeout(function(){e.call(b)},d)},function(){clearTimeout(a);a=setTimeout(function(){g.call(b)},f)})})}})(jQuery);

// jquery replacetext plugin https://github.com/cowboy/jquery-replacetext
(function(e){e.fn.replaceText=function(t,n,r){return this.each(function(){var i=this.firstChild,s,o,u=[];if(i){do{if(i.nodeType===3){s=i.nodeValue;o=s.replace(t,n);if(o!==s){if(!r&&/</.test(o)){e(i).before(o);u.push(i)}else{i.nodeValue=o}}}}while(i=i.nextSibling)}u.length&&e(u).remove()})}})(jQuery);

// Timeago jQuery plugin ~ URL: http://timeago.yarp.com
(function(e){if(typeof define==="function"&&define.amd){define(["jquery"],e)}else{e(jQuery)}})(function(e){function r(){var n=i(this);var r=t.settings;if(!isNaN(n.datetime)){if(r.cutoff==0||Math.abs(o(n.datetime))<r.cutoff){e(this).text(s(n.datetime))}}return this}function i(n){n=e(n);if(!n.data("timeago")){n.data("timeago",{datetime:t.datetime(n)});var r=e.trim(n.text());if(t.settings.localeTitle){n.attr("title",n.data("timeago").datetime.toLocaleString())}else if(r.length>0&&!(t.isTime(n)&&n.attr("title"))){n.attr("title",r)}}return n.data("timeago")}function s(e){return t.inWords(o(e))}function o(e){return(new Date).getTime()-e.getTime()}e.timeago=function(t){if(t instanceof Date){return s(t)}else if(typeof t==="string"){return s(e.timeago.parse(t))}else if(typeof t==="number"){return s(new Date(t))}else{return s(e.timeago.datetime(t))}};var t=e.timeago;e.extend(e.timeago,{settings:{refreshMillis:6e4,allowPast:true,allowFuture:false,localeTitle:false,cutoff:0,strings:{prefixAgo:null,prefixFromNow:null,suffixAgo:"ago",suffixFromNow:"from now",inPast:"in a moment",seconds:"a few seconds",minute:"%d minute",minutes:"%d mins",hour:"%d hour",hours:"%d hrs",day:"%d day",days:"%d days",month:"month",months:"%d months",year:"%d year",years:"%d years",wordSeparator:" ",numbers:[]}},inWords:function(t){function l(r,i){var s=e.isFunction(r)?r(i,t):r;var o=n.numbers&&n.numbers[i]||i;return s.replace(/%d/i,o)}if(!this.settings.allowPast&&!this.settings.allowFuture){throw"timeago allowPast and allowFuture settings can not both be set to false."}var n=this.settings.strings;var r=n.prefixAgo;var i=n.suffixAgo;if(this.settings.allowFuture){if(t<0){r=n.prefixFromNow;i=n.suffixFromNow}}if(!this.settings.allowPast&&t>=0){return this.settings.strings.inPast}var s=Math.abs(t)/1e3;var o=s/60;var u=o/60;var a=u/24;var f=a/365;var c=s<45&&l(n.seconds,Math.round(s))||s<90&&l(n.minute,1)||o<45&&l(n.minutes,Math.round(o))||o<90&&l(n.hour,1)||u<24&&l(n.hours,Math.round(u))||u<42&&l(n.day,1)||a<30&&l(n.days,Math.round(a))||a<45&&l(n.month,1)||a<365&&l(n.months,Math.round(a/30))||f<1.5&&l(n.year,1)||l(n.years,Math.round(f));var h=n.wordSeparator||"";if(n.wordSeparator===undefined){h=" "}return e.trim([r,c,i].join(h))},parse:function(t){var n=e.trim(t);n=n.replace(/\.\d+/,"");n=n.replace(/-/,"/").replace(/-/,"/");n=n.replace(/T/," ").replace(/Z/," UTC");n=n.replace(/([\+\-]\d\d)\:?(\d\d)/," $1$2");n=n.replace(/([\+\-]\d\d)$/," $100");return new Date(n)},datetime:function(n){var r=t.isTime(n)?e(n).attr("datetime"):e(n).attr("title");return t.parse(r)},isTime:function(t){return e(t).get(0).tagName.toLowerCase()==="time"}});var n={init:function(){var n=e.proxy(r,this);n();var i=t.settings;if(i.refreshMillis>0){this._timeagoInterval=setInterval(n,i.refreshMillis)}},update:function(n){var i=t.parse(n);e(this).data("timeago",{datetime:i});if(t.settings.localeTitle)e(this).attr("title",i.toLocaleString());r.apply(this)},updateFromDOM:function(){e(this).data("timeago",{datetime:t.parse(t.isTime(this)?e(this).attr("datetime"):e(this).attr("title"))});r.apply(this)},dispose:function(){if(this._timeagoInterval){window.clearInterval(this._timeagoInterval);this._timeagoInterval=null}}};e.fn.timeago=function(e,t){var r=e?n[e]:n.init;if(!r){throw new Error("Unknown function name '"+e+"' for timeago")}this.each(function(){r.call(this,t)});return this};document.createElement("abbr");document.createElement("time")});

// Plugin: SelectNav.js ~ url: https://github.com/lukaszfiszer/selectnav.js
window.selectnav=function(){"use strict";var e=function(e,t){function c(e){var t;if(!e)e=window.event;if(e.target)t=e.target;else if(e.srcElement)t=e.srcElement;if(t.nodeType===3)t=t.parentNode;if(t.value)window.location.href=t.value}function h(e){var t=e.nodeName.toLowerCase();return t==="ul"||t==="ol"}function p(e){for(var t=1;document.getElementById("selectnav"+t);t++);return e?"selectnav"+t:"selectnav"+(t-1)}function d(e){a++;var t=e.children.length,n="",l="",c=a-1;if(!t){return}if(c){while(c--){l+=o}l+=" "}for(var v=0;v<t;v++){var m=e.children[v].children[0];if(typeof m!=="undefined"){var g=m.innerText||m.textContent;var y="";if(r){y=m.className.search(r)!==-1||m.parentNode.className.search(r)!==-1?f:""}if(i&&!y){y=m.href===document.URL?f:""}n+='<option value="'+m.href+'" '+y+">"+l+g+"</option>";if(s){var b=e.children[v].children[1];if(b&&h(b)){n+=d(b)}}}}if(a===1&&u){n='<option value="">'+u+"</option>"+n}if(a===1){n='<select class="selectnav" id="'+p(true)+'">'+n+"</select>"}a--;return n}e=document.getElementById(e);if(!e){return}if(!h(e)){return}if(!("insertAdjacentHTML"in window.document.documentElement)){return}document.documentElement.className+=" js";var n=t||{},r=n.activeclass||"active",i=typeof n.autoselect==="boolean"?n.autoselect:true,s=typeof n.nested==="boolean"?n.nested:true,o=n.indent||"-",u=n.label||"Menu",a=0,f=" selected ";e.insertAdjacentHTML("afterend",d(e));var l=document.getElementById(p());if(l.addEventListener){l.addEventListener("change",c)}if(l.attachEvent){l.attachEvent("onchange",c)}return l};return function(t,n){e(t,n)}}();

// Tabslet jQuery plugin -  http://vdw.staytuned.gr
(function($,window,undefined){$.fn.tabslet=function(options){var defaults={mouseevent:"click",attribute:"href",animation:false,autorotate:false,pauseonhover:true,delay:2000,active:1,controls:{prev:".prev",next:".next"}};var options=$.extend(defaults,options);return this.each(function(){var $this=$(this);options.mouseevent=$this.data("mouseevent")||options.mouseevent;options.attribute=$this.data("attribute")||options.attribute;options.animation=$this.data("animation")||options.animation;options.autorotate=$this.data("autorotate")||options.autorotate;options.pauseonhover=$this.data("pauseonhover")||options.pauseonhover;options.delay=$this.data("delay")||options.delay;options.active=$this.data("active")||options.active;$this.find("> div").hide();$this.find("> div").eq(options.active-1).show();$this.find("> ul li").eq(options.active-1).addClass("active");var fn=eval(function(){$(this).trigger("_before");$this.find("> ul li").removeClass("active");$(this).addClass("active");$this.find("> div").hide();var currentTab=$(this).find("a").attr(options.attribute);if(options.animation){$this.find(currentTab).animate({opacity:"show"},"slow",function(){$(this).trigger("_after")})}else{$this.find(currentTab).show();$(this).trigger("_after")}return false});var init=eval("$this.find('> ul li')."+options.mouseevent+"(fn)");init;var elements=$this.find("> ul li"),i=options.active-1;function forward(){i=++i%elements.length;options.mouseevent=="hover"?elements.eq(i).trigger("mouseover"):elements.eq(i).click();var t=setTimeout(forward,options.delay);$this.mouseover(function(){if(options.pauseonhover){clearTimeout(t)}})}if(options.autorotate){setTimeout(forward,0);if(options.pauseonhover){$this.on("mouseleave",function(){setTimeout(forward,1000)})}}function move(direction){if(direction=="forward"){i=++i%elements.length}if(direction=="backward"){i=--i%elements.length}elements.eq(i).click()}$this.find(options.controls.next).click(function(){move("forward")});$this.find(options.controls.prev).click(function(){move("backward")});$this.on("destroy",function(){$(this).removeData()})})};$(document).ready(function(){$('[data-toggle="tabslet"]').tabslet()})})(jQuery);

// Simple Tab JQuery Plugin by Taufik Nurrohman - https://plus.google.com/108949996304093815163/about
(function(a){a.fn.simplyTab=function(b){b=jQuery.extend({active:1,fx:null,showSpeed:400,hideSpeed:400,showEasing:null,hideEasing:null,show:function(){},hide:function(){},change:function(){}},b);return this.each(function(){var e=a(this),c=e.children("[data-tab]"),d=b.active-1;e.addClass("simplyTab").prepend('<ul class="wrap-tab"></ul>');c.addClass("content-tab").each(function(){a(this).hide();e.find(".wrap-tab").append('<li><a href="#">'+a(this).data("tab")+"</a></li>")}).eq(d).show();e.find(".wrap-tab a").on("click",function(){var f=a(this).parent().index();a(this).closest(".wrap-tab").find(".activeTab").removeClass("activeTab");a(this).addClass("activeTab");if(b.fx=="slide"){if(c.eq(f).is(":hidden")){c.slideUp(b.hideSpeed,b.hideEasing,function(){b.hide.call(e)}).eq(f).slideDown(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(b.fx=="fade"){if(c.eq(f).is(":hidden")){c.hide().eq(f).fadeIn(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(b.fx=="fancyslide"){if(c.eq(f).is(":hidden")){c.slideUp(b.hideSpeed,b.hideEasing,function(){b.hide.call(e)}).eq(f).delay(b.hideSpeed).slideDown(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(c.eq(f).is(":hidden")){c.hide().eq(f).show()}}}}b.change.call(e);return false}).eq(d).addClass("activeTab")})}})(jQuery);

// Main Scripts 
$(document).ready(function($) {
    var k = -1,
        o = "",
        p = "";
    $("#menu").find("ul").find("li").each(function() {
        for (var text = $(this).text(), url = $(this).find("a").attr("href"), x = 0, z = 0; z < text.length && (x = text.indexOf("_", x), -1 != x); z++)
            x++;
        if (level = z, level > k && (o += "<ul>", p += "<ul>"), level < k) {
            offset = k - level;
            for (var z = 0; z < offset; z++) o += "</ul></li>", p += "</ul></li>"
        }
        text = text.replace(/_/gi, ""), o += "<li><a href='" + url + "'>" + text + "</a>", p += "<li><a href='" + url + "'>";
        for (var z = 0; z < level; z++) p += "";
        p += text + "</a>", k = level
    });
    for (var x = 0; k >= x; x++) o += "</ul>", p += "</ul>", 0 != x && (o += "</li>", p += "</li>");
    $("#menu .LinkList").html(p), $("#menu > .LinkList > ul").attr("id", "nav"), selectnav('nav'), $("#menu ul > li > ul").parent("li").addClass("parent"), $("#menu .widget").attr("style", "display:block!important;");
});
$(function() {
    selectnav('nav1');
});
$(document).ready(function() {
    $(".cmm-tabs").simplyTab({
        active: 1,
        fx: "fade",
        showSpeed: 400,
        hideSpeed: 400
    });
    $('.blogger-tab').append($('#comments'));
    $(".cmm-tabs.simplyTab .wrap-tab").wrap("<div class='cmm-tabs-header'/>");
    $('.cmm-tabs-header').prepend('<h3><h8>Post </h8>Comment<h9>s</h9></h3>')
});
$(document).ready(function(e) {
    e("abbr.timeago").timeago()
});
$(document).ready(function() {
    $("ul#sub-menu").parent("li").addClass("hasSub");
    (jQuery)
});
$(document).ready(function() {
    $('a[name="ads-post-in"]').before($('#ads-post10').html());
    $('#ads-post10').html('')
});
$(document).ready(function() {
    $(".sidebar-wrapper .widget h2").wrap("<div class='widget-title'/>");
    $(".footer-sections .widget h2").wrap("<div class='widget-title'/>");
    $(".index .post-outer,.archive .post-outer").each(function() {
        $(this).find(".block-image .thumb a").attr("style", function(e, t) {
            return t.replace("/default.jpg", "/mqdefault.jpg")
        }).attr("style", function(e, t) {
            return t.replace("s72-c", "s1600")
        })
    });
    $(window).scroll(function() {
        if ($(this).scrollTop() > 200) {
            $('#back-to-top').fadeIn()
        } else {
            $('#back-to-top').fadeOut()
        }
    });
    $('#back-to-top').hide().click(function() {
        $('html, body').animate({
            scrollTop: 0
        }, 1000);
        return false
    });
    var search = $('.search');
    search.click(function(e) {
        e.preventDefault();
        if (search.is('.active') && $(e.target).is(search)) {
            search.removeClass('active')
        } else {
            search.addClass('active');
            search.find('input').focus()
        }
    });
    $('body').click(function(e) {
        if (search.is('.active') && !$(e.target).is('.search, .search form, .search input')) {
            search.removeClass('active')
        }
    });
    (function(e) {
        var t = e("a.newer-link");
        var n = e("a.older-link");
        e.get(t.attr("href"), function(n) {
            t.html('<strong>Next <i class="fa fa-arrow-circle-o-right"></i></strong><span>' + e(n).find(".post h1.post-title").text() + "</span>")
        }, "html");
        e.get(n.attr("href"), function(t) {
            n.html('<strong><i class="fa fa-arrow-circle-o-left"></i> Previous</strong><span>' + e(t).find(".post h1.post-title").text() + "</span>")
        }, "html")
    })(jQuery)
});
$(document).ready(function() {
    $('.HTML .widget-content').each(function() {
        var text = $(this).text();
        if (text.match('randomposts')) {
            $.ajax({
                url: "/feeds/posts/default?alt=json-in-script",
                type: 'get',
                dataType: "jsonp",
                success: function(datax) {
                    var numpost = datax.feed.entry.length;
                    var min = 0;
                    var max = numpost - randomposts_number;
                    var random = Math.floor(Math.random() * (max - min + 1)) + min;
                    $.ajax({
                        url: "/feeds/posts/default?alt=json-in-script&start-index=" + random + "&max-results=" + randomposts_number,
                        type: 'get',
                        dataType: "jsonp",
                        success: function(data) {
                            var posturl = "";
                            var htmlcode = '<ul class="roma-widget">';
                            for (var i = 0; i < data.feed.entry.length; i++) {
                                for (var j = 0; j < data.feed.entry[i].link.length; j++) {
                                    if (data.feed.entry[i].link[j].rel == "alternate") {
                                        posturl = data.feed.entry[i].link[j].href;
                                        break
                                    }
                                }
                                var posttitle = data.feed.entry[i].title.$t;
                                var author = data.feed.entry[i].author[0].name.$t;
                                var get_date = data.feed.entry[i].published.$t,
                                    year = get_date.substring(0, 4),
                                    month = get_date.substring(5, 7),
                                    day = get_date.substring(8, 10),
                                    date = text_month[parseInt(month, 10)] + ' ' + day + ', ' + year;
                                var tag = data.feed.entry[i].category[0].term;
                                var content = data.feed.entry[i].content.$t;
                                var $content = $('<div>').html(content);
                                if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                                    var src2 = data.feed.entry[i].media$thumbnail.url;
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                                } else if (content.indexOf("<img") > -1) {
                                    var src = $content.find('img:first').attr('src');
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"/>'
                                } else {
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + no_image_url + ') no-repeat center center;background-size: cover"/>'
                                }
                                htmlcode += '<li><div class="wid-thumb">' + thumb + '</div><div class="p-head"><h3 class="wrp-titulo"><a href="' + posturl + '">' + posttitle + '</a></h3></div></li>'
                            }
                            htmlcode += '</ul><div class="clear"/>';
                            $('.HTML .widget-content').each(function() {
                                if ($(this).text().match('randomposts')) {
                                    $(this).html(htmlcode);
                                    $(this).parent().addClass('ideias-widget');
                                    $(this).find('.rcp-thumb').each(function() {
                                        $(this).attr('style', function(i, src) {
                                            return src.replace('/default.jpg', '/mqdefault.jpg')
                                        }).attr('style', function(i, src) {
                                            return src.replace('s72-c', 's1600')
                                        })
                                    });
                                    $("p.trans").each(function() {
                                        var e = $(this).text();
                                        var t = $(this).attr("data-tran");
                                        $("#pages-wrapper *").replaceText(e, t)
                                    })
                                }
                            })
                        }
                    })
                }
            })
        }
        if (text.match('recentposts')) {
            $.ajax({
                url: "/feeds/posts/default?alt=json-in-script",
                type: 'get',
                dataType: "jsonp",
                success: function(datax) {
                    $.ajax({
                        url: "/feeds/posts/default?alt=json-in-script&max-results=" + recentposts_number,
                        type: 'get',
                        dataType: "jsonp",
                        success: function(data) {
                            var posturl = "";
                            var htmlcode = '<ul class="roma-widget">';
                            for (var i = 0; i < data.feed.entry.length; i++) {
                                for (var j = 0; j < data.feed.entry[i].link.length; j++) {
                                    if (data.feed.entry[i].link[j].rel == "alternate") {
                                        posturl = data.feed.entry[i].link[j].href;
                                        break
                                    }
                                }
                                var posttitle = data.feed.entry[i].title.$t;
                                var author = data.feed.entry[i].author[0].name.$t;
                                var get_date = data.feed.entry[i].published.$t,
                                    year = get_date.substring(0, 4),
                                    month = get_date.substring(5, 7),
                                    day = get_date.substring(8, 10),
                                    date = text_month[parseInt(month, 10)] + ' ' + day + ', ' + year;
                                var tag = data.feed.entry[i].category[0].term;
                                var content = data.feed.entry[i].content.$t;
                                var $content = $('<div>').html(content);
                                if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                                    var src2 = data.feed.entry[i].media$thumbnail.url;
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                                } else if (content.indexOf("<img") > -1) {
                                    var src = $content.find('img:first').attr('src');
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"/>'
                                } else {
                                    var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + no_image_url + ') no-repeat center center;background-size: cover"/>'
                                }
                                htmlcode += '<li><div class="wid-thumb">' + thumb + '</div><div class="p-head"><h3 class="wrp-titulo"><a href="' + posturl + '">' + posttitle + '</a></h3></div></li>'
                            }
                            htmlcode += '</ul><div class="clear"/>';
                            $('.HTML .widget-content').each(function() {
                                if ($(this).text().match('recentposts')) {
                                    $(this).html(htmlcode);
                                    $(this).parent().addClass('ideias-widget');
                                    $(this).find('.rcp-thumb').each(function() {
                                        $(this).attr('style', function(i, src) {
                                            return src.replace('/default.jpg', '/mqdefault.jpg')
                                        }).attr('style', function(i, src) {
                                            return src.replace('s72-c', 's1600')
                                        })
                                    });
                                    $("p.trans").each(function() {
                                        var e = $(this).text();
                                        var t = $(this).attr("data-tran");
                                        $("#pages-wrapper *").replaceText(e, t)
                                    })
                                }
                            })
                        }
                    })
                }
            })
        }
    });
    $(".feat-layout .HTML .widget-content").each(function() {
        var t = $(this).html(),
            k = $(this).prev("h2").text();
        var z = t.match(/[^[\]]+(?=])/g);
        $(this).html("<span>" + z[0] + "</span><span>" + z[1] + "</span>");
        var ideas = $(this).text();
        var g = $(this).find("span").eq(0).text();
        var style = $(this).find("span").eq(1).text();
        if (style.match('feat1')) {
            $.ajax({
                url: "/feeds/posts/default/-/" + g + "?alt=json-in-script&max-results=" + feat1_number,
                type: 'get',
                dataType: "jsonp",
                success: function(data) {
                    var posturl = "";
                    var htmlcode = '<ul>';
                    for (var i = 0; i < data.feed.entry.length; i++) {
                        for (var j = 0; j < data.feed.entry[i].link.length; j++) {
                            if (data.feed.entry[i].link[j].rel == "alternate") {
                                posturl = data.feed.entry[i].link[j].href;
                                break
                            }
                        }
                        var posttitle = data.feed.entry[i].title.$t;
                        var author = data.feed.entry[i].author[0].name.$t;
                        var get_date = data.feed.entry[i].published.$t,
                            year = get_date.substring(0, 4),
                            month = get_date.substring(5, 7),
                            day = get_date.substring(8, 10),
                            date = text_month[parseInt(month, 10)] + ' ' + day + ', ' + year;
                        var content = data.feed.entry[i].content.$t;
                        var $content = $('<div>').html(content);
                        if (i == 0) {
                            var re = /<\S[^>]*>/g;
                            var postcontent = content.replace(re, "");
                            if (postcontent.length > 100) {
                                postcontent = '' + postcontent.substring(0, 130) + '...'
                            }
                            if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                                var src2 = data.feed.entry[i].media$thumbnail.url;
                                var thumb = '<a class="primeiro-thumb" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                            } else if (content.indexOf("<img") > -1) {
                                var src = $content.find('img:first').attr('src');
                                var thumb = '<a class="primeiro-thumb" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"/>'
                            } else {
                                var thumb = '<a class="primeiro-thumb" href="' + posturl + '" style="background:url(' + no_image_url + ') no-repeat center center;background-size: cover"/>'
                            }
                        } else {
                            if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                                var src2 = data.feed.entry[i].media$thumbnail.url;
                                var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                            } else if (content.indexOf("<img") > -1) {
                                var src = $content.find('img:first').attr('src');
                                var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"/>'
                            } else {
                                var thumb = '<a class="mag-thumb" href="' + posturl + '" style="background:url(' + no_image_url + ') no-repeat center center;background-size: cover"/>'
                            }
                        };
                        if (i == 0) {
                            htmlcode += '<div class="primeiro"><div class="feat-thumb">' + thumb + '</div><div class="primeiro-content"><h3 class="feat-headline"><a href="' + posturl + '">' + posttitle + '</a></h3><span class="p-author">' + author + '</span><span class="p-date">' + date + '</span><p class="recent-des">' + postcontent + '</p></div></div>'
                        } else {
                            htmlcode += '<li><div class="feat-thumb">' + thumb + '</div><div class="mag-content"><span class="p-author">' + author + '</span><h3 class="feat-headline"><a href="' + posturl + '">' + posttitle + '</a></h3></div><div class="clear"/></li></div>'
                        }
                    }
                    htmlcode += '</ul>';
                    $(".feat-layout .HTML .widget-content").each(function() {
                        var text = $(this).text();
                        if (text == ideas) {
                            $(this).html(htmlcode);
                            $(this).parent().addClass('feat1');
                            $(this).parent().addClass('feat');
                            $(this).removeClass('widget-content').addClass('layout-content');
                            $(this).find('.mag-thumb,.primeiro-thumb').each(function() {
                                $(this).attr('style', function(i, src) {
                                    return src.replace('/default.jpg', '/mqdefault.jpg')
                                }).attr('style', function(i, src) {
                                    return src.replace('s72-c', 's1600')
                                })
                            });
                            $("p.trans").each(function() {
                                var e = $(this).text();
                                var t = $(this).attr("data-tran");
                                $("#pages-wrapper *").replaceText(e, t)
                            })
                        }
                    })
                }
            })
        }
    })
});
$("#related-posts").each(function() {
    var g = $(this).html();
    $.ajax({
        url: "/feeds/posts/default/-/" + g + "?alt=json-in-script&max-results=" + related_number,
        type: 'get',
        dataType: "jsonp",
        success: function(data) {
            var posturl = "";
            var htmlcode = '<div class="related">';
            for (var i = 0; i < data.feed.entry.length; i++) {
                for (var j = 0; j < data.feed.entry[i].link.length; j++) {
                    if (data.feed.entry[i].link[j].rel == "alternate") {
                        posturl = data.feed.entry[i].link[j].href;
                        break
                    }
                }
                var posttitle = data.feed.entry[i].title.$t;
                var content = data.feed.entry[i].content.$t;
                var $content = $('<div>').html(content);
                if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                    var src2 = data.feed.entry[i].media$thumbnail.url;
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                } else if (content.indexOf("<img") > -1) {
                    var src = $content.find('img:first').attr('src');
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"/>'
                } else {
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + no_image_url + ') no-repeat center center;background-size: cover"/>'
                }
                htmlcode += '<li><div class="related-thumb">' + thumb + '</div><h3 class="related-title"><a href="' + posturl + '">' + posttitle + '</a></h3></li>'
            }
            htmlcode += '</div><div class="clear"/>';
            $("#related-posts").html(htmlcode);
            $('.related-img').each(function() {
                $(this).attr('style', function(i, src) {
                    return src.replace('/default.jpg', '/mqdefault.jpg')
                }).attr('style', function(i, src) {
                    return src.replace('s72-c', 's1600')
                })
            });
            $("p.trans").each(function() {
                var e = $(this).text();
                var t = $(this).attr("data-tran");
                $("#pages-wrapper *").replaceText(e, t)
            })
        }
    })
});
//]]>
</script>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script type='text/javascript'>
//<![CDATA[
$(document).ready(function() {
    $('a[name="ad-post"]').before($('#ads-blog').html());
    $('#ads-blog').html('')
});
//]]>
</script>
</b:if>


</div>

<script type='text/javascript'>
var numshowpage=3;
var upPageWord =&#39;&lt;i class=&quot;fa fa-angle-left&quot;&gt;&lt;/i&gt; Prev&#39;;
var downPageWord =&#39;Next &lt;i class=&quot;fa fa-angle-right&quot;&gt;&lt;/i&gt;&#39;;
var urlactivepage=location.href;
var home_page=&quot;/&quot;;
</script>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<script type='text/javascript'>
//<![CDATA[
var nopage;var jenis;var nomerhal;var lblname1;halamanblogger();function loophalaman(banyakdata){var html='';nomerkiri=parseInt(numshowpage/2);if(nomerkiri==numshowpage-nomerkiri){numshowpage=nomerkiri*2+1}mulai=nomerhal-nomerkiri;if(mulai<1)mulai=1;maksimal=parseInt(banyakdata/postperpage)+1;if(maksimal-1==banyakdata/postperpage)maksimal=maksimal-1;akhir=mulai+numshowpage-1;if(akhir>maksimal)akhir=maksimal;html+="<span class='showpageOf'>Page "+nomerhal+' of '+maksimal+"</span>";var prevnomer=parseInt(nomerhal)-1;if(nomerhal>1){if(nomerhal==2){if(jenis=="page"){html+='<span class="showpage"><a href="'+home_page+'">'+upPageWord+'</a></span>'}else{html+='<span class="showpageNum"><a href="/search/label/'+lblname1+'?&max-results='+postperpage+'">'+upPageWord+'</a></span>'}}else{if(jenis=="page"){html+='<span class="showpageNum"><a href="#" onclick="redirectpage('+prevnomer+');return false">'+upPageWord+'</a></span>'}else{html+='<span class="showpageNum"><a href="#" onclick="redirectlabel('+prevnomer+');return false">'+upPageWord+'</a></span>'}}}if(mulai>1){if(jenis=="page"){html+='<span class="showpageNum"><a href="'+home_page+'">1</a></span>'}else{html+='<span class="showpageNum"><a href="/search/label/'+lblname1+'?&max-results='+postperpage+'">1</a></span>'}}if(mulai>2){html+='  '}for(var jj=mulai;jj<=akhir;jj++){if(nomerhal==jj){html+='<span class="showpagePoint">'+jj+'</span>'}else if(jj==1){if(jenis=="page"){html+='<span class="showpageNum"><a href="'+home_page+'">1</a></span>'}else{html+='<span class="showpageNum"><a href="/search/label/'+lblname1+'?&max-results='+postperpage+'">1</a></span>'}}else{if(jenis=="page"){html+='<span class="showpageNum"><a href="#" onclick="redirectpage('+jj+');return false">'+jj+'</a></span>'}else{html+='<span class="showpageNum"><a href="#" onclick="redirectlabel('+jj+');return false">'+jj+'</a></span>'}}}if(akhir<maksimal-1){html+=''}if(akhir<maksimal){if(jenis=="page"){html+='<span class="showpageNum"><a href="#" onclick="redirectpage('+maksimal+');return false">'+maksimal+'</a></span>'}else{html+='<span class="showpageNum"><a href="#" onclick="redirectlabel('+maksimal+');return false">'+maksimal+'</a></span>'}}var nextnomer=parseInt(nomerhal)+1;if(nomerhal<maksimal){if(jenis=="page"){html+='<span class="showpageNum"><a href="#" onclick="redirectpage('+nextnomer+');return false">'+downPageWord+'</a></span>'}else{html+='<span class="showpageNum"><a href="#" onclick="redirectlabel('+nextnomer+');return false">'+downPageWord+'</a></span>'}}var pageArea=document.getElementsByName("pageArea");var blogPager=document.getElementById("blog-pager");for(var p=0;p<pageArea.length;p++){pageArea[p].innerHTML=html}if(pageArea&&pageArea.length>0){html=''}if(blogPager){blogPager.innerHTML=html}}function hitungtotaldata(root){var feed=root.feed;var totaldata=parseInt(feed.openSearch$totalResults.$t,10);loophalaman(totaldata)}function halamanblogger(){var thisUrl=urlactivepage;if(thisUrl.indexOf("/search/label/")!=-1){if(thisUrl.indexOf("?updated-max")!=-1){lblname1=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?updated-max"))}else{lblname1=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?&max"))}}if(thisUrl.indexOf("?q=")==-1&&thisUrl.indexOf(".html")==-1){if(thisUrl.indexOf("/search/label/")==-1){jenis="page";if(urlactivepage.indexOf("#PageNo=")!=-1){nomerhal=urlactivepage.substring(urlactivepage.indexOf("#PageNo=")+8,urlactivepage.length)}else{nomerhal=1}document.write("<script src=\""+home_page+"feeds/posts/summary?max-results=1&alt=json-in-script&callback=hitungtotaldata\"><\/script>")}else{jenis="label";if(thisUrl.indexOf("&max-results=")==-1){postperpage=20}if(urlactivepage.indexOf("#PageNo=")!=-1){nomerhal=urlactivepage.substring(urlactivepage.indexOf("#PageNo=")+8,urlactivepage.length)}else{nomerhal=1}document.write('<script src="'+home_page+'feeds/posts/summary/-/'+lblname1+'?alt=json-in-script&callback=hitungtotaldata&max-results=1" ><\/script>')}}}function redirectpage(numberpage){jsonstart=(numberpage-1)*postperpage;nopage=numberpage;var nBody=document.getElementsByTagName('head')[0];var newInclude=document.createElement('script');newInclude.type='text/javascript';newInclude.setAttribute("src",home_page+"feeds/posts/summary?start-index="+jsonstart+"&max-results=1&alt=json-in-script&callback=finddatepost");nBody.appendChild(newInclude)}function redirectlabel(numberpage){jsonstart=(numberpage-1)*postperpage;nopage=numberpage;var nBody=document.getElementsByTagName('head')[0];var newInclude=document.createElement('script');newInclude.type='text/javascript';newInclude.setAttribute("src",home_page+"feeds/posts/summary/-/"+lblname1+"?start-index="+jsonstart+"&max-results=1&alt=json-in-script&callback=finddatepost");nBody.appendChild(newInclude)}function finddatepost(root){post=root.feed.entry[0];var timestamp1=post.published.$t.substring(0,19)+post.published.$t.substring(23,29);var timestamp=encodeURIComponent(timestamp1);if(jenis=="page"){var alamat="/search?updated-max="+timestamp+"&max-results="+postperpage+"#PageNo="+nopage}else{var alamat="/search/label/"+lblname1+"?updated-max="+timestamp+"&max-results="+postperpage+"#PageNo="+nopage}location.href=alamat}
//]]>
</script>
</b:if>
</b:if>
<script type='text/javascript'>
//<![CDATA[
(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.5&appId=1760806057479925";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));
//]]>
</script>
<div class='back-to-top'>
      <a href='#' id='back-to-top' title='back to top'>
        <i class='fa fa-hand-o-up'/>
      </a>
    </div>
</body>
  <script async='async' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
<ins class='adsbygoogle' data-ad-client='ca-pub-4974651546853754' data-ad-slot='1491889926' style='display:inline-block;width:336px;height:280px'/>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>

</html>
1
<?xml version="1.0" encoding="UTF-8" ?>
2
<!DOCTYPE html>
3
<html b:version='2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
4
  <head><script async='async' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
5
<ins class='adsbygoogle' data-ad-client='ca-pub-4974651546853754' data-ad-slot='1491889926' style='display:inline-block;width:336px;height:280px'/>
6
<script>
7
     (adsbygoogle = window.adsbygoogle || []).push({});
8
</script>
9
​
10
    
11
    <script async='async' data-ad-client='ca-pub-4974651546853754' src='https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
12
    
13
    <!--[if IE]><script type="text/javascript" src="https://www.blogger.com/static/v1/jsbin/3382421118-ieretrofit.js"></script>
14
<![endif]-->
15
    <meta charset='utf-8'/>
16
    <meta content='IE=edge' http-equiv='X-UA-Compatible'/>
17
    <meta content='width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0' name='viewport'/>
18
    <link href='//fonts.googleapis.com/css?family=Montserrat:400,700|Arimo:400,400i,700' rel='stylesheet' type='text/css'/>
19
    <link href='//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css' rel='stylesheet'/>
20
    <b:include data='blog' name='all-head-content'/>
21
    <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
22
    <title>
23
        <b:if cond='data:blog.pageType == &quot;index&quot;'>
24
            <data:blog.pageTitle/>
25
        <b:else/>
26
            <b:if cond='data:blog.pageType != &quot;error_page&quot;'>
27
                <data:blog.pageName/> - <data:blog.title/>
28
            <b:else/>
29
                ERROR 404 - <data:blog.title/> 
30
            </b:if>
31
        </b:if>
32
    </title>
33
    <!-- Description and Keywords (start) -->
34
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
35
    <meta content='YOUR DESCRIPTION HERE' name='description'/>
36
    </b:if>
37
    <meta content='YOUR KEYWORDS HERE' name='keywords'/>
38
    <!-- Description and Keywords (end) -->
39
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
40
        <meta expr:content='data:blog.pageName' property='og:title'/>
41
        <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
42
        <meta content='article' property='og:type'/>
43
    </b:if>
44
    <b:if cond='data:blog.postImageUrl'>
45
        <meta expr:content='data:blog.postImageUrl' property='og:image'/>
46
    <b:else/>
47
    <b:if cond='data:blog.postImageThumbnailUrl'>
48
        <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
49
    </b:if></b:if>
50
    <b:if cond='data:blog.metaDescription != &quot;&quot;'>
51
        <meta expr:content='data:blog.metaDescription' name='og:description'/>
52
    </b:if>
53
    <meta expr:content='data:blog.title' property='og:site_name'/>
54
    <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
55
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
56
    <b:if cond='data:blog.postImageUrl'>
57
      <meta content='summary_large_image' name='twitter:card'/>
58
      <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
59
    <b:else/>
60
      <meta content='summary' name='twitter:card'/>
61
      <b:if cond='data:blog.postImageThumbnailUrl'>
62
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/> 
63
      </b:if>
64
    </b:if>
65
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
66
    <b:if cond='data:blog.metaDescription'>
67
      <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
68
    </b:if>
69
    <!-- Social Media meta tag need customer customization -->
70
    <meta content='Facebook App ID here' property='fb:app_id'/> 
71
    <meta content='Facebook Admin ID here' property='fb:admins'/> 
72
    <meta content='@username' name='twitter:site'/>
73
    <meta content='@username' name='twitter:creator'/>   
74
​
75
    <script type='text/javascript'>
76
      var blog = document.location.hostname.split(&quot;.&quot;);
77
      if (window.location.href.indexOf(&quot;.blogspot&quot;) &gt; -1) {
78
          if (blog[blog.length - 1] != &quot;com&quot;) {
79
              var ncr = &quot;http://&quot; + blog[0] + &quot;.blogspot.com/ncr&quot;;
80
              window.location.replace(ncr + document.location.pathname);
81
          }
82
      }
83
    </script> 
84
​
85
<b:skin><![CDATA[/
86
-----------------------------------------------
87
Blogger Template Style
88
Name:        Sora Front
89
Author :     http://www.soratemplates.com
90
License:     Premium Version
91
----------------------------------------------- */
92
​
93
/* Variable definitions
94
-----------------------
95
<Variable name="keycolor" description="Main Color" type="color" default="#1e87f0" value="#1e87f0"/>
96
<Variable name="body.background" description="Background" type="background" color="#999" default="$(color) url() repeat scroll top left" value="$(color) url() repeat scroll top left"/>
97
<Variable name="color.menu" description="Menu Background Color" type="color" default="#2A5A8E" value="#D52C1F"/>
98
<Variable name="color.theme" description="Color Theme" type="color" default="#2A5A8E" value="#D52C1F"/>
99
-----------------------
100
*/
101
a,abbr,acronym,address,applet,b,big,blockquote,body,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,h1,h2,h3,h4,h5,h6,html,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{
102
    padding:0;
103
    border:0;
104
    outline:0;
105
    vertical-align:baseline;
106
    background:0 0;
107
    margin:0
108
}
109
 ins{
110
    text-decoration:underline
111
}
112
 del{
113
    text-decoration:line-through
114
}
115
 dl,ul{
116
    list-style-position:inside;
117
    font-weight:700;
118
    list-style:none;
119
}
120
 ul li{


