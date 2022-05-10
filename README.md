# Rickroll-on-any-page
This script makes it modify the images and sound of any page so you can rickroll your friends when you present screen or yourself :I

```
const images = document.getElementsByTagName("img"); for (var i = 0, l = images.length; i < l; i++) { images[i].src = "https://c.tenor.com/WHrgX-FXJjwAAAAM/rickroll.gif"; }; const typeWriter = new Audio("https://www.myinstants.com/media/sounds/rick-ogg_gwcjskk.mp3"); typeWriter.volume = 0.6; typeWriter.play(); setTimeout(() => {typeWriter.pause(); window.location.reload()}, 9000)
```
