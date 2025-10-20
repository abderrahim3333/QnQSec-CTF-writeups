![Challenge screenshot](Screenshot2025-10-20091945.png)

**Challenge Description:**

When I listened to the file, it just sounded like static noise.
Because it was in the Steganography category, I suspected there might be hidden information in the audio spectrum — something that can be visualized using Sonic Visualizer.


**Approach:**

At first glance, the challenge file sounded like static noise. Since it was in the Steganography category and mentioned “random noise”, I suspected there might be hidden data inside the audio — possibly encoded visually in the spectrogram.

**Tools Used:**

Sonic Visualizer — to visualize the frequency spectrum

Opened the .wav file inside Sonic Visualizer: File → Import → alien.wav




Add Waveform and Spectrogram Layer
![Waveform](../image/Screenshot2025-10-20091617.png)          ![Spectogram](../image/Screenshot2025-10-20091639.png)


**After zooming into the right section of the audio, the flag text became visible inside the spectrogram!**

![Visibleflag](QnQSec-CTF-writeups/image/Screenshot2025-10-20091651.png)


`QnQSec{h1dd3n_1n_4ud1o}`




