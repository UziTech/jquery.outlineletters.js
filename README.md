# outline letters jquery plugin
#### Copyright (c) 2013 Tony Brix http://tonybrix.info
#### MIT Licensed: http://www.opensource.org/licenses/mit-license.php

A jQuery Plugin that outlines letters in a paragraph. Tested on jquery v 1.2.3 and up

## DEMO:
http://uzitech.com/files/outlineletters.php
## OPTIONS:
color: outline color. default: '#888'

size: outline width in px. default: 1 (I recommend not going higher than 5)

round: round corners when size &gt; 1. default: true

useTextShadow: uses css3 property "text-shadow" if browser supports it. default: true
## USAGE:
<pre>
$("#ol1").outlineLetters({color: '#0ff', size: 2});
$("#ol2").outlineLetters({color: '#0ff'});
$("#ol3").outlineLetters({size: 5});
$("#ol4").outlineLetters({size: 5, useTextShadow: false});
$("#ol5").outlineLetters({size: 5, round: false});
$("#ol6").outlineLetters();
</pre>
