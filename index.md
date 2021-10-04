# Intreduce
 ![QQ头像](https://q1.qlogo.cn/g?b=qq&nk=1764712330&s=640)
 <center>I'm 艾菲.</center>
 ---
 <div style="text-algn:center">
 <p id="hitokoto" ><a id="hitokoto_text">:D 获取中...</a></p>
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
 
 <tr>
 <td>QQ: </td>
 <td>1764712330</td>
 <td>WeChat: </td>
 <td>ooiv7oo</td>
 </tr>
 </div>
### Plan
- [ ]     ONE
- [ ]     TWO
- [ ]     THR

---
### Work


```123
这里暂时什么都没有..
```
<script>
  window.onload=function() {
     document.querySelector("head > title").innerText='AIFREE|HOMEPAGE';
     document.querySelector("body > header > h1").innerText='W e l c o m e !';
     document.querySelector("#content > footer > span").innerHTML='!wo!ow!';
   };
</script>
<style>
#content > p > img{
   display: block;
   width: 150px;
   margin-left: auto;
   margin-right: auto;
   border: 1px solid white;
   border-radius: 50%;
   height: auto;
  }
</style>
