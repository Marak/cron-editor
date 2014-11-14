<h1>Visual Cron Editor</h1>

A jQuery plugin which creates a visual editor for [Cron Jobs](http://en.wikipedia.org/wiki/Cron).

<h2><a href="http://marak.com/cron-editor/">Live Demo</a></h2>

<img src="http://i.imgur.com/eakjYL3.png"></img>

The cron format supports seconds. If your cron editor doesn't support seconds you can ignore this parameters.


<h3>Example Code</h3>

``` js
// be sure to include all required files ( see index.html file )
$(document).ready(function(){
  // turn the div into a cron editor
  $('.myDiv').croneditor();
});
```

<h3>License</h3>
MIT