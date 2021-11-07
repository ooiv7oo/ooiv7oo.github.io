---
layout: default
title: "HOMEPAGE"
---

<div class="header">
    <div class="tx">
      <img src="https://q1.qlogo.cn/g?b=qq&amp;nk=1764712330&amp;s=640" alt="qq">
    </div>
    <div class="contact">
      <p>I'm 艾菲.</p>
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