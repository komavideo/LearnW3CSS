在面板里玩耍
========

## 知识点

* w3-panel

### w3-panel（面板）

页面中的功能区域，例如：登陆区或信息显示区。

## 综合例

~~~html
<div class="w3-panel w3-indigo w3-card-4">
    <h3>我爱NBA。</h3>
    <p>今年的全明星很好看，特别是3分大赛，火箭的戈登赢了骑士的欧文。</p>
</div>
<div class="w3-panel w3-sand w3-leftbar w3-xlarge">
    <p><i>"W3.css不难，起码不比Boostrap难。"</i></p>
</div>
<div class="w3-container">
    <button class="w3-btn w3-blue" onclick="document.getElementById('id01').style.display='block'">其他爱好</button>
</div>
<div id="id01" class="w3-panel w3-green w3-round-xlarge" style="display:none">
    <span  class="w3-closebtn" onclick="this.parentElement.style.display='none'">X</span>
    <p>我也爱英超，嘿嘿！</p>
</div>
~~~

## 课程文件

* https://git.oschina.net/komavideo/LearnW3CSS

## 小马视频频道

http://i.youku.com/komavideo
https://www.youtube.com/c/小马视频