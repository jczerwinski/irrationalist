---
title: Alberta Population Pyramid
author: jam
date: 2014-02-03 19:41
template: article.jade
---
Alberta's population by age group, gender, and year.
<span class="more"></span>

<div style="margin-right: max-width: 100%; auto; margin-left: auto; text-align: center" id="PopulationPyramid"></div>
<div id="PopulationPyramidAlt">Sorry, your viewport is too small to view this animation</div>
<script src="http://cdnjs.cloudflare.com/ajax/libs/d3/3.3.9/d3.js"></script>
<script src="/articles/alberta-population-pyramid/alberta.js"></script>
<script src="http://code.jquery.com/jquery-1.9.1.js"></script>
<script src="http://code.jquery.com/ui/1.10.3/jquery-ui.js"></script>
<script src="/articles/alberta-population-pyramid/d3populationpyramid.js"></script>
<style>
@media  (max-width: 850px) {
	#PopulationPyramid {
		display: none;
	}
	#PopulationPyramidAlt {
		display: block;
	}
}
@media(min-width: 851px) {
	#PopulationPyramid {
		display: inline-block;
	}
	#PopulationPyramidAlt {
		display: none;
	}
}
</style>
<link rel="stylesheet" href="http://code.jquery.com/ui/1.10.3/themes/smoothness/jquery-ui.css">
<script>
	var pyramid = new PeoplePyramid(data, 'PopulationPyramid', 'K');
</script>

A couple of observations. First, from 1975 until recently, its been all about the Baby Boomers. They have really dominated demographically.

But look at the last few years. Alberta attracts a lot of workers, most of whom are relatively young. As of 2012, 25-35 year olds outnumber 45-55 year olds.

Times have changed.