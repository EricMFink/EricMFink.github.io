---
layout: page
permalink: /music/
title: Music
---

#### [Tired & Hungry & Looking For My Youth]({{ site.baseurl}}/music/TiredAndHungry)

<a href="{{ site.baseurl}}/music/TiredAndHungry"><img src="{{ site.baseurl}}/assets/music/TiredAndHungry/cover.png" alt="" width="320"/></a>

<a href='{{ site.baseurl }}/assets//music/TiredAndHungry.zip' download="">
<button class="large"><i class="fa fa-download"></i> </button>
</a>

<ul>
{% for song in site.data.songs.TiredAndHungry %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

#### [A Promise With A Catch]({{ site.baseurl}}/music/PromiseWithACatch)

<a href="{{ site.baseurl}}/music/PromiseWithACatch"><img src="{{ site.baseurl}}/assets/music/PromiseWithACatch/cover.png" alt="" width="320"/></a>

<a href='{{ site.baseurl }}/assets//music/PromiseWithACatch.zip' download="">
<button class="large"><i class="fa fa-download"></i> </button>
</a>

<ul>
{% for song in site.data.songs.PromiseWithACatch %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

#### [Revolutionary Anthems, Labor Hymns, & Sectarian Satire]({{ site.baseurl}}/music/RevolutionaryAnthems)

<a href="{{ site.baseurl}}/music/RevolutionaryAnthems"><img src="{{ site.baseurl}}/assets/music/RevolutionaryAnthems/cover.png" alt="" width="320"/></a>

<a href='{{ site.baseurl }}/assets//music/RevolutionaryAnthems.zip' download="">
<button class="large"><i class="fa fa-download"></i> </button>
</a>

<ul>
{% for song in site.data.songs.RevolutionaryAnthems %}<li><a href="{{ site.baseurl}}/music/{{ song.file }}">{{ song.title }}</a></li>{% endfor %}
</ul>

