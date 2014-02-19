# Media Experiments

A random collection of useless experiments with HTML5 media elements.

## Files

### play-video-segment.html

Try to solve the problem of caching a video segment and play it offline.

To use, do:
```bash
npm install connect
node bin/http-server
```

In Firefox, you need to activate the Media Source Extensions API. Go to `about:config` and set
`media.mediasource.enabled` to true.

Then, point your browser to `http://localhost:3000/play-video-segment.html`.

### prefetch-video.html

Prefetch a video and know exactly how much is loaded using XHR.

### media-fragments-uri.html

An example of the Media Fragment URI you can use to see the HTTP headers involved.

### video-events.html

Log the list of all events fired in order by media elements.
