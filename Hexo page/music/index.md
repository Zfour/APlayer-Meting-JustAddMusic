---

title: 音乐收藏
date: 2020-08-24 18:24:04
aplayer: true

---
<h2> 我的音乐收藏 </h2>  
<h4> 2016-04-27 创建</h4>  
<p class="colormusictitle">最近在听的歌。</p>
<!--<buttom type="button" class="btn-beautify button--animated outline black" id="musicvisualchange"   style="cursor:pointer" onclick="musicvisualchange()"><i class="far fa-hand-point-right fa-fw"></i>隐藏可视化</buttom>
-->


<link rel="stylesheet" href="/APlayer-Meting-JustAddMusic/css/APlayer.min.css"/> 
<link rel="stylesheet" href="/APlayer-Meting-JustAddMusic/css/justaddmusic.css"/> 


{% meting "5249407673" "netease"  "playlist" "order:random"  %}



<br>

<div class="musiccontainer" id="container" style="position: fixed; right:0; bottom:0;"></div>
<buttom class="btn-beautify button--animated outline black" id="musicvisualchange"   style="cursor:pointer" onclick="musicvisualchange()"><i class="fas fa-eye-slash fa-fw"></i>HIDE</buttom>
	
{% btn 'https://music.163.com/#/playlist?id=370673384&userid=270622912',网易云歌单,far fa-hand-point-right,outline red  %}
<script src="/APlayer-Meting-JustAddMusic/js/jquary.js"></script>
<script src="/APlayer-Meting-JustAddMusic/js/APlayer.min.jam.js"></script>
<script src="/APlayer-Meting-JustAddMusic/js/Meting.min.js"></script>
<script src="/APlayer-Meting-JustAddMusic/js/JustAddMusic.js"></script>
<script  src="/APlayer-Meting-JustAddMusic/js/jamsetting.js"></script>
<script  src="/APlayer-Meting-JustAddMusic/js/visualupper.js"></script>
<script  src="/APlayer-Meting-JustAddMusic/js/visualchanger.js"></script>