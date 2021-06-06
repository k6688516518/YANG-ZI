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

<a href="{{ site.url }}/feed.xml">RSS订阅</a> 

|      博客链接                        |      日志链接                          |          网站链接                             |
| :------:                            |    :----:                             |  :----------:                                |
|  [about me](blog/aboutme.md)        | [highschool years](blog/shige.md)     | [Two dimensions door](https://pixivic.com/)  |
| [Starry poem](blog/xingkong.md)     | [Poetry excerpt](bloglu/shige.md)     | And more                                     |


---
 
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=1451720450&auto=1&height=66"></iframe> 
 
---
        
If today is your birthday, click on the link below. 

<a  href="http://kxy0618.top/birthday/"  title="点击进入">click here!</a>

If you are familiar the inverse function（k=xy）, click on the link below.                

<a  href="https://kxy0618.top/LoveTree/"  title="点击进入">click here!</a>  

This is a idle web page.

<a  href="https://kxy0618.top/YANG-ZI/a.html"  title="点击进入">click here!</a>

---

---
layout: default
title: Blog
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

---          

<html lang="en">
<head>
<body>
 <script>setInterval("timenow.innerHTML=new Date().toLocaleString()+' 星期'+'日一二三四五六'.charAt(new Date().getDay());",1000);
</script>
</body>


