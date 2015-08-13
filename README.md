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
  $('.myDiv').croneditor({
    value: "* * * * *"
  });
});
```

<h3>License</h3>

Copyright (c) 2014 Marak Squires

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.