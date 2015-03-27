# skin.umega
skin.µmega

Plex Home Theater skin based on Maximinimalism by theDeadman
skin.maximinimalism

Maximinimalism is a skin for Kodi 14 (Helix) by theDeadman.

Maximinimalism is built from scratch to provide a simple, elegant and fast media browsing experience for home tv / remote setups. Well suited for lower power devices such as the Raspberry Pi.

Skin is 1920x1080p native, will work in other resolutions as well.


Custom Menu Items URL shortcuts how to:

First 3 channels need a plugin name ie. youtube, iplayer, iTunes, vimeo, lmwt etc (get from plex logs or plugin dir .py code)

Next 6 use complete URL (Of course Plex (Windows Kodi) doesn't let you paste in keyboard box....)

OK,so here we go.

Get this: http://www.hot-keyboard.com/docs/paste_help.htm

Enable PHT debug logging, start PHT and go to the channel and where you want shortcut to link to.

Close PHT, goto log and find the URL, something like this:

15:31:13 T:4516 DEBUG: CPlexFilterManager::loadFiltersFromDisk loading filters for section plexserver://be947b30de7253zzzzzzcb4fc15db35684dffb09/video/youtube/parsefeed?url=http%3A%2F%2Fgdata.youtube.com%2Ffeeds%2Fapi%2Fstandardfeeds%2FREGIONID%2Fmost_viewed%3Ftime%3Dtoday&title=Most+Viewed

then we need this bit plexserver://be947b30de7253zzzzzzcb4fc15db35684dffb09/video/youtube/parsefeed?url=http%3A%2F%2Fgdata.youtube.com%2Ffeeds%2Fapi%2Fstandardfeeds%2FREGIONID%2Fmost_viewed%3Ftime%3Dtoday&title=Most+Viewed

Open Hot app, new macro, choose paste, select play keys, paste your URL, choose hot key. Repeat for others.

Enter PHT settings, channels, use URL type channels, use hotkey to paste. Done!
