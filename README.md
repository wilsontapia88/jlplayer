# jlplayer
Player de vídeo personalizado em HTML5 e Javascript

# Inclua esta linha na <head> do seu documento

<link rel="stylesheet" href="https://www.seusite.com/jlplayer/jlplayer.min.css">

# Inclua esta linha antes de fechar o <body>
<script src="https://www.seusite.com/player/jlplayer.min.js" async></script>


# Basta chama a tag <video> com class="jlplayer-video" e prontinho....

<video preload="none" class="jlplayer-video" poster="https://www.seusite.com/capa-do-video.jpg">
     <source src="https://www.seusite.com/video.mp4" type="video/mp4">
    <track kind="captions" src="https://www.seusite.com/legenda.vtt" default>
</video>
