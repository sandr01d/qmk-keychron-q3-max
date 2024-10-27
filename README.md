# Keychron Q3 Max Keymap

Custom keymap for the Keychron Q3 Max.

> [!IMPORTANT]
> At the time of writing this, the firware for the Q3 Max and other wireless keyboards from Keychron has not yet been upstreamed to the QMK project. You have to compile the firmware from the [`wireless_playground` branch of Keychrons fork](https://github.com/Keychron/qmk_firmware/tree/wireless_playground).

## Features

* Adds number keys to the home row of the `WIN_FN` layer to allow fast number typing without a numpad.
* Uses [layer tab toggle](https://docs.qmk.fm/feature_layers#switching-and-toggling-layers) for the `Fn` key and activate it with 2 taps for faster switching to the `WIN_FN` layer.
* Enables [Caps Word](https://docs.qmk.fm/features/caps_word)
* Uses [tap dance](https://docs.qmk.fm/features/tap_dance#tap-dance-a-single-key-can-do-3-5-or-100-different-things) to control music with the rotary knob:
    * **Single tap:** Play/Pause track
    * **Double tap:** Next track
    * **Triple tap**: Previous track