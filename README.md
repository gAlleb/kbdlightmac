Kbdlight
========

kbdlight is very simple application that changes MacBook 12 inch 2017 (Macbook10.1) keyboard
backlight level.

While usable standalone, the main goal is for it to be used by other
applications, including things like sxhkd or xbindkeys.

Usage
-----
Usage is quite simple:

    kbdlight up [<percentage>]|down [<percentage>]|off|max|get|getp|set <value>

`getp` returns the percentage of brightness for the value.
`percentage` should be an integer between 0 and 100.
`value` should be an integer between 0 the maximum brightness value (usually
255, but this *may* vary).

