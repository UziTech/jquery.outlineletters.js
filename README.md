# outline letters jquery plugin
#### Copyright (c) 2013 Tony Brix http://tonybrix.info
#### MIT Licensed: http://www.opensource.org/licenses/mit-license.php

This is a jQuery Plugin that outlines letters in a paragraph. Tested on jquery v 1.2.3 and up

## DEMO:
http://uzitech.com/files/outlineletters.php
## OPTIONS:
color: outline color. default: '#888'
size: outline width in px. default: 1 (I recommend not going higher than 5)
round: round corners when size &gt; 1. default: true
useTextShadow: uses css3 property "text-shadow" if browser supports it. default: true
## USAGE: 
&lt;!DOCTYPE html&gt;
&lt;html&gt;
 &lt;head&gt;
  &lt;title&gt;OutlineLetters Demo&lt;/title&gt;
  &lt;script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.2.3/jquery.min.js"&gt;&lt;/script&gt;
  &lt;script type="text/javascript" src="http://www.uzitech.com/files/jquery-outline-1.5.js"&gt;&lt;/script&gt;
  &lt;script type="text/javascript"&gt;
   $(document).ready(function(){	
    $("#ol1").outlineLetters({color: '#0ff', size: 2});
    $("#ol2").outlineLetters({color: '#0ff'});
    $("#ol3").outlineLetters({size: 5});
    $("#ol4").outlineLetters({size: 5, useTextShadow: false});
    $("#ol5").outlineLetters({size: 5, round: false});
    $("#ol6").outlineLetters();
   });
  &lt;/script&gt;
 &lt;/head&gt;
 &lt;body&gt;
  &lt;div id="ol1" style="color: #f00;"&gt;outline letters 1&lt;/div&gt;
  &lt;br/&gt;
  &lt;div id="ol2" style="color: #f00;"&gt;outline letters 2&lt;/div&gt;
  &lt;br/&gt;
  &lt;div id="ol3" style="color: #0f0;"&gt;outline letters 3&lt;/div&gt;
  &lt;br/&gt;
  &lt;div id="ol4" style="color: #0f0;"&gt;outline letters 4&lt;/div&gt;
  &lt;br/&gt;
  &lt;div id="ol5" style="color: #0f0;"&gt;outline letters 5&lt;/div&gt;
  &lt;br/&gt;
  &lt;div id="ol6" style="color: #00f;"&gt;outline letters 6&lt;/div&gt;
  &lt;br/&gt;
 &lt;/body&gt;
&lt;/html&gt;
