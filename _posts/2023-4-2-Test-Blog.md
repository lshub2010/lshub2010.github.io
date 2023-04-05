---
layout: post
title: 第一篇博客
description: >
  这是我的第一篇文章，同时也是一篇测试文章
tags: [blog]
---

## 你好！
欢迎来到我的博客
你可以在这里查看有关于我的信息
如果可以的话来评论哦！

<script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
<script>
    var jsonModel = [
    "https://unpkg.com/live2d-widget-model-miku@1.0.5/assets/miku.model.json",// 初音
    "https://unpkg.com/live2d-widget-model-shizuku@1.0.5/assets/shizuku.model.json",// 萌娘
    "https://unpkg.com/live2d-widget-model-koharu@1.0.5/assets/koharu.model.json",// 小可爱（女）
    "https://unpkg.com/live2d-widget-model-haruto@1.0.5/assets/haruto.model.json",// 小可爱（男）
    "https://unpkg.com/live2d-widget-model-chitose@1.0.5/assets/chitose.model.json",// 小帅哥
    ];
    L2Dwidget.init({ 
        "model": { 
            "jsonPath": jsonModel[Math.floor(Math.random()*(jsonModel.length-1))],
            "scale": 1 
        }, 
        "display": { 
            "position": "left", // 位置left、right
            "width": 66, // 宽度
            "height": 90, // 高度
            "hOffset": 10, // 横向边距
            "vOffset": 0 // 众向边距
        }, 
        "mobile": { 
            "show": false // 手机是否显示
        },
    });
</script>

<!-- 来必力City版安装代码 -->
<div id="lv-container" data-id="city" data-uid="MTAyMC81ODMwNi8zNDc2OQ==">
<script type="text/javascript">
   (function(d, s) {
       var j, e = d.getElementsByTagName(s)[0];

       if (typeof LivereTower === 'function') { return; }

       j = d.createElement(s);
       j.src = 'https://cdn-city.livere.com/js/embed.dist.js';
       j.async = true;

       e.parentNode.insertBefore(j, e);
   })(document, 'script');
</script>
<noscript>为正常使用来必力评论功能请激活JavaScript</noscript>
</div>
<!-- City版安装代码已完成 -->
