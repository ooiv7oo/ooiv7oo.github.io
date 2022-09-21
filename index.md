---
layout: default
title: "HOMEPAGE"
---

<div class="header">
    <div class="tx">
      <img src="./assets/images/Avatar.png" alt="qq头像">
    </div>
    <div class="contact">
      <p>I'm 艾菲.</p>
    </div>
</div>
<div class="content">
    <div class="introduce">
        <a href="/">1</a>
        <a href="/">2</a>
        <a href="/">3</a>
        <a href="/">4</a>
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
      <div></div>
      <div></div>
      <div></div>
    </div>
</div>
