# Turn Timer · Canvas

A lightweight, high-performance countdown timer web application built entirely on a single HTML5 Canvas element. Designed with smooth touch handling, custom Web Audio API sounds, and responsive scaling, it works seamlessly across desktop and mobile browsers.

---

## Features

* **HTML5 Canvas UI**: Smooth, resolution-independent rendering scaled to fit any device or window size.


* **Web Audio API Sound Engine**: Custom synthesised audio cues including short warning beeps during the final 5 seconds, an uplifting start bing, and a rich multi-harmonic horn at completion.


* **Precise Deadline Tracking**: Uses absolute timestamp deadlines (`Date.now()`) to prevent timer drift, even when backgrounded or throttled by mobile browsers.


* **Flexible Input Controls**:
* Quick preset buttons for 30 seconds, 1 minute, and 2 minutes.


* Step buttons (`+` / `−`) for fine-tuning minutes and seconds.


* Direct numeric input support via a hidden input overlay optimized for mobile keyboards (`inputmode="numeric"`).




* **Keyboard Shortcuts**: Space/Enter to start or reset, `R` to restart, and `Escape` to return to setup.



---

## Quick Start

1. Save the code as an HTML file (e.g., `index.html`).


2. Open the file in any modern web browser.


3. Set your desired countdown duration using the presets or adjustment buttons, then tap **START**.
