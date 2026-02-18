# ⏳ LIFE TIME TERMINAL (PROJECT INCEPTION)

> *"You're waiting for a train. A train that will take you far away..."*

### 🔴 [LIVE SYSTEM PREVIEW](https://thegowsik.github.io/life-time-terminal/)

**Life Time Terminal** is a cinematic, browser-based "Reality Check" dashboard inspired by the visual aesthetics of the movie *Inception* and retro CRT monitors. 

It serves as a digital **Memento Mori**—a reminder that time is ticking. By inputting your age, the system calculates the exact duration of your existence across multiple dimensions (seconds, weeks, years) while playing an immersive soundtrack.

---

## 🖥️ Interface
*(You can add a screenshot of your site here later)*

The interface is designed with a **Cyberpunk / Hacker** aesthetic:
- **Neon Cyan Text:** `#00FFFF` (Standard Terminal Color)
- **CRT Scanlines:** Simulated monitor refresh lines.
- **TV Static:** Subtle background noise for realism.
- **Blinking Cursors:** Old-school terminal feel.

## ⚡ Features

* **Real-Time Chronometer:** Tracks your life stats dynamically.
    * Years, Months, Weeks, Days
    * Hours, Minutes
    * **Total Seconds Lived** (Updates every second)
* **Dynamic Quote Engine:** The system talks to you. It reads your stats and generates quotes like *"You have survived 180,000 hours..."*
* **Immersive Audio:** Hidden audio player designed to loop the *Inception* soundtrack.
* **Responsive Design:** Works on mobile and desktop (Press `F11` for full immersion).

---

## 🚀 How to Run Locally

If you want to run this on your own machine:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/thegowsik/life-time-terminal.git](https://github.com/thegowsik/life-time-terminal.git)
    ```
2.  **Add the Audio:**
    * The code looks for a file named `inception.mp3`.
    * Add your favorite MP3 file to the root folder and rename it to `inception.mp3`.
3.  **Launch:**
    * Open `index.html` in any web browser.

---

## 🛠️ Technologies Used

* **HTML5:** Structure and Audio API.
* **CSS3:** Flexbox, Grid Layout, Keyframe Animations (Blink/Fade), and Pseudo-elements for CRT effects.
* **JavaScript (ES6):** * `setInterval` for the atomic clock.
    * Math logic to convert Age into Seconds/Weeks/Months.
    * DOM manipulation for the typewriter effects.

---

## 📂 Project Structure

```text
/
├── index.html       # The main terminal interface
├── inception.mp3    # Background audio (Not included in repo)
└── README.md        # This documentation
