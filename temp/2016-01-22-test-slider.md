---
layout: post
title: slider test
description: "Slider Test"
modified: 2016-01-22
tags: [slider,test]
image:
  feature:
  credit:
  creditlink: 
---
<link href="{{ site.url }}/assets/css/twentytwenty.css" rel="stylesheet" type="text/css" />

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js"></script>
<script src="{{ site.url }}/assets/js/jquery.event.move.js" type="text/javascript"></script>
<script src="{{ site.url }}/assets/js/jquery.twentytwenty.js" type="text/javascript"></script>

<script>
    $(window).load(function(){
      $(".twentytwenty-container[data-orientation!='vertical']").twentytwenty({default_offset_pct: 0.7});
      $(".twentytwenty-container[data-orientation='vertical']").twentytwenty({default_offset_pct: 0.3, orientation: 'vertical'});
    });
</script>

Slider test

<div class="twentytwenty-container">
	<img src="{{ site.url }}/images/test_1.png" />
	<img src="{{ site.url }}/images/test_2.png" />
</div>

just 2 images:

<img src="{{ site.url }}/images/test_1.png" />
<img src="{{ site.url }}/images/test_2.png" />

End of post


