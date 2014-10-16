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
<div id="example1"></div>
``` javascript
$("#example1").outlineLetters();
```
### Color
<div id="example2"></div>
``` javascript
$("#example2").outlineLetters({color: '#0ff'});
```
### Size
<div id="example3"></div>
``` javascript
$("#example3").outlineLetters({size: 5});
```
### Color & Size
<div id="example4"></div>
``` javascript
$("#example4").outlineLetters({color: '#0ff', size: 2});
```
### No text shadow
<div id="example5"></div>
``` javascript
$("#example5").outlineLetters({size: 5, useTextShadow: false});
```
### Round
<div id="example6"></div>
``` javascript
$("#example6").outlineLetters({size: 5, round: false});
```
