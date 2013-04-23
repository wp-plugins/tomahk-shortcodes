=== Tomahk Embed ===
Contributors: G.Breant 
Tags: Tomahawk, shortcode, toma.hk
Requires at least: 3.5
Tested up to: 3.5.1
Stable tag: trunk

Use shortcodes to embed playlists, albums and single tracks from toma.hk.

== Description ==

Tomahk shortcodes allows you to embed playlists, albums and single tracks from toma.hk.

=== Embed a playlist ===

Use this code : [twk-playlist]TOMAHK_PLAYLIST_URL[/twk-playlist] where TOMAHK_PLAYLIST_URL is the url of your playlist (eg.: http://toma.hk/p/R222222M).
You can also specify several arguments :

* width (the embed width) - default is 550
* height (the embed height) - default is 430

Like this : [twk-playlist width="550" height="430"]TOMAHK_PLAYLIST_URL[/twk-playlist]

=== Embed an album ===

Use this code : 
[twk-album artist="ALBUM ARTIST" title="ALBUM TITLE"][/twk-album]

Or use:
[twk-album]TOMAHK_ALBUM_URL[/twk-album]where TOMAHK_ALBUM_URL is the url of your album (eg.: http://toma.hk/album/The+Smashing+Pumpkins/Oceania).

You can also specify several arguments :

 
* width (the embed width) - default is 550
* height (the embed height) - default is 430
* Like this : [twk-album width="550" height="430"]TOMAHK_ALBUM_URL[/twk-album] 

=== Embed a single track ===


Use this code : 

[twk-track artist="TRACK ARTIST" title="TRACK TITLE"][/twk-track]

Or use:

[twk-track]TOMAHK_TRACK_URL[/twk-track]where TOMAHK_TRACK_URL is the url of your track (eg.: http://toma.hk/Belaaaab).

You can also specify several arguments :

* width (the embed width) - default is 200
* height (the embed height) - default is 200
* autoplay (true|false) - default is true
* disabled resolvers - default is false

Like this : [twk-album width="200" height="200" autoplay=true disabled_resolvers="Soundcloud,Officialfm"]TOMAHK_ALBUM_URL[/twk-album] 
 