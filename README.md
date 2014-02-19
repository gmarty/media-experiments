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
