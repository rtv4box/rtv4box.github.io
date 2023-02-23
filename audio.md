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

## Two Types of Audio

### Digital Audio

Digital audio as the name implies, is sound stored as a digital representation. The data is made up of sound waves, also known as samples.

There are 2 factors that affect the overall quality of the digital audio.

**Sampling Rate** refers to the number of samples that is used as data by the digital audio every second.

**Bit Depth** is also know as sample size. It refers to the number of bits used in each sample of the digital audio.

### MIDI Audio

Musical Instrument Digital Interface (MIDI) audio is used to connect devices that create and output sound, including computers, samplers, and electronic musical instruments.

MIDI allows for the transmission of notes or sequences of notes between electronic musical devices.

## Adding Sound to Elements on Your Website

Below is a short quiz, you will know if you got the right answer based on the sound being played.

1. The data for digital audio is stored in the form of samples.

    <button onclick="document.getElementById('ding').play();">True</button>
    <button onclick="document.getElementById('buzzer').play();">False</button>

2. The 2 factors that affect the quality of digital audio are sampling rate and file size.

    <button onclick="document.getElementById('buzzer').play();">True</button>
    <button onclick="document.getElementById('ding').play();">False</button>

3. MIDI stands for Musical Instrument Digital Interface.

    <button onclick="document.getElementById('ding').play();">True</button>
    <button onclick="document.getElementById('buzzer').play();">False</button>

### Audio Used

The audio used for this page are all under the Creative Commons 0 License: [Background Music](https://freesound.org/people/T_roy_920/sounds/425556/), [Correct Audio](https://freesound.org/people/Daronoxus/sounds/393633/), [Incorrect Audio](https://freesound.org/people/SomeoneCool15/sounds/419086/)