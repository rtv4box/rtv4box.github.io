---
layout: default
---

# **Audio in Multimedia**
**February 20th, 2023**

<audio id="buzzer" src="./assets/audio/buzzer.mp3" preload="auto"></audio>
<audio id="ding" src="./assets/audio/ding.mp3" preload="auto"></audio>
<audio id="rock" src="./assets/audio/rock.mp3" preload="auto"></audio>

## Background Music
<button onclick="(function() {
    var x = document.getElementById('bgMusic');
    if (x.style.display === 'none') {
        x.style.display = 'block';
        document.getElementById('rock').play();
        document.getElementById('rock').loop = true;
    }
    else {
        x.style.display = 'none';
        document.getElementById('rock').pause();
        document.getElementById('rock').loop = false;
    }
})();">Toggle Music</button>

<div id="bgMusic" style="display:none;">
  Background music can help capture the attention of your audience, but make sure that the music fits with the content and theme of your website.
</div>

## Adding Sound to Elements on Your Website

<button onclick="document.getElementById('ding').play();">Correct</button>
<button onclick="document.getElementById('buzzer').play();">Incorrect</button>