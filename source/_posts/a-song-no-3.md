---
title: A Song No.3
date: 2020-06-09 16:44:28
index_img: /img/cdplayer.jpg
tags:
---

## 你快回来
> 《你快回来》是孙楠演唱的一首歌曲，收录于孙楠1999年发行的专辑《南极光》中，而且，他还是电视剧《永不瞑目》的片尾曲，这首歌是你不在身边想你时耳边不自觉响起的一首歌，歌曲的词，以及副歌部分孙楠充沛的情感很好地把一个思念者的心情表达了出来。

<div id="aplayer" style="margin: 20px 0;"></div>

没有你 世界寸步难行

我困在原地 任回忆凝积

黑夜里 祈求黎明快来临

只有你 给我温暖晨曦

走到思念的尽头

我终于相信

没有你的世界

爱都无法给予

忧伤反复纠缠

我无法躲闪

心中有个声音总在呼喊

你快回来

我一人承受不来

你快回来

生命因你而精彩

你快回来

把我的思念带回来

别让我的心 空如大海

没有你 世界寸步难行

我困在原地 任回忆凝积

黑夜里 祈求黎明快来临

只有你 给我温暖晨曦

走到思念的尽头

我终于相信

没有你的世界

爱都无法给予

忧伤反复纠缠

我无法躲闪

心中有个声音总在呼喊

你快回来

我一人承受不来

你快回来

生命因你而精彩

你快回来

把我的思念带回来

别让我的心 空如大海

你快回来

我一人承受不来

你快回来

生命因你而精彩

你快回来

把我的思念带回来

别让我的心 空如大海

别让我的心 空如大海

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
      audio: { name: '你快回来', artist: '孙楠', url: '/song/3.mp3', cover: '/img/sunnan.jpg', }
    });
  }
</script>
