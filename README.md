screentoggle
=========

A simple script to switch between various monitor combinations.

Installation
---

Run in current location or copy to a $PATH location and run:

    screentoggle

Usage
---

By default the modes in order are:
   
    1. Laptop primary (LVDS1) + VGA1
    2. Laptop primary (LVDS1) + HDMI1
    3. VGA1/HDMI1 only
    4. LVDS1 only


It is easy to bind a key(combo) to run the script.

In my sxhkdrc:

    XF86Display
        screentoggle

