# 🛸 Echoes of the Unknown — QnQSec CTF Writeup

<p align="center">
  <img src="Screenshot%202025-10-20%20091945.png" alt="Challenge screenshot" width="600">
</p>

---

##  Challenge Description

When I listened to the file, it just sounded like static noise.  
Because it was in the **Steganography** category, I suspected there might be hidden information inside the audio spectrum — something that can be visualized using **Sonic Visualizer**.

---

##  Approach

At first glance, the challenge file sounded like static noise.  
Since it was under *Steganography* and mentioned “random noise”, I suspected that the data might be visually hidden inside the **spectrogram** representation of the audio.

---

##  Tools Used

-  **Sonic Visualizer** — to visualize the frequency spectrum  
- Opened the `.wav` file:  
  **File → Import → alien.wav**
- Added **Waveform** and **Spectrogram** layers for deeper inspection.

<p align="center">
  <img src="images/Screenshot%202025-10-20%20091628.png" alt="Spectrogram" width="500">
</p>

<p align="center">
  <img src="images/Screenshot%202025-10-20%20091617.png" alt="Waveform" width="500">
</p>

---

## 🔍 Discovery

After zooming into the **right section** of the spectrogram,  
A faint but readable **text flag** became visible embedded in the frequency visualization!

<p align="center">
  <img src="images/Screenshot%202025-10-20%20091651.png" alt="Visible Flag" width="600">
</p>

---

## 🏁 Flag

```bash
QnQSec{h1dd3n_1n_4ud1o}
