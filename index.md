<html><head><head>
<meta content="en-us" http-equiv="Content-Language">
<meta content="text/html; charset=utf-8" http-equiv="Content-Type">
<meta name="viewport" content="width=device-width, initial-scale=0.9, maximum-scale=0.9, minimum-scale=0.9, user-scalable=no" /> 
<title id="title"></title>
<script type="text/javascript">
var d = new Date()
var time = d.getHours()
if (time < 24) 
{ 
document.getElementById("title").innerHTML="晚安";
 }
 if (time < 19) 
{ 
document.getElementById("title").innerHTML="下午好";
 } 
if (time < 12)
{ 
document.getElementById("title").innerHTML="早上好";
 } 
if (time < 5) 
{
 document.getElementById("title").innerHTML="又在熬夜";
 } 
</script>
<style>
*{margin:0px; padding:0px;}
body {	text-align: center;background-image:url("http://t.cn/RJXCRdu") !important; background-size: 100% !important;background-repeat: no-repeat;background-color: #fff;}
img.smaller {	width: 18px;	height: 65px;	max-width: 25px;	animation: flipInX 3s;	-webkit-animation:  3.5s}
.logo {	font-size: 2em;	white-space: normal;	word-wrap: break-word;	text-decoration: none;	color: #fff}
#search_input {	width: 100%;	height: 40px;	background-color: transparent;	border: none;	outline: 0;	font-size: 16px;	color: #000000;}
.search_part {margin-bottom: 10px;margin-top: 40px;}
.search_bar span {	display: block;	font-size: 12px;	overflow: hidden;	padding-left: 2px;	margin-right: 42px;	vertical-align: middle;}
.search_bar span i {	display:none;	float: right;	width: 35px;	height: 40px;	background: url("http://t.cn/RXB6QDa") no-repeat center;	background-size: 16px;}
.search_bar .si {	margin: 0 38px 0 10px;} 
#suggest {	position: absolute;	left: -1px;	right: -1px;	top: 40px;	border:1px solid #ccc;	background: #fff;	line-height: 40px;}
#suggest li {	border-bottom: 1px solid #ccc;	text-align: left;	padding-left: 16px;}
#suggest li:active {	background: #F0F0F0;}
#suggest li b {	float: right;width: 44px;	height: 40px;	background: url("http://t.cn/RXgoxyz") no-repeat scroll center center #fff;	background-size: 11px;}
#suggest .close {	text-align: right;	font-size: 14px;	color: #888;	padding-right: 12px;}
.search_bar {	box-shadow: 0 0 5px rgba(70,70,40,.255);	-webkit-animation: fadeIn 2.5s;	animation: fadeIn 2.5s;
	background-color: #fff;	border-radius: 3px;	display: table;	vertical-align: middle;	width: 100%;	height: 20px;	max-width: 400px;	margin: 10px auto;	position: relative;	z-index: 10;}
#search_submit {	outline: 0;	height: 40px;	float: right;	color: #125;	font-size: 18px;	font-weight: 500;	border: none;	background-color: transparent;	padding: 0 13px 0 13px}
#content {	width: 100%;	text-align: center;	padding-top: 0px;	padding-bottom: 0px;}
.box {-webkit-animation: fadeInDown 1s;animation: fadeInDown 1s;	position: relative;	display: inline-block;width: 75px;	border: 0;}
.box a {	width: 100%;	height: 100%;	position: absolute;	left: 0;	top: 0;}
.url {	color: #232323;	height: 1.5em;	line-height: 1.5em;	width: 72px;	font-size: 0.75em;	white-space: nowrap;	overflow: hidden;	margin: auto;	-webkit-border-top-right-radius: 5px;	-webkit-border-bottom-right-radius: 5px;	text-overflow: ellipsis;	-o-text-overflow: ellipsis;-ms-text-overflow: ellipsis;padding-top: 3px;padding-bottom: 8px;}
.icon {	width: 3em;	height: 3em;	max-width: 60px;}
#yiyan {	width: 100%;	max-width: 400px;	margin: 0px auto;	text-align: center;	background-color: #fff;	padding-top: 0px;	padding-bottom: 15px;}
.shuxing { font-size: 12px;height: 30px; line-height: 20px; padding: 0 10px 0 20px;}
</style>
</script>
</head>
<body>
<br>
<br>
<br>
<br>
<iframe style="display:block;margin-left:10%;" name="weather_inc" src="http://i.tianqi.com/index.php?c=code&amp;id=2&amp;num=2" width="350" height="70" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
<br>
<div id="content">
<div class="search_part">
<form id="search_form" onsubmit="return search()" class="search_bar">
<input type="image" id="search_submit" value="" src="http://t.cn/RXNquWR"> 
<span><i id="clear" onclick="clear_seach()"></i><div class="si"><input class="search" type="text" value="" onkeyup="get_suggest()" onfocus="get_suggest()" onpaste="get_suggest()" autocomplete="off" id="search_input" placeholder="输入关键字"></div>
</span>
<div id="suggest" style="display:none">
	<ul id="suglist"></ul>
	<div class="close" onclick="close_sug()">收起</div>
</div>
</form>
</div>

<br>
 <div class="box">
<a href="folder://"></a>
<p><img class="icon" src="http://t.cn/RXaYJc0"></p>
<p class="url">书签</p>
</div>


<div class="box">
<a href="history://"></a>
<p><img class="icon" src="http://t.cn/RXaY9GH"></p>
<p class="url">足迹</p>
</div>

<div class="box">
<a href="http://t.cn/RVLKxUe"></a>
<p><img class="icon" src="http://t.cn/RXrGmR1"></p>
<p class="url">百度</p>
</div>


<div class="box">
<a href="http://t.cn/RiwZd0S"></a>
<p><img class="icon" src="http://t.cn/RXaThLY"></p>
<p class="url">热文</p>
</div>


<div class="box">
<a href="http://t.cn/"></a>
<p><img class="icon" src="http://t.cn/RXBb45E"></p>
<p class="url">微博</p>
</div>


<div class="box">
<a href="http://t.cn/R5oGTEn"></a>
<p><img class="icon" src="http://t.cn/RXaT6X1"></p>
<p class="url">导航</p>
</div>


<div class="box">
<a href="http://t.cn/RXrq5S3"></a>
<p><img class="icon" src="http://t.cn/RXaTOQT"></p>
<p class="url">翻译</p>
</div>


<div class="box">
<a href="http://t.cn/Rt19vIK"></a>
<p><img class="icon" src="http://t.cn/RXBbaUU"></p>
<p class="url">视频</p>
</div>


<div class="box">
<a href="http://t.cn/RyHMCU5"></a>
<p><img class="icon" src="http://t.cn/RXrqTwj"></p>
<p class="url">书城</p>
</div>


<div class="box">
<a href="http://t.cn/RhYWssO"></a>
<p><img class="icon" src="http://t.cn/RXrqD8L"></p>
<p class="url">菜谱</p>
</div>
<br>
<br>
<font size=?>——·❀·——</font>
<div id="yiyan">
<div class="shuxing"><script type="text/javascript" src="https://api.lwl12.com/hitokoto/main/get?encode=js&amp;charset=utf-8"></script><div id="lwlhitokoto"><script>lwlhitokoto()</script>是故当知，世皆无常，会必有离，勿怀忧恼，世相如是。当勤精进，早求解脱；以智慧明，灭诸痴暗。</div>
</div>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<font size=?>今日美图</font>
<img src="https://api.i-meto.com/bing?new" height="250" width="100%">
<div class="shuxing">
<a href="http://t.cn/RXrAeGY" style="color:#232323">课表</a>
<a href="http://t.cn/RXr2EVG" style="color:#232323">     安全教育</a>
<a href="http://t.cn/RXNtiIi" style="color:#232323">      德育网</a>
<a href="http://t.cn/RVzxfte" style="color:#232323">       订阅</a>
<a href="http://t.cn/RXrLNYw" style="color:#232323">      解析视频</a>
<a href="http://t.cn/RJ7ATU5" style="color:#232323">       度盘</a>
</div>
<script type="text/javascript">
var last_kw = '';
var max_sug_len = 1; //搜索建议最短触发长度

/*获取搜索建议
采用的神马搜索的服务
*/
function get_suggest() {
	var kw = document.getElementById('search_input').value;
	var clear = document.getElementById('clear');
	if (kw) clear.style.display = 'block';
	else clear.style.display = 'none';
	if (kw == last_kw) return;
	last_kw = kw;
	if (!kw || kw.length < max_sug_len) {
		close_sug();
		return;
	}
	var script = document.createElement('script');
	script.type = 'text/javascript';
	script.src = 'http://sugs.m.sm.cn/web?t=w&uc_param_str=dnnwnt&scheme=http&fr=android&bid=1&q=' + encodeURIComponent(kw) + '&_=' + new Date().getTime() + '&callback=jsonp3';
	var head = document.querySelector('head');
	script.onload = function() {
      head.removeChild(script);
	};
	head.appendChild(script);
}
function jsonp3(res) {
	var suggest = document.getElementById('suggest');
	if (!res.r || !res.r.length) {
		suggest.style.display = 'none';
		return;
	}
	var html = '';
	res.r.forEach(function(v) {
		html += '<li>' + v.w + '<b></b></li>';
	});
	document.getElementById('suglist').innerHTML = html;
	suggest.style.display = 'block';
}
function close_sug() {
	last_kw = '';
	document.getElementById('suggest').style.display = 'none';
}
function move_input() {
	document.body.scrollTop = document.getElementById('search_form').offsetTop - 2;
}
function clear_seach() {
	var input = document.getElementById('search_input');
	input.value = '';
	document.getElementById('clear').style.display = 'none';
	close_sug();
	input.focus();
}
function search(){if(document.getElementById("search_input").value != ""){
//window.location.href = "http://m.baidu.com/s?ie=utf-8&rn=30&tn=baiduhome_pg&oq=%E5%BC%A0%E7%B1%BD%E6%B2%90&rsv_enter=0&wd=" + encodeURIComponent(document.getElementById("search_input").value);
window.location.href = "https://m.baidu.com/from=smor/s?word=" + encodeURIComponent(document.getElementById("search_input").value) + "&from=smor&safe=1&snum=1";
document.getElementById("search_input").value = "";}return false;}

document.getElementById('suglist').addEventListener('click', function(e) {
	var input = document.getElementById('search_input');
	if (e.target.tagName == 'B') {
		input.value = e.target.parentNode.firstChild.textContent;
		input.focus();
	} else if (e.target.tagName == 'LI') {
		input.value = e.target.firstChild.textContent;
		close_sug();
		search();
	}
});
window.addEventListener('resize', move_input);
</script>
</body>
</head></html>
；
