---
layout: default
title: "HOMEPAGE"
---
<div class="menu"></div>
<div class="header">
<img src="https://q1.qlogo.cn/g?b=qq&amp;nk=1764712330&amp;s=640" alt="qq">
<div class="contact">
<center>I'm 艾菲.</center>
</div>
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
 
{% include footer.html %}