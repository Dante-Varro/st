# st - Simple Terminal (Custom Fork)

My personal customized build of `st`, the simple terminal emulator for X. 

---

## Features & Patches Included
* **`anysize`** — Allows the terminal window to resize freely to any pixel dimension rather than snapping strictly to character grid increments.
* **`alpha`** — Adds adjustable window transparency.
* **`scrollback`** — Enables history scrolling with the keyboard/mouse, reflowing text dynamically when the window size changes.
---

## Installation

Make sure you have Xlib header files installed on your system. 

```sh
# Clone your repository (or navigate to your local folder)
git clone [https://github.com/Dante-Varro/st.git](https://github.com/Dante-Varro/st.git)
cd st

# Build and install (may require sudo depending on your prefix in config.mk)
sudo make clean install
