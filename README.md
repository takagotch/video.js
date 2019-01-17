### video.js
---
https://github.com/videojs/video.js

```js
var player = videojs('my-player');

var player = videojs('my-player', options, function onPlayerReady(){
  videojs.log('Your player is ready!');
  this.play();
  this.on('ended', function(){
    videojs.log('Awww...');
  });
});

window.HELP_IMPROVE_VIDEOJS = false;


```

```
<video
  id="my-player"
  class="video-js"
  controls
  preload="auto"
  poster="//vjs.zencdn.net/v/oceans.png"
  data-setup='{}'>
  <source src="//vjs.zencdn.net/v/oceans.mp4" type="video/mp4"></source>
  <source src="//vjs.zencdn.net/v/oceans.webm" type="video/webm"></source>
  <source src="//vjs.zencdn.net/v/oceans.ogv" type="video/ogg"></source>
  <p class="vjs-no-js">
    text
    <a href="http://videojs.com/html5-video-support/" target="_blank">
      supports HTML5 video
    </a>
  </p>
</video>
```

```
```

