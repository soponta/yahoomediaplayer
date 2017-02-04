# yahoomediaplayer

A version of the yahoo media / web player that can be embedded to play media, in particular mp3 files.
Basic Usage
1 Add the yahoomedia folder in this repository to your sites relevant js folder
2 Add the following to pages that have mp3 files on your site

<script >
var YMPParams = { autoplay:false,volume:1, assetsroot: '{{ site.url }}/assets/js/yahoomedia', defaultalbumart:"{{ site.url }}/images/victorian_carol_singers_silouette_32.png" };
</script>

<script  src="{{ site.url }}/assets/js/yahoomedia/music-player.min.js"></script>
