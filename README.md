# Description

A simple Linux sound meter based on ALSA API. Here's the demo on [youtube](https://www.youtube.com/watch?v=KgapjPoEeJI). The noisy sound is generated by a guitar tuner,
and as it gets louder, the dB and peak value displayed on the screen gets
larger.

# Compile

Just run `make`, it should work (I hope).

# Noted

I wrote this program few years ago and I haven't wrote C and ALSA stuff for a
while, so I might not able to answer your question, but I'll do my best if you
got any! :)

Please visit [ALSA project - the C library reference](http://www.alsa-project.org/alsa-doc/alsa-lib/pcm.html) for more information. This code is based on
`alsa-lib/test/pcm_min.c`.

