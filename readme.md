# StreamByter Velocity Scaling/Boosting Script

When using an external MIDI keyboard (fully-weighted digital pianos in particular) the velocity curve and range of that keyboard may not extend fully to the range expected by some piano apps. Apps that do not include adequate velocity curve/range editors can make it unnaturally difficult to play notes at medium/loud volumes with your keyboard.

This is a simple [StreamByter](https://audeonic.com/streambyter/) stript that applies a multiplier to the velocity from your keyboard, which you can then route to your piano app. Values are capped to the maximum velocity of 127 (7F).

The scaling factor in the script is 160%. You can tune that to your own taste by changing that scale value (L0). Numbers less than 100 will reduce the range of velocity if you prefer to dampen it.

[View the script.](./StreamByter-VelocityBoost.txt)

### References

* [StreamByter script documentation](https://audeonic.boards.net/board/14/university)
* [Other custom scripts](https://audeonic.boards.net/board/12/boutique)
