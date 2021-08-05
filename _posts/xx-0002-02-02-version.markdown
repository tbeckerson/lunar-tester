---
layout: post-transp-bg
title: version info
bg-img: bg-02
bg-transp: 210,40%,80%,0.8
tx-color: dark-gray
bg-attach: fixed
---

_what programs go here? the system level programs (kernel, gcc, etc) or user level applications (web browsers, music players, etc).
Would a list of user level applications be more useful? Both?_

_More importantly, are version numbers a worthwhile to put on the site? Do people care about the version number? This will need constant revision, is it work we actually want to do?_

_sample text below:_

**Lunar uses up-to-date versions of software, without risking stability.**

{% for item in site.data.versions %}
    {{ item.name }} : {{ item.version }}
{% endfor %}
