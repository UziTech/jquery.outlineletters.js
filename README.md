# Outline letters jquery plugin
#### Copyright (c) 2014 Tony Brix http://tonybrix.info
#### MIT Licensed: http://www.opensource.org/licenses/mit-license.php

A jQuery Plugin that outlines letters in a paragraph. Tested on jquery v 1.2.3 and up

## Options
color: outline color. default: '#888'

size: outline width in px. default: 1

round: round corners when size &gt; 1. default: true

useTextShadow: uses css3 property "text-shadow" if browser supports it. default: true
## Examples

### Basic

<p id="example1"></p>

![Example 1](http://uzitech.github.io/images/example1.png)

``` html
<p id="example1" style="color: #00f">Example 1</p>
<script>
  $("#example1").outlineLetters();
</script>
```

### Color

<p id="example2"></p>

![Example 2](http://uzitech.github.io/images/example2.png)

``` html
<p id="example2" style="color: #f00">Example 2</p>
<script>
  $("#example2").outlineLetters({color: '#0ff'});
</script>
```

### Size

<p id="example3"></p>

![Example 3](http://uzitech.github.io/images/example3.png)

``` html
<p id="example3" style="color: #0f0">Example 3</p>
<script>
  $("#example3").outlineLetters({size: 5});
</script>
```

### Color & Size

<p id="example4"></p>

![Example 4](http://uzitech.github.io/images/example4.png)

``` html
<p id="example4" style="color: #f00">Example 4</p>
<script>
  $("#example4").outlineLetters({color: '#0ff', size: 2});
</script>
```

### No text shadow

<p id="example5"></p>

![Example 5](http://uzitech.github.io/images/example5.png)

``` html
<p id="example5" style="color: #0f0">Example 5</p>
<script>
  $("#example5").outlineLetters({size: 5, useTextShadow: false});
</script>
```

### No Round

<p id="example6"></p>

![Example 6](http://uzitech.github.io/images/example6.png)

``` html
<p id="example6" style="color: #0f0">Example 6</p>
<script>
  $("#example6").outlineLetters({size: 5, round: false});
</script>
```
