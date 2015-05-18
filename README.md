# Introduction #
A very simple wrapper functions to get mp3 inforamtion from native mp3info package. Please have mp3info instatlled first.

# Steps #
* Install mp3info

> apt-get install mp3info
> npm install pilla-lib-mp3info

* Have code example to get the mp3 info

<pre><code>var mp3info = require('pilla-lib-mp3info');
mp3info(filePath, function(err, data) {
  console.log(data);
}); 
</code></pre>
