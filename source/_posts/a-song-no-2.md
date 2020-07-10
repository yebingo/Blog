---
title: A Song No.2
date: 2020-06-04 17:41:00
index_img: /img/earphone.jpg
tags:
---

## 迷宫
> 《迷宫》是王若琳演唱的一首歌，收录于王若琳2008年发行的专辑《Start From Here》中，歌词似乎描绘了刚相识的情侣即将要在一起，对爱情未来的不确定性抱有惊喜，心怀期待。整个作品似乎有一种慵懒、颓废的曲风，相信这也是你比较喜欢的一首歌吧

<div id="aplayer" style="margin: 20px 0;"></div>

看着你看窗外

瞧瞧变红的夜

轻轻的你的手

又握紧了一些

该不该让你到我的世界

let's start from here

无所谓慢慢来

迷宫一样的未来

转一个圈会到哪里

我喜欢爱情有点神秘

i don't care where we go

let's start from here

陪着我喝咖啡

爱在空气里

暖暖的是你的笑

赶走心情的灰

我想我不在意你曾爱过谁

let's start from here

无所谓就算爱

像空沙发在等待

拥抱着是不确定

我喜欢爱情多点惊喜

i don't care where we go

let's start from here

let's start from here

爱一个人怎么开始啊

像街上走过那些人们

转一个弯预见美好

start from here

无所谓慢慢来

迷宫一样的未来

转一个圈会到哪里

我喜欢爱情有点神秘

无所谓就算爱

像空沙发在等待

拥抱着是不确定

我喜欢爱情多点惊喜

i don't care where we go

let's start from here

let's start from here

let's start from here

let's start from here

<style>
@import url('//cdn.staticfile.org/aplayer/1.10.1/APlayer.min.css')
</style>
<script src="//cdn.staticfile.org/aplayer/1.10.1/APlayer.min.js" defer></script>
<script type="text/javascript">
  var oldLoadAp = window.onload;
  window.onload = function () {
    oldLoadAp && oldLoadAp();

    new APlayer({
      container: document.getElementById('aplayer'),
      autoplay: false,
      audio: { name: '迷宫', artist: '王若琳', url: '/song/2.mp3', cover: '/img/wangruolin.jpg', }
    });
  }
</script>