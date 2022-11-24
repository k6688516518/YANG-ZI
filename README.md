<script type="text/javascript">
/* 鼠标特效 */
var a_idx = 0;
jQuery(document).ready(function($) {
    $("body").click(function(e) {
        var a = new Array("❤郑恩地❤","❤李知恩❤","❤金泰妍❤","❤希望天空❤","❤除了春天、爱情和樱花❤","❤why❤","❤少女的少年❤","❤palette❤","❤rain❤","❤夜信❤","❤blueming❤","❤离别初体验❤");
        var $i = $("<span></span>").text(a[a_idx]);
        a_idx = (a_idx + 1) % a.length;
        var x = e.pageX,
        y = e.pageY;
        $i.css({
            "z-index": 999999999999999999999999999999999999999999999999999999999999999999999,
            "top": y - 20,
            "left": x,
            "position": "absolute",
            "font-weight": "bold",
            "color": "rgb("+~~(255*Math.random())+","+~~(255*Math.random())+","+~~(255*Math.random())+")"
        });
        $("body").append($i);
        $i.animate({
            "top": y - 180,
            "opacity": 0
        },
        3000,
        function() {
            $i.remove();
        });
    });
});
</script>


<div id="timenow"></div>  



![image](https://user-images.githubusercontent.com/59243825/120888313-3381c200-c62a-11eb-9e45-b2ff01143f33.png)

``醉后不知天在水,满船清梦压星河。
                ——《题龙阳县青草湖》唐珙``

![image](https://user-images.githubusercontent.com/59243825/120889958-6c259980-c632-11eb-92ee-42495afe3622.png)

``明月皎皎照我床，星汉西流夜未央。
                ——《燕歌行二首·其一》曹丕``

![image](https://user-images.githubusercontent.com/59243825/120913278-85792500-c6c8-11eb-8832-3e1f2e761648.png)

``似此星辰非昨夜，为谁风露立中宵。
               ——《绮怀》黄景仁``

---



|      博客链接                        |      日志链接                          |          网站链接                             |
| :------:                             |    :----:                             |  :----------:                                 |
|  [笔者简介](blog/aboutme.md)         | [高中时代](blog/shige.md)              | [次元传送门](https://pixivic.com/)            |
|  [星空诗集](blog/xingkong.md)        | [诗歌集录](bloglu/shige.md)            | And more                                      |


---


<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=3986241&auto=1&height=66"></iframe>

---
        
If today is your birthday, click on the link below. 

<a  href="https://k6688516518.github.io/birthday/"  title="点击进入">click here!</a>

If you are familiar the inverse function（k=xy）, click on the link below.                

<a  href="https://"  title="点击进入">click here!</a>  

This is a idle web page.

<a  href="https://kxy0618.top/a.html"  title="点击进入">click here!</a>

---

------

---          

<html lang="en">
<head>
<body>
 <script>setInterval("timenow.innerHTML=new Date().toLocaleString()+' 星期'+'日一二三四五六'.charAt(new Date().getDay());",1000);
</script>
</body>

    
