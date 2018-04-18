---
layout: page
title: About
description: Traing My Life
keywords: Yong Zheng
comments: true
menu: 关于
permalink: /about/
---

写给你和我：

自己尝试，自己选择吧，先尝试，再选择，认准方向后，作死地撑住，边撑边掌握平衡。

不要怕，大胆迈出第一步就好，没必要按着别人的脚印走，也没必要跑给别人看。

会摔吗？会的，而且不止摔一次。

会走错吗？当然会，一定会，而且不止走错一次。

那为什么还要走呢？

因为生命应该用来体验和发现，到死之前，我们都是需要发育的孩子。

因为尝试和选择这四个字，这是年轻的你理所应当的权利。

因为疼痛总比苍白好，总比遗憾好，总比无病申呤的平淡是真要好得多得多。

因为对年轻人而言，没有比认认真真地去“犯错”更酷更有意义的事情了。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
