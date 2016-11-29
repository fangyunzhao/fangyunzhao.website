---
layout: home
title: Home
landing-title: Olivia Zhao
description: 
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Past Projects</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Something about Me</h2>
		</header>
		<p>Hello! I am currently a undergraduate student in University of Wisconsin-Madison, studying psychology and statistics. </p>
		<ul class="actions">
			<li><a href="landing.html" class="button next">More About Me</a></li>
		</ul>
	</div>
</section>

</div>

