# Lua

I'm not going to lie, most of these are for LÖVE. On the subject, http://easings.net/ has a list of all tweening modes.

## [Boipushy](https://github.com/adonaac/boipushy)

Simplifies input handling in LÖVE.

## [Classic](https://github.com/rxi/classic)

A class module for lua. Include classic.lua

## [Enhanced Timer](https://gist.github.com/anonymous/07496ce1500fb80a9b08c77c278f017a)

Supports the addition of event tags. So in this case, the event '''r_key_press''' is attached to the timer that is created whenever the r key is pressed. If the key is pressed multiple times repeatedly, the module will automatically see that this event has other timers registered to it and cancel those previous timers as a default behavior, which is what we wanted. If the tag is not used then it defaults to the normal behavior of the module. You can download this enhanced version here and swap the timer import in main.lua from libraries/hump/timer to wherever you end up placing the EnhancedTimer.lua file

## [Hump](https://github.com/vrld/hump)

Has a bunch of utilities for LÖVE. Refer back to the original repo for the docs.

* gamestate.lua: Easy gamestate management.
* timer.lua: Delayed and time-limited function calls and tweening.
* vector.lua: 2D vector math.
* vector-light.lua: Lightweight 2D vector math (for optimisation purposes - leads to potentially ugly code).
* class.lua: Lightweight object orientation (class or prototype based).
* signal.lua: Simple Signal/Slot (aka. Observer) implementation.
* camera.lua: Move-, zoom- and rotatable camera with camera locking and movement smoothing.
