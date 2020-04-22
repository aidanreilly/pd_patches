
This readme file should describe what this library does, where to find more
info and get help, and any specific instructions for building it.






- locusamp~   : streaming client

*****************************************************************************

locusamp~ Usage: locusamp~ <channels> <buffer size>

<channels> number of outlets~, default 2, up to 64
<buffer size> per channel of the circular buffer in Kilobytes, default 2048 KB.

Leftmost outlets: sound outlets, according to creation argumemts, or 2 by default
Center outlet: status message (error, warning, metadata, codec, samplerate, channels, bitrate, format).
Rightmost outlet: connection state. 0: disconnected, 1: connected


Knowned supported file format: Ogg Vorbis, MP3, Opus, AAC (HE-AAC), WAVE, AIFF, FLAC, WebA, Au.