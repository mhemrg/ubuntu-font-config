Ubuntu Font Configuration
=========================

Mac-like font rendering on Ubuntu, including decent results for Japanese, Arabic, etc.

* Get the following fonts:

  * [Droid Sans Fallback](http://en.wikipedia.org/wiki/Droid_%28font%29)
  * Tahoma (from Windows)
  * Arial Unicode (from Windows)
  * MS Core Fonts (package `msttcorefonts`)

* In the font preferences GUI, turn off hinting and turn on subpixel rendering.

* Replace /etc/fonts with this repository.

* Restart the X server (or reboot).
