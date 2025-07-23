# starwars-coke-ar

Star Wars and Coca-Cola HoloCreator AR Experience

<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]

<h2>Client</h2>
<p>Contract: Subvrsive</p>
<p><b>for The Coca-Cola Company and Lucasfilm</b></p>

<br />
<div align="center">
  <a href="https://github.com/victorcappa/starwars-coke-ar">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Star Wars Coca-Cola HoloCreator</h3>

  <p align="center">
An immersive WebAR experience that invites users to choose - from Jedi, Sith, Pilot, Trooper or Twi'lek  — and bring holographic Star Wars characters to life directly from limited-edition Coca-Cola packaging.
  </p>
</div>

---

## Visuals

![splash 1](https://github.com/user-attachments/assets/a1eb4dcc-196a-4792-af22-5b322bd825d7)
![splash 2](https://github.com/user-attachments/assets/de683e5a-50aa-4546-b88d-a97fcb11888b)






---

## About The Project

This mobile experience transforms Coca-Cola cans and bottles into portals for augmented reality. Users scroll through a cinematic introduction, select a Star Wars character, and launch an interactive hologram in the real world — all directly in their browser.

Built using Three.js and React, and powered by 8th Wall’s AR engine, the project merges storytelling and real-time 3D to create a fluid and responsive interface that feels more like a game than a webpage.

---

## Key Features

* **Scroll-Based Animation:** Smooth transitions and storytelling moments tied to scroll position using GSAP and custom animation logic.
* **Character Carousel:** Users explore iconic characters like Jedi, Sith, Twi'lek, Trooper, and Pilot through a rotating holographic selector.
* **Live Holograms in AR:** After choosing a character, users activate a real-time hologram that appears in their physical space.
* **Optimized for Mobile:** Designed to perform reliably across a wide range of mobile browsers and devices.
* **Sound, Motion, and Visual Effects:** The experience layers audio cues and subtle post-processing to elevate immersion.

---
Great — your current version is solid and clear. Here's how you can integrate a **“Challenges”** section that highlights your **technical decisions and problem-solving** — keeping the language accessible, but still showing your skills.

---

## Challenges

Throughout development, we faced several creative and technical challenges — especially considering the need to support real-time 3D on mobile web:

* **Performance on Low-End Devices:** To keep the experience smooth across a wide range of smartphones, we implemented texture compression, optimized PNG sequences, and used batching strategies to reduce memory usage.

* **Battery-Saving Mode Detection:** Some devices throttle GPU performance when in low-power mode, affecting animation speed and frame updates. We built a system to detect this condition and gracefully adapt visual fidelity.

* **Post-Processing Tuning:** Real-time effects like glow and transparency had to be finely tuned to balance quality with mobile browser constraints. We iterated on custom materials and removed features that didn’t scale well on older phones.

* **Asset Management:** All character animations were built from hundreds of texture frames. We used dynamic loading and lazy initialization to avoid blocking the main thread or increasing load time.

* **Gesture + Scroll Navigation:** Ensuring smooth scroll transitions that didn’t conflict with native gestures on mobile browsers required careful timing and fallback logic for both Android and iOS environments.

---

## Impact

* 🌍 **Global Campaign** in partnership with Lucasfilm and Coca-Cola.
* 📱 **Millions of Interactions** across multiple territories.
* ⚡ **Fast & Accessible** — no app required; launched instantly from a QR code.
* 🎥 **Shared Online** via social media, further extending the reach.

---

## License

All intellectual property is owned by Lucasfilm and The Coca-Cola Company.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Contact

Reach out - <a href="mailto:cappacurta@gmail.com">Victor Cappa</a> <a href="https://www.linkedin.com/in/victor-cappa-50839788/">Linkedin</a>

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/victor-cappa-50839788/

