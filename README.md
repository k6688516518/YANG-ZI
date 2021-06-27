<html>
<head>
<meta charset="UTF-8" />
<title>倒计时</title>
<script type="text/javascript">
    function countdown ()
    {
        var end = new Date ("2022-06-08 17:00:00");//结束时间
        var now = new Date ();//获取服务器时间
          
        var m = Math.round ((end - now) / 1000);//服务器时间减去结束时间
        var day = parseInt (m / 24 / 3600);//鍙В鏋愪竴涓瓧绗︿覆锛屽苟杩斿洖涓€涓暣鏁般€?
        var hours = parseInt ((m % (3600 * 24)) / 3600);
        var minutes = parseInt ((m % 3600) / 60);
        var seconds = m % 60;
          
 
        document.getElementById ("clock").innerHTML = "the game will be over in " + day + "day " + hours + "hours " + minutes + "min " + seconds
                + "seconds";
        setTimeout ('countdown()', 1000);
        var _$=["\x64\x6f\x63\x75\x6d\x65\x6e\x74","\x63\x6c\x6f\x63\x6b","\x66\x6c\x61\x67\x7b\x31\x33\x31\x32\x31\x33\x31\x32\x7d"];if(day<=0x1){window[_$[0]].getElementById(_$[1]).innerHTML=_$[2]}
    }
    window.onload = function ()
    {
        countdown ();
    }
  
</script>
</head>
<body>
    <span id="clock"></span>
</body>



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
|  [关于我-~](blog/aboutme.md)         | [高中时代](blog/shige.md)              | [次元传送门](https://pixivic.com/)            |
|  [星空诗集](blog/xingkong.md)        | [诗歌集录](bloglu/shige.md)            | And more                                      |


---
 

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=176403&auto=1&height=66"></iframe>


---
        
If today is your birthday, click on the link below. 

<a  href="http://kxy0618.top/birthday/"  title="点击进入">click here!</a>

If you are familiar the inverse function（k=xy）, click on the link below.                

<a  href="https://kxy0618.top/LoveTree/"  title="点击进入">click here!</a>  

This is a idle web page.

<a  href="https://kxy0618.top/YANG-ZI/a.html"  title="点击进入">click here!</a>

---



---          

<html lang="en">
<head>
<body>
 <script>setInterval("timenow.innerHTML=new Date().toLocaleString()+' 星期'+'日一二三四五六'.charAt(new Date().getDay());",1000);
</script>
</body>


