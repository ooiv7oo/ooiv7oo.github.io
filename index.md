---
layout: default
title: "HOMEPAGE"
---

<div class="menu">oo</div>
<div class="header">
 <img src="https://q1.qlogo.cn/g?b=qq&nk=1764712330&s=640" />
<center>I'm 艾菲.</center>
<div class="contact"></div>
</div>
<div class="main">
<div id="hitokoto"><p id="hitokoto_text">一直在追求极致的精彩</p></div>
 <script>
  var xhr = new XMLHttpRequest();
  xhr.open('get', 'https://v1.hitokoto.cn');
  xhr.onreadystatechange = function () {
    if (xhr.readyState === 4) {
      var data = JSON.parse(xhr.responseText);
      var hitokoto = document.getElementById('hitokoto_text');
      hitokoto.innerText = data.hitokoto;
    }
  }
  xhr.send();
</script>
</div>
 
<footer>
<a href="https://dash.cloudflare.com" target="_blank" rel="nofollow"><img src="https://cdn.jsdelivr.net/gh/ooiv7oo/ling@gh-pages/assets/images/CloudFlare.png" style="width:5.58rem;"></a>
┊
<a href="https://github.com" target="_blank" rel="nofollow"><img src="https://cdn.jsdelivr.net/gh/ooiv7oo/ling@gh-pages/assets/images/GitHub.png" style="width:3rem;"></a>
</footer>
