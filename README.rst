**********************************
Play video on Dreambox for Android
**********************************

Send videos from your phone's browser to dreambox satellite receiver.

This app adds an entry to the android browser's share menu.
It sends the URL to a configurable `playVideoOnDreambox proxy`__ server,
which instructs your Dreambox to play the video.

With this, you can browse youtube or other video sites and play the videos on
your satellite receiver.

__ https://github.com/cweiske/playVideoOnDreamboxProxy


Thanks to https://github.com/matgoebl/Send2URL on which this app is based on.


Errors
======
Error reporting in this app is very sparse.

Not Acceptable
--------------
If you get a "Not Acceptable" error, then the proxy could not extract
the video URL from the URL that was sent to it.

The stock browser on Android 6 only seems to send the main URL (domain)
when sharing, and misses the path.
The video cannot be extracted, and boom.

A workaround is to reload the website on android by pulling it down,
and share then.
Videos on youtube and media.ccc.de are correctly played then.
