---
title: A Song No.1
date: 2020-06-30 17:21:27
index_img: /img/cd.jpg
tags:
---

## 一首简单的歌
> 这是王力宏在2004年发表的一首歌曲，第一次听觉得很普通，但是慢慢的，歌词让我体会到对待爱情的那份克制、简单、深情，让我触动，让我不由自主想把这些词，说给你听。

<div id="aplayer" style="margin: 20px 0;"></div>

这世界很复杂,

混淆我想说的话

我不懂,

太复杂的文法

什么样的礼物

能够永远记得住

让幸福别走的太仓促

云和天,蝶和花

从来不需要说话

断不了依然日夜牵挂

唱情歌,说情话

只想让你听清楚

我爱你是唯一的倾诉

写一首简单的歌,

让你的心情快乐

爱情就像一条河

难免会碰到波折

这一首简单的歌,

并没有什么独特

好像我

那么的平凡却又深刻

我一直在思考

让你了解我的好

却忘了

常常对你微笑

失去的忘记的

我会尽力去弥补

你是我最珍贵的财富

简单的歌

好像我

那么的平凡却又

深刻

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
      audio: { name: '一首简单的歌', artist: '王力宏', url: '/song/1.mp3', cover: '/img/wanglihong.jpg', }
    });
  }
</script>
