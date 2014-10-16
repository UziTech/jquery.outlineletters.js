# Outline letters jquery plugin
#### Copyright (c) 2014 Tony Brix http://tonybrix.info
#### MIT Licensed: http://www.opensource.org/licenses/mit-license.php

A jQuery Plugin that outlines letters in a paragraph. Tested on jquery v 1.2.3 and up

## Demo
http://uzitech.com/files/outlineletters.php
## Options
color: outline color. default: '#888'

size: outline width in px. default: 1

round: round corners when size &gt; 1. default: true

useTextShadow: uses css3 property "text-shadow" if browser supports it. default: true
## Examples

### Basic
<p id="example1"></p>
``` javascript
$("#example1").outlineLetters();
```
### Color
<p id="example2"></p>
``` javascript
$("#example2").outlineLetters({color: '#0ff'});
```
### Size
<p id="example3"></p>
``` javascript
$("#example3").outlineLetters({size: 5});
```
### Color & Size
<p id="example4"></p>
``` javascript
$("#example4").outlineLetters({color: '#0ff', size: 2});
```
### No text shadow
<p id="example5"></p>
``` javascript
$("#example5").outlineLetters({size: 5, useTextShadow: false});
```
### Round
<p id="example6"></p>
``` javascript
$("#example6").outlineLetters({size: 5, round: false});
```
